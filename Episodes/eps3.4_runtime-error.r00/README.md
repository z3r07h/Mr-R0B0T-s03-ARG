eps3.4_runtime-error.r00
========================

Preface
-------

A very interesting episode in retrospect. What makes it particular amazing IMO is that the entire episode is shot in one take! This does pose a bit of a problem with camera focus for a lot of elements such as employee names. However, the focus is definite sharp in places it needs to be in order to facilitate the ARG. 



Preliminary stuff from previous episodes
----------------------------------------

- some commands being used on the UPS server
- Another MAP - behind Philip Price, although this is a map of the world (most of it)

Observations
------------

- 01m48s Strange static noises
- 01m49s **Aller Anfang ist schwer. Anfangen ist leicht, beharren eine Kunst.** which means the beginning is difficult, to begin is easy, perrsistence is art. The second part is a german proverb attributed to Friedrich Heinrich Wilhelm Körte (1861).  
- 03m52  **43rd floor** Elliot works on the 
- 05m25s **Samar Swailem** The name of the guy next to Elliot is revealed 
- 06m52s More employee names but shot is moving too fast to focus in properly
- 07m43s **e-corp-usa.com/password/reset** site seen on Elliot's screen
- 08m04s **072391** Elliot's employee number (found this already through elliot's QR code badge easter egg see (LINK)
- 08m49s **192.251.68.232** IP seen as Elliot uses PuTTY to connect over port 22 (standard SSH port)
- 08m55s **Port 5601** is the port the kibana instance is running on, on the same computer 
- 08m55s **samsepi01** Sam Sepiol - Elliot's login for the **elkbox** this is the same username he had in Season 2
- 08m55s **192.251.68.232:5601/app/kibana#/dashboard/Priority-Host-Monitoring** full kibana link
- 09m13s **Bobby/Bobbi Fulltern** Samar confirms her name (TODO Update previous episode notes)
- 10m12s **Floor 11** has the best bathrooms apparently, according to Samar
- 10m33s Strange symbols in the hallway, maybe perfectly natural, not sure at this time. 
- 10m57s Elliot says there's an IT emergency on 29 - more numbers. 
- 11m50s **Floor 44 Stairwell F** Elliot goes up to
- 12m33s **Fred Watson** 
- 12m45s **Patrick Head**
- 12m57s **Barry Caswith**
- 13m49s **Edie Hughes** And oh my gosh, this lady ROCKS, I wish people I met in offices could implement security procedures as well as she can. Props to Esmail&co for being a non-stereotype team. Lovely stuff. AND SHE LOCKS HER WORKSTATION WHEN NOT AT HER DESK. PURE GOLD. 
- 14m41s We can hear what Fred is listening to on his headphones. Need to find the name of the song. 
- 15m15s **www.e-corp-usa.com** main website 
- 15m21s **admin** kibana login username - password is 10 characters 
- 15m24s **Frank Bowman** a user seen in the kibana dashboard
- 15m24s **\\csat-fs01** a fileserver on the ecorp-network (FQDN csat.e-corp.usa.com) - D$ is the share (D:\)
- 15m24s **mimi.exe** seen in kibana dashboard - looks like someone was using mimikatz to grab kerberos tickets from c:\temp\tickets
- 15m38s **Floor 23** the floor Frank Bowman works on
- 17m11s **Shaun** - Head of Sales
- 17m14s **Dave Kennedy** Elliot introduces himself as this guy. (He *worked with Craig on the Q4 push*)
- 17m31s **4412C** the room the meeting is in (Elliot also mentions room 4312C)
- 19m57 **Vera** a glimpse into Elliots mind, and his 3rd alter ego who has previously told him to walk away from Vera
- 21m32s Renaissance hotel across from the ecorp building (Screenshot in Extras)
- 21m39s one of the protestors signs says Up(arrow) F, Down(arrow) E.
- 21m43s Aries Nail is another name seen across from the ecorp building
- 26m34s Looks like the rioters/dark army cadets like the letter X as well. 
- 27m43s Another X
- 28m52s **Elliot's Instructions** from the dark army is clearly in focus - there is also a QR code on the ID badge - it's Frank Bowman. Instructions are listed in Instructions.md file
- 29m16s **Floor 41** Angela's floor
- 29m54s **Floor 32** Security guard get's on lift
- 31m02 **QR Code** A Clearer shot of Frank Bowman's ID badge
- 34m21s Some interesting details, such as extension numbers on the notice board.
- 35m28s **QR Code** very blurry, screenshot sorry. Employee is LYDIA RILEY
- 36m42s **192.251.68.233**  & **192.251.68.234** info from the CSAT server screen
- 40m33s **Marlinspike** Codename used by Irving on phone with Angela
- 40m33s **Moxie** Angela's codename reply


