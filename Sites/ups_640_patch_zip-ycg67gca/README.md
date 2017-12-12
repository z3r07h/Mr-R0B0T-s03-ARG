ups_640_patch_zip-ycg67gca
==

Solved
==

Full site link:

https://ycg67gca.bxjyb2jvda.net/files/ups_640_patch.zip

Original IP 192.251.68.232/files/ups_640_patch.zip

![main page](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/ups_640_patch_zip-ycg67gca/screenshots/01-file.jpg)

Description
--

The site goes to an entire page filled with base64. We can assume that this base64 is a representation of the file ups_640_patch.zip

The base64 file is in files

Investigation
--
 
**Credits to u/punkAB on reddit (ARGSociety) for a pretty masterful solve on this one**


so on the third line of the base64 raw there is a serious of capital letters that spell out complete words - this is pretty rare for anything encoded/encrypted as the level of randomness is supposed to mimic real life randomness. Entropy talks are beyond this discussion for now however punk noticed that on the third line there is the text **8DOWN5OVER**

Using this as a starting point punk then checked 8 lines down and 5 characters over, seemingly pointing to an innocuous string of capital letters **YTIAHOSRWCFSTAUUUTESTSTMNAA**

Hmm ok - well the story doesn't end there, scouring the rest of the encoded text there is also the word **RAIL** and the word **FOUR**.. to most people this would mean nothing but to seasons ARG'ers, CTF'ers and even just Cipher fans, this quite obviously points to a **RAIL FENCE** cipher - for more information I suggest you check out this article, as it does a great job of explaining it, and was actually part of another CTf/ARG - https://www.secplicity.org/2017/05/25/historical-cryptography-ciphers/

With that information punk put it all together to decode the long string of capital letters into YOUMUSTRUNTWICEASFASTASTHAT *you must run twice as fast as that* another Alice in Wonderland quote/reference

For reference here is a screenshot detailing what's been explained

![screenshot](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/master/Sites/ups_640_patch_zip-ycg67gca/screenshots/8DOWN5ACROSS.jpg)


