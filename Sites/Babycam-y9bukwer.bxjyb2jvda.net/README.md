Babycam-y9bukwer.bxjyb2jvda.net 
==

Solved
==

Full site link:

https://y9bukwer.bxjyb2jvda.net

Original IP 192.251.68.238 

**Main page**
![main_page](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/Babycam-y9bukwer.bxjyb2jvda.net/screeenshots/01-stream_php.jpg)

Description
--

On page load we are presented with a babycam monitor that is not connected and so all we can see is static. However the source contains some interesting information. 
There's a function that does a GET request to stream.php

If we follow the url to stream.php (https://y9bukwer.bxjyb2jvda.net/stream/php) we reach a page that outputs the result of the display_stream() function in the source code. 

This gives us a really weird looking URL:  
{"streamdata":"valid","streamsrc":"\/6NYYVkW4nEpEia7NOm7j\/WDr8ug\/fXHPTo\/siDVEv\/rPFweY\/stream.gif"}

We can take out the extra backslashes and follow it to the gif. This image looks pretty benign at first, lets run a little forensics on it and see if we can see anymore. 

First things first since its a gif, and gifs are made up of lots of static images, there might be something hidden in one of the images. 

I went to picasion.com and got a gif breakdown - these static images are in files

Interestingly enough if you run the file through a hex viewer the string Netscape 2.0 sticks out. So I tried to view the site in chrome with a user-agent string that corresponds to netscape 2.x  **Well that definitely didn't work** cloudflare instantly banned me from accessing the site - dont worry though reseting the user-agent unbans you (in case you want to try)

**68 65 72 65** Putting the files through a java program called Stegsolve.jar, 05.gif when using the 'Gray bits' filter shows a set of 4 numbers 

Pretty obviously this is ascii hex table letters, which turns out to say: **h e r e**


**URL exposure**
![url](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/Babycam-y9bukwer.bxjyb2jvda.net/screeenshots/02-stream_php_info.jpg)

**h e r e**
![here](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/Babycam-y9bukwer.bxjyb2jvda.net/screeenshots/03-here.jpg)

**Credits to ARGSociety and Gamedetectives.net for the below information**
Each time you visit the site the gif that is loaded is randomised from a set of 4, each of the 4 holds a secret code. They are:

77 65 26 23 33 39 3b 72 65 - we're
61 6c 6c - all
6d 61 64 - mad
68 65 72 65 - here

making up the phrase *we're all mad here* a reference to Lewis Carroll's Alice in Wonderland.


