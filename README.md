# Resources

This repository is meant to track a lot of tools I'm told about, where do I get them, how to install, and some basic usage examples if I even get that far <br/><br/>

########### Terminals & Articles about Them ########### <br/>
iTerm2 for OSX <br/>
https://iterm2.com/ <br/>
<br/>
The new Windows Terminal <br/>
https://www.howtogeek.com/673729/heres-why-the-new-windows-10-terminal-is-amazing/ <br/>
<br/>
Terminator for Linux <br/>
https://www.2daygeek.com/terminator-linux-terminal-emulator-supports-multiple-terminals-in-one-window/ <br/>
<br/>
Add functionality to your shell: <br/>
https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/ <br/>
<br/><br/>

########### Fun Reads ########### <br/>
A great read about pivoting <br/>
https://artkond.com/2017/03/23/pivoting-guide/ <br/><br/>

Pentesting on Memcached Servers <br/>
https://www.hackingarticles.in/penetration-testing-on-memcached-server/ <br/><br/>

Windows Memory Analysis <br/>
http://scitechconnect.elsevier.com/wp-content/uploads/2013/09/Windows-Memory-Analysis.pdf <br/><br/> 

<br/>
########### Command Line Tricks ########### <br/>
Get the local domain from your resolv.conf file <br/>
cat /etc/resolv.conf <br/><br/>

Use 'dig' to enumerate all of the DCs for that domain: <br/>
dig +short any _kerberos._tcp.{PUT THE DOMAIN FROM THE RESOLV.CONF HERE} <br/><br/>

Quick way to find you IP address using ip tools instead of ifconfig: <br/>
ip -f addr show {device} (Example for HTB: ip -f addr show tun0) <br/><br/>

<br/>
########### Tools ########### <br/>
Impacket: Collection of Python classes for working with network protocols <br/>
https://github.com/SecureAuthCorp/impacket <br/><br/>

Windows privilege escalation (enumeration) script designed with OSCP labs in mind <br/>
https://github.com/M4ximuss/Powerless <br/><br/>

Record and Replay Linux Terminal Session Commands <br/>
https://www.tecmint.com/record-and-replay-linux-terminal-session-commands-using-script/ <br/><br/>

Memory Ananlysis Tool: DumpIt <br/>
https://blog.comae.io/your-favorite-memory-toolkit-is-back-f97072d33d5c <br/><br/>

Memory Analysis Tool: Volatility Framework <br/>
https://github.com/volatilityfoundation/volatility <br/><br/>

Memory Analysis Tool (Paid but great!): Arsenal Recon <br/>
https://arsenalrecon.com <br/><br/>

Walrus App (Badge cloning for Red Teaming) <br/>
https://walrus.app <br/><br/>

Keychain Dumper for OSX <br/>
https://github.com/ptoomey3/Keychain-Dumper <br/><br/>


########### Exploit Databases ########### <br/>
Exploit DB by Offensive Security <br/>
https://github.com/offensive-security/exploitdb <br/>
https://www.exploit-db.com <br/><br/>

Searchsploit (Does not include the Google Hacking Database) <br/>
https://github.com/offensive-security/exploitdb <br/>
https://www.exploit-db.com/searchsploit <br/><br/>

Google Hacking Database <br/>
https://www.exploit-db.com/google-hacking-database <br/><br/>

<br/>
########### Wordlists ########### <br/>
SecLists <br/>
https://github.com/danielmiessler/SecLists <br/>
https://owasp.org/www-project-seclists/migrated_content <br/><br/>

<br/>
########### Virtual Machines and Legal Hacking Sites  ########### <br/>
Commando VM (Windows version of Kali) <br/>
https://github.com/fireeye/commando-vm <br/><br/>

Hack the Box (HTB) <br/>
Alpha: https://www.hackthebox.eu <br/>
Beta: https://app.hackthebox.eu/login <br/><br/>
