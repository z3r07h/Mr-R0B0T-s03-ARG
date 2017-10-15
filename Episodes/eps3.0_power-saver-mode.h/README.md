Changelog
--------
Sun 15 Oct 16:16:20 BST 2017 - Started



Lots of Juicy stuff seen in this episode (and heard maybe)


Observations
------------
- Irvings Auto Square "habla Espaniol" - NY10803 - car business card
- "Property of Josh Groban (2013)" - Sweater Elliot is wearing
- Who was the Neighbour of Elliot's that got evicted?
- Elliot has a strange mosaic in his apartment, with red and yellow colouring
- "Materialism and GrEEd are not my American values" posters everywhere
- People with VR headsets everywhere (perhaps foreboding some VR stuff or panderinng to the fan-theories about Elliot living in VR/Being a real life VM)
- 1984 (split in the middle by colouring)
- Picture of dog on wall (Spaniel?) "never forget"
- The Exit is above the Eye.. (?)
- "Poison the data" - perhaps links back to Alice in wonderland
- Nameservers on the ruxmsu9u dns page are different than on the maindomain.co website
- Domain K6F7241
-**computer 192.251.68.242:36268 | http://www.conficturaindustries.com/**
- Eliiot gets a connection from the slave at 10:29/10:30 pm approx - NY time
- file apc_hw05_aos_640.bin is also on the slave machine
- @26.34 - there is a sign that says "NOTICE, Building under 24 hour surveillance"
- Taxi number 7X23
- Following car number plate - UVM7482 (NY)(2015)
-** www.nyspcjis.net/menu/services/nyspncic2000/**
- Car registered to Brooklyn 11222
- New chr is called Detective Robert Abernethy/ Abernathy 
- Detective Badge number is 8301  - 19th Precinct
- DT asks Darlene to order a "couple of number 4s)
- Number 4 on redwheel barrow menu is - St louis _____ pork ___ 
- Lots of signs around saying things like FOR LEASE OR RENT, PRIME COMMERCIAL SPACE AVAILABLE
- FOR, SALE, OR, LEASE, 2000 Sq.Ft., On Ground FL, WILL, SUB-DIVIDE
- signs are mostly from E-Corp Real Estate Group
- more signs showing the NEW NBC show "Shift+Control"
- 34.48 Sound of the Tv newscaster is distorted
- Sign for Yankee Perfumes with a phone number - 21____7_24
- 35:31 Trumps audio and VIDEO visibly distorted
- Nods to Gideon Goddard 1963-2015
- **QR code on wall - leads to CV of Dylan C Roberts, which leads to "inside_e_corp" Subreddit **
- Dylan C Roberts reddit user name is BCC4LIFE
- CV is hosted at jobs.runpula.net (runpula base64 becomes ECOULA)
- part of the css used comes from a site call thingsthatarebrown.com - needs to be checked
- 718-555-0179 phone number on the bottom of one of the job adverts on the wall
- Shodan.io used by Mr Robot
- "org: "Evil corp" product: "Apache Tomcat"
- **compute.evil-corp-usa.com**
- Also information about AWS staging area and a session cookie
- between 49:55 - 50:40 approx there is another weird static sound distortion
- Bus number is 7016


Theories + Interesting stuff
----------------------------

Car yard business card says "habla Espaniol" Maybe this is a clue to translate the site to Spanish? 

Property of Josh Groban shirts are normally dated 2012! Something weird here

The Mosaic in Elliots apartment could be some sort of floor plan (credit: CD) 

Materialism and Greed are not my American Values.. This seems almost like a cryptic crossword clue. 
Therefore if M&G != American Values - What does? 'Values' here sticks out like a sore thumb, but what are American Values.. HEX, RGB? Something else I bet

Need to find someone (as Im lazy) to put the sound distortions noticed into an analyser to see if there's anything hidden there

If we can get onto the MASTER (Tyrells) Machine at 10:29/10:30 perhaps we can get a connection from the slave machine (via rwwwshell). If so, the BIN file on their may be quite Easter Eggy

Also the video distortion at 35:31 seems highly suspect

r/inside_e_corp This is Insane.. IS this the hidden thing Sam E was talking about? It would make sense, considering so much of Reddit was focused on the previous ARGS and never noticed that there was an e-corp subreddit all along!
This thing is crazy, all made two years ago, which shows us how deeply they've thought about this story and it's main events. 
Two other crazy bits here 1) the subreddit also references another one called "Real Mystery Spot" which hints at parallel dimension stuff.. Which was one of the fan-theories. 
Also if We as fans found this two years ago, we would have been getting a glimpse of the future, also fueling the time travel theories. This is weird. I will say more about it in their own sections. 

There is a sign basically saying LOOK AT ME
it says **NOTICE - Building under 24 hour surveillance**
But it looks almost like some of those words could have easily fitted on a line together.. so I thought maybe we read the first letter downwards or are being steered in that direction.
Reading the first letter from top to bottom we get **BU2VS**
If we include each word instead we get **BU24HVS**

The FBI car is FOLLOWING the taxi, perhaps this means that UVM7482 (the car number plate) follows 7x23, smells like a subdomain to me
7x23.UVM7482

Shodan.io Screen shows a number of cookies - we might be able to hijack these to get a live session on the website.
Mr Robot is also looking for installation of Apache Tomcat - Of which older versions that expose the management console have huge vulnerabilities in. 





IP Address/Sites
----------------
192.251.68.218 > redirects to https://www.ruxmsu9u.net/

Nameservers now start with - ns1.ndns, ns215.ni (rest is obscured)
also other name servers can be seen with 2ns. and ns2. 

192.251.68.242:36268 | http://www.conficturaindustries.com/ 

Files
-----
apc_hw05_aos_640.bin


CMD used
--------
ls
shred -f -n 3 *

Crazy Ramblings
---------------

Abernathy in the Red wheel barrow shop when debating about his free milkshake.
"What constitutes a visit" - made me think of a website visit
"Do I have to go Home?" - 127.0.0.1 
"Is it time-based"  - perhaps indicating the time-based nature of the web exploit using the rwwwshell

Is the 36268 port used a representation of the word ROBOT? 

ECOULA was quite close to ECORP, so for completeness, the base 64 RUNPRP -> ECORP
