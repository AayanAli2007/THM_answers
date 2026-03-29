# THM_answers

-- EXTRAS
const links = document.querySelectorAll('a[href^="/room/"]');

links.forEach(link => {
    console.log("https://tryhackme.com" + link.getAttribute("href"));
});
-- EXTRAS


https://tryhackme.com/room/beginnerpathintro
Ben.Spring
THM{BRUTEFORCING}
$300 million

https://tryhackme.com/room/startingoutincybersec
penetration tester
Security Analyst

https://tryhackme.com/room/introtoresearch
Repeater
NTLM
Cron jobs
Base 16
sha512crypt

CVE-2020-10385
CVE-2016-1240
CVE-2007-0017
CVE-2019-18634

-r
-l
-B
nc -l -p 12345
  -l listen mode
  -p specify port

https://tryhackme.com/room/catregex
  https://regexr.com/
[cog]
[cfh]at
[CcHh]at
[Ff]ile[1-9]
[Ff]ile[^7]

.at
[Cc]ats?
cat\.xyz
[ch]ats?\.xyz
...[^n-z]
[^r]ats?

cats{4}
[Cc]ats*
regex go br+
[abc]{1,3}[01]{4}
[Ff]ile\d{1,2}
kali\s+tools
\w{5}\W
\S*\s*\S*
\S{8}[^!]
\.?\w+

Password:[^0]{10}
^username:\s
^\D
EOF\$$
I use (nano|vim)
\$\d\$\S+
(\d{1,3}\.){3}\d{1,3}
(\w+)@(\w+)\.com


https://tryhackme.com/room/linuxmodules -- THIS IS REALY NICE
  grep -iE "password|user|comment" filename
Yea
-v
bobthebuilder
LinuxIsGawd
fs0ciety

  https://man7.org/linux/man-pages/man1/tr.1.html
:digit:
:alpha:

awk 'BEGIN{OFS=":"} {print $1, $4}' awk.txt
awk 'BEGIN{ORS=", "} {print $1}' awk.txt

sed 's/hack/back/3g' file.txt
sed '3,4 s/hack/back/3g' file.txt
sed 's/  */:/g' sed1.txt
CONGRATULATIONS YOU MADE IT THROUGH THIS SMALL LITTLE CHALLENGE
   sed 's/[^a-zA-Z]//g' sed2.txt
's/[[:digit:]]//g'
"That's What"
  "That's What" she sed





