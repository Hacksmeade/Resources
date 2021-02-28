# Resources

This repository is meant to track a lot of tools I'm told about, where do I get them, how to install, and some basic usage examples if I even get that far

########### Terminals & Articles about Them ###########
iTerm2 for OSX
https://iterm2.com/

The new Windows Terminal 
https://www.howtogeek.com/673729/heres-why-the-new-windows-10-terminal-is-amazing/

Terminator for Linux
https://www.2daygeek.com/terminator-linux-terminal-emulator-supports-multiple-terminals-in-one-window/

Add functionality to your shell:
https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/


########### Fun Reads ###########
A great read about pivoting
https://artkond.com/2017/03/23/pivoting-guide/

Pentesting on Memcached Servers
https://www.hackingarticles.in/penetration-testing-on-memcached-server/

Windows Memory Analysis
http://scitechconnect.elsevier.com/wp-content/uploads/2013/09/Windows-Memory-Analysis.pdf


########### Command Line Tricks ###########
Get the local domain from your resolv.conf file
cat /etc/resolv.conf

Use 'dig' to enumerate all of the DCs for that domain:
dig +short any _kerberos._tcp.{PUT THE DOMAIN FROM THE RESOLV.CONF HERE}

Quick way to find you IP address using ip tools instead of ifconfig: 
ip -f addr show {device} (Example for HTB: ip -f addr show tun0)


########### Tools ###########
Impacket: Collection of Python classes for working with network protocols
https://github.com/SecureAuthCorp/impacket

Windows privilege escalation (enumeration) script designed with OSCP labs in mind
https://github.com/M4ximuss/Powerless

Record and Replay Linux Terminal Session Commands
https://www.tecmint.com/record-and-replay-linux-terminal-session-commands-using-script/

Memory Ananlysis Tool: DumpIt 
https://blog.comae.io/your-favorite-memory-toolkit-is-back-f97072d33d5c

Memory Analysis Tool: Volatility Framework 
https://github.com/volatilityfoundation/volatility

Memory Analysis Tool (Paid but great!): Arsenal Recon
https://arsenalrecon.com

Walrus App (Badge cloning for Red Teaming)
https://walrus.app

Keychain Dumper for OSX
https://github.com/ptoomey3/Keychain-Dumper


########### Exploit Databases ###########
Exploit DB by Offensive Security
https://github.com/offensive-security/exploitdb
https://www.exploit-db.com

Searchsploit (Does not include the Google Hacking Database)
https://github.com/offensive-security/exploitdb
https://www.exploit-db.com/searchsploit

Google Hacking Database
https://www.exploit-db.com/google-hacking-database


########### Wordlists ###########
SecLists
https://github.com/danielmiessler/SecLists
https://owasp.org/www-project-seclists/migrated_content


########### Virtual Machines and Legal Hacking Sites  ###########
Commando VM (Windows version of Kali)
https://github.com/fireeye/commando-vm

Hack the Box (HTB)
Alpha: https://www.hackthebox.eu
Beta: https://app.hackthebox.eu/login 
