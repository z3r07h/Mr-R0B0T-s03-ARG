eps3.8_stage3.torrent
==

Preface
--

Another seemingly quite quiet episode.. lets see.

Observations
--

- 07m48s "From Hunted To Hero" - Tyrell Wellick Article
- 12m01s Romeo Evidence part 1
- 12m01s **102868** Case number
- 12m01s **108-71** Location of Seizure
- 12m19s **Serial numbers - see below** from Romero file
- 15m05s **108** number above door that Irving stops outside
- 22m47s **Weird mosaic** again, with the colours Red, Yellow, and Green being prominent
- 31m44s **Red, Yellow, and Orange** post-its over faces
- 32m00s **Red and Orange phones**
- 32m21s **828** Time on Angela's phone
- 32m53s  Dr Wang is playing/organising a weird card game
- 45m53s Elliot showing The Volatility Foundation pieces of code for doing deep memory forensics (in this case probably adding artefacts to a usb stick for his target)
- 45m53s **192.251.68.228/index** Ip in the Volatility code
- 45m53s **141924** 6 digits seen in code
- 45m53s **39238** Program PID
- 45m55s More code being exampled on Elliot's computer, using evince, and GDB for some reverse engineering
- 45m57s Elliot causing a Segmentation Fault to load his malicious code into
- 46m02s Elliot writing shell code into his binary. Might be worth trying to reverse this.
- 46m02s **ecoin_vuln_notes.pdf** malicious file Elliot is creating
- 46m50s **MAP** small one showing US infections from dark army malware I assume
- 46m54s **172.17.0.1**, **u1rbr0uz.net**
- 46m54s **192.168.5.11** garyhost address
- 46m54s **garyhost** Username Elliot logs into 172.17.0.1 with
- 46m57s **HUNTER2** A huge easter egg nod to a meme known as hunter2 - Looks like Elliots malware scraped passwords from the host and put them into a innocuous looking /dev/nu11 folder (normall on a unix/linux host this is meant to look like the dev/null folder which you can send any amounts of crap to and it'll just vanish)
in the folder is a keylog of events, first someone is typing an internal address, then the word garyhost, then they type their password but have to backspace a couple of times - therefore "huntr[BS]er3[BS]2" becomes "hunter2" =D
- 47m27s Seems like the Dark army infections are much greater than we saw before.



Evidence
--

**Tyrell Article**
![tyrell_article](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/01-Tyrell_article.jpg)

**Romero's Evidence**
![romero_evidence](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/02-Romero_ev1.jpg)

**Romero Serial Numbers**
![serial_nos](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/03-Romero_serial_numbers.jpg)

**Door Numbers 108**
![108](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/04-Door_number.jpg)

**Dom's FBI ID**
![dom_id](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/05-Dom_id.jpg)

**Elliot's Interesting Mosaic Again**
![mosaic](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/06-weird_mosaic_again.jpg)

**Red, Yellow, Orange Post-its**
![postits](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/07-Red_and_yellow.jpg)

**Angela's Coloured Phones**
![phones](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/08-phones.jpg)

**Time on Angela's Phone**
![angela_phone](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/09-Angela_phone.jpg)

**Dr Wangs Card Game**
![wang](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/10-wang_cards.jpg)

**Volatility Framework In Use**
![vol_framework](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/11-Volatility_framework.jpg)

**Elliot's Desktop While Coding**
![elliot_desktop](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/12-Elliot_desktop.jpg)

**SEGFAULT**
![segfault](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/13-Segfault.jpg)

**Elliot's Shellcode**
![shellcode](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/14-shellcode.jpg)

**Dark Army Map 1**
![map1](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/15-map1.jpg)

**Garyhost Details**
![garyhost](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/16-Garyhost.jpg)

**Hunter2 Easter Egg**
![hunter2](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/17-Hunter2.jpg)

**Dark Army Infections Map and CC server**
![dark_army](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/18-Dark_army_infections.jpg)

**Larger Infections Map**
![infections_map](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/ep9/Episodes/eps3.8_stage3.torrent/screenshots/19-Infection_map.jpg)

Interesting
--
**Romero Serial Numbers**  
BND7BZAFWWCUQ8J6  (ROM-01)
YCYVE6EMMGSP8A3M  (ROM-02)
5P8FF938V93HBWEX  (ROM-03)
57HLZDB4X446V4TP  (ROM-04)

**Hard Drive Details**
ST902504-EXA101-RK    (Model Number)
5QFGXNRD  (Serial Number)


Dom shows off a bunch of tattoo's in this episode that I don't think we've seen before.  
It kind of looks like Dom's ID badge has a sim-card in it.  
Doms passcode has 456 in it. it goes, bottom left, 456, (perhaps 9), then two unseen numbers


TODO
--
- Reverse Elliots Shellcode and see what's inside
