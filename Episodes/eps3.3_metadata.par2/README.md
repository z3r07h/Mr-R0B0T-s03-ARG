ep3.3_metadata.par2
===================

Preface
-------

On the surface this episode seemed a little quiet again for easter eggs. I have only given it a brief going over so this write-up is not as in depth as the others currently. In saying that some of the stuff garnered is pretty technical and v interesting (from a certain perspective)

Without further ado...

Observations
------------

- 04m45s  Comet Electric Van (check on this company)
- 07m35s  **278 Manhattan Av** Doms safe house address.
- 14m28s  **https://www.ecoin.services/manager** showing apache tomcat management page, Elliot is using an RCE exploit for struts2 to gain access to folders on the server
- 14m28s  **ecoinweb1l_access_log.2015-09-18.txt**  
- 14m28s  **192.251.68.224** (double check this against the website)
- 14m28s  For reference the apache page Elliot is looking at is https://struts.apache.org/docs/s2-016.html
- 19m34s **https://shipping.e-corp-usa.com/fin/01/App/Shipping?/Loginfs129/Manifest+all** Elliot using the shipping site. Still need to find a login for this afaik. 
- 19m37s **Ecorp shipping numbers** Also Elliot is logged in as **Administrator** meaning the login for the ecorp shipping site is "Administrator"
- 20m14s **091615** New filename that has appeared on Elliot's desktop  
- 22m17s **Mr Nore/Nori** Fsociety/Dark Army member identified by Dom 
- 23m52s **EUS2065** Number plate  
- 25m15s Notes on the back of the FBI whiteboard
- 26m08s - Darlene's desktop - She's downloading 1996 film Shazaam - mp4 release by HDMIRCO. Time 01:47 - Confirms **D0loresH4ze** as her handle. 
- 26m17s **Budapest at its Best** website Darlene is looking at.. will check but this looks like a legit website. https://gotoday.com/stw
- 27m19s **116292** numbers on street sign - Also there's another big X on the shutters behind where Elliot/Mr Robot is walking  
- 27m32s **116183** Number on street sign 
- 28m40s **4X89** Taxi number that Mr Robot and Angela get into  
- 28m58s **patrick.smith** is now the login being used (by Tyrell) for the shipping website (need to check this name against ecorp employees)
- 30m34s "Never appeal to a man's better nature, he may not have one" quoted by Mr Robot
- 41m39s **TAXI** number 4P56 or perhaps 4F56 drives past Price while he's on the phone to Angela - the sign on the top says "Groundhog Taxi"
- 43m57s 9:07am time on Angela's phone


Interesting 
-----------

- Irving is having his favourite (number 4) ribs from the redwheelbarrow menu  

- looks like the struts vulnerability is redirecting to /tmp/LWzHKDalYy & doing a canonical path lookup endinng in NwYGJa - therefore path to check for easter eggs will be **http://www.ecoin.services/struts2-blank/example/HelloWorld.action?redirect:/tmp/LWzHKDalYy**  - which should just point to **http://www.ecoin.services/tmp/LWzHKDalYy**

- In the background of the shipping screenshot you can see Elliot is also using Kibana, this is network logging/monitoring software and ties in with him saying that he had been "monitoring traffic and found an unpatched server" earlier in the episode 

- The phrase "Greed and materialism are not my american values" pops up again a number of times in this episode

- Colours Red Blue Yellow (And Green) seen on the streets

- Mr Robot and Angela go into East Broadway Station - When Darlene exits, theres a huge Green light on the station entrance. 

- Lots of RED items in the basement where Tyrell has been working, pipes, box lettering, lamp, shovel handle, bucket, and more. 


CMDs
----

List of GET/POST commands from Apache struts exploit. see Screenshot for now. 


URL Encoded items
-----------------

%24 = $
\u002f = / 


TODO
----

- Put java commands through compiler and see what the concatonations might look like  
- Cross reference number plates/Taxi numbers
- Check on Patrick Smith
- Try some basic admin passwords against shipping site
- 29m14s approx Tyrell smashes up his keyboard perhaps in an homage to Angry German Kid. 
- Find out where the quote about a man's better nature is from 

