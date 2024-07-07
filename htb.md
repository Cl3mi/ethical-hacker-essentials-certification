# Hack the Box notes
# Box Lame
## check smb (server message block) version
nmap -Pn -p 139, 445 --script=smb-os-discovery [IPADRESS]

nmap -Pn -T4 -A -v [IPADRESS]


