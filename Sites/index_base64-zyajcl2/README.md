index_base64-zyajcl2
==

Possibly Solved
==

Full site link:

https://zyajcl2.bxjyb2jvda.net/index

Information
--

This site (seen in episode 9) is just a base32/base64 text only page.

For sake of organisation the entire text can be found in the file 'base64'

Investigation
--

This file has a PK header, meaning it's a form of ZIP file.

**Credits to ARGSociety for the following information**

Decoding the base64 file will give you a corrupt zip - on linux you can still extract the file using dd. The image is of two roses. This time around I've left the original file format of .png as this is important. 

![corrupted_flowers](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/master/Sites/index_base64-zyajcl2/files/output.png)

When comparing this image to the stock image version of the same file there are some slight noticeable differences, particularly with some fuzziness/blurriness to the image. The heavily indicates that the image has been modified, not enough to change it completely but enough to hide extract data in it. For more information lookkup steganography, and LSB steganography. 

Utilising LSB (Least significant bit) steganography some text strings are revealed:  
```
johI8xS2mc{
  "h":"60e1c7c059dc85fe1125ad92c0e5ebde74f7e93ce502038a288bf5da39426943",
  "p":"qBqOR5VJJzgJERxpXZ4l2JXSQOthufVnAynQMROT"
}
```

Which looks like a piece of JSON, the starting string and the 'h' parameter have yet to find a use however the 'p' parameter can be used on garyhost as the password. 


