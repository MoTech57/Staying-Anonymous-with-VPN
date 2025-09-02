<h1>👻 Staying Anonymous with VPN👻</h1>

<h2>Description</h2>
This lab demonstrates how to enhance anonymity and security while performing network reconnaissance by leveraging ProxyChains with a SOCKS5 Tor proxy. The setup routes all traffic through the Tor network, ensuring that scans and connections are obfuscated from the target system. Using tools like Nmap in combination with ProxyChains highlights how penetration testers and ethical hackers can conduct stealthier assessments while maintaining privacy. The project covers configuration of ProxyChains, integration with Tor, and practical use cases such as anonymized port scanning and service enumeration.
 
<br />

<h2>Languages and Utilities Used</h2>

- <b>ProxyChains</b>  
- <b>Tor (SOCKS5 proxy)</b>  
- <b>Nmap</b>  
- <b>SSH (remote access)</b>
- <b>Remote Desktop Client</b>  
- <b>Netcat</b>  
- <b>Linux networking utilities (ping, curl, etc.)</b>  

<h2>Environments Used</h2>

- <b>Fedora Linux</b>  
- <b>Tor Network</b>  
- <b>Virtualized Lab Environment (VMware/VirtualBox)</b>  

<h2>Workflow</h2>

<p align="center">

<b>Download from server closest to location:</b><br/>  
<img src="https://i.imgur.com/mpcV6d4.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>cd to downloaded folder and ls content:</b><br/>  
<img src="https://i.imgur.com/SWslN3s.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Start Tor:</b><br/>  
<img src="https://i.imgur.com/G81obtB.png" height="100%" width="100%" alt="Active Directory Setup"/> 
<img src="https://i.imgur.com/ODdzJel.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Use both DNS addressess from OpenDns:</b><br/>  
<img src="https://i.imgur.com/nRTMmES.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Change orginal dns to DNS from OpenDns</b><br/>  
<img src="https://i.imgur.com/xTZj2uG.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Run comanad openvpn --config on VPN of choosing:</b><br/>  
<img src="https://i.imgur.com/CE4uksv.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

</p>
