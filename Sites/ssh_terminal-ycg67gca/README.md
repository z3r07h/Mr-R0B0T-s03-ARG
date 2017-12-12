ssh_terminal-ycg67gca
==

Possibly Solved
==

Full site link:

https://ycg67gca.bxjyb2jvda.net/ssh/terminal/


Original IP 192.251.68.232

**Main Directories**
![main_shell](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/ssh_terminal-ycg67gca/screenshots/01-directories.jpg)

Description
--

This site is from ep3.4_runtime_error

A terminal screen that is Elliot loggin into the elkbox (automatically) to check the logstash logs

- We can use 'ls' command to list directory contents
- We can follow /usr/local/logstash-ups to see an entire list of logstash log results
- There is a /home path but it does not contain anything AFAIK


**Logstash Logs**
![logstash](https://github.com/z3r07h/Mr-R0B0T-s03-ARG/blob/sites/Sites/ssh_terminal-ycg67gca/screenshots/02-logstash_ups.jpg)


**Credits to ARGSociety for the below information**

In the logstash-ups folder, type tail results-2015-09-29.txt to get:
'''
09/25/15: 06:05:10 192.251.68.229: Pinging (via IMCP) device
09/25/15: 06:05:12 192.251.68.229: Device connection passed
09/25/15: 06:05:13 192.251.68.229: Testing FTP Log-in
09/25/15: 06:05:19 192.251.68.229: FTP Log-in passed
09/25/15: 06:05:28 192.251.68.229: Saving data file
09/25/15: 06:05:35 192.251.68.229: OS Prior to firmware transfer: Network Management Card OS v6.4.1
09/25/15: 06:05:41 192.251.68.229: Saving event & configuration files
09/25/15: 06:05:49 192.251.68.229: Validating firmware file (1/1)
09/25/15: 06:06:32 192.251.68.229: Signature check failed, update aborted
09/25/15: 06:07:20 192.251.68.229: Encountered 1 failure during upgrade
'''