Evidence
--------

**Prelim UPS commands**
![ups_commands](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/00-commands.jpg)

**World map**
![map](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/00-map.jpg)

**Elliot's working floor**
![elliot_floor](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/01-Elliot_floor.jpg)

**Samar Swailem**
![samar](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/02-samar_swailem.jpg)

**Blurry Ecorp names**
![ecorp_names](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/03-more_ecorp_names.jpg)

**Password reset site**
![password_reset](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/04-password_reset.jpg)

**Kibana dashboard 1**
![kibana_1](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/05-update_failure.jpg)

**192.251.68.232**
![telnet](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/06-telnet_site.jpg)

**samsepiol and kibana URL**
![kibana_login](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/07-sepi0l_and_kibana.jpg)

**Strange symbols (On the right of the picture)**
![symbols](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/08-strange_symbols.jpg)

**Floor 44**
![floor_44](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/09-floor44.jpg)

**Fred Watson**
![fred](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/10_fred_watson.jpg)

**Patrick Head**
![patrick](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/11_patrick_head.jpg)

**Barry Caswith**
![barry](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/12-barry_caswith.jpg)

**Edie Hughes**
![edie](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/13-edie_hughes.jpg)

**Main Ecorp website**
![ecorp_website](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/14-ecorp_website.jpg)

**kibana login**
![kibana_login](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/15-kibana_login.jpg)

**Frank Bowman**
![frank](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/16-frank_bowman.jpg)

**MORE Frank Bowman**
![mo_frank](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/17-more_frank_bowman.jpg)

**Shaun (Head of Sales)**
![shaun](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/18-shaun_sales.jpg)

**Mr Robot talks about Vera**
![vera](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/19-vera.jpg)

**X**
![X](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/20-X.jpg)

**Another X**
![mo_X](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/21-another_X.jpg)

**THE INSTRUCTIONS**
![instructions](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/22-instructions.jpg)

**Floor 32**
![floor_32](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/23-floor_32.jpg)

**Bowman QR code**
![bowman_qr](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/24-bowman-QR.jpg)

**Notice Board**
![notice_board](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/25-notice_board.jpg)

**Lydia Riley Badge/QR**
![lydia_badge](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/26-lydia_badge.jpg)

**CSAT Server screen**
![CSAT_server](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/27-CSAT_server.jpg)

**Moxie Marlinspike**
![moxie](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/28-marlin_moxie.jpg)

**Lydia Riley**
![lydia](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep5/Episodes/eps3.4_runtime-error.r00/screenshots/29-lydia_riley.jpg)


Interesting
-----------

- Fred Watson has a thing for Bernie (Sanders) could be a good angle for a password attempt
- Lots of floor numbers
- some other interesting numbers from Elliot's instructions **23-148**, **022350**
- par login - **zlon0101**
- Frank Bowman's password - **hidd3nlynx** is a reference to a hacker group (a serious hacker group) more info: https://www.symantec.com/connect/blogs/hidden-lynx-professional-hackers-hire
- There is a taxi in this episode (2 actually) before the coin riot starts, but the number is far to unfocused to read. 
- Ecorp extension numbers - Safety Hotline **3401**, ID help desk hotline **2219**, E corp security **791**
- The internal audit team is from DETROIT
- The codenames used by Irvings and Angela directly correspond to security researcher **Moxie Marlinspike** whom mainly deals with security of communications - pretty cool since they're using a phone at the time. More info on MM can be found here: https://en.wikipedia.org/wiki/Moxie_Marlinspike, https://moxie.org/, https://github.com/moxie0
- a Marlinspike is also a type of knot, since MM has a mariners license his psuedonym is probably derived from this. 

IPs & Sites Seen
----------------
- **e-corp-usa.com/password/reset**
- **192.251.68.232:5601/app/kibana#/dashboard/Priority-Host-Monitoring**
- **www.e-corp-usa.com**
- **192.251.68.233**
- **192.251.68.234**
- **192.251.68.232**



Ecorp Employees 
---------------
- Samar Swailem
- Fred Watson
- Patrick Head
- Barry Caswith
- Edie Hughes
- Frank Bowman *password: hidd3nlynx*
- Dave Kennedy (might be fake)
- Lydia Riley


6 Digit Numbers
---------------
- 072391
- 022350


CMDS
----

cfgpower -all
upsfwupdate -last

cd /usr/local/logstatsh-ups
ls 



TODO
--
- QR Codes
- base64/md5/try to decode the hashes seen in kibana dashboard **b9a4dac2192fd78cda097bfa79f6e7b2**, **28656e674bfa56253bc73ec81071363e**, **b8a9569a8a227f7e98eb297433d405da**, **1f038b87e8a1f84d89a74168e27a44a0**,

