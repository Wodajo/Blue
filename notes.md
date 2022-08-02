SOC - security operation center - security monitoring people  
SIM - Security Information Management (software for data collecting)
SEM - Security Event Management (soft that correlates data -> alerts)
SIEM - tool for data collection (many nodes) & correlation  
CISO - chief information security officer  
Playbook - form of standarisation, categorisation and guidebook for cases  
e.g. SOC 1 - malware! -> ticket -> hash check -> priority P3 -> comment -> SOC Tier 2  
kinda like medical algorithms  
CSIRT - Computer Security Incident Response Team (as SOC 2 or parallel)  
also takes part in further investigations (criminology)  
MSSP - Managed Security Service Provider - outside SOC  
TMS - task management system (e.g. jira, trello)  
SOAR - security orchestration, automation and response - stack of compatible software programs for collecting data about security threats and responce to security events without human assistance.  
EDR - end-point detection and response. You can connect into host remotely if sth happens. Used i.a. in crime related stuff  
IOC - indicator of compromise  
BYOD - bring your own device  
Crowdstrike - EDR based on machine learning  
HIPS - host-based intrusion prevention system  
DLP - data leak prevention
NAC - network access control - big entinty, may combine authentication, device management, fw, IDS, profiling and fingerprinting etc. Mainly used inside infrastructures  
E.g. connecting unknown device by eth -> NAC might alert and restrict access to resources based on e.g. MAC
IDS - intrusion detection system - parallely
IPS - intrusion prevention system - in line
kredki=credentiale:D
NIPS - network intrusion prevention system - collective name for IDS, IPS, fw and such in current set of tools

Snort - IPS&IDS software
[PacketFence](https://www.packetfence.org/about.html) - NAC, can be configurated as gateway or dedicated server managing VLANs
pfSense - fw
[VirusTotal](https://www.virustotal.com/gui/home/upload) - data base with viruses hashes -> many ifno about what to search for in maybe-infected OSs (new files, registry actions, processes, IP addresses to check)  
[Maleware bazaar](https://bazaar.abuse.ch/browse/) - malware samples (in passwd-secured .zip)  
[any.run](https://any.run/) - mainly for links  


Active Directory - windows server i.a. assigning FQDN
(Having admin AD you can get into any connected host)

Even Viewer (Windows) is weak

