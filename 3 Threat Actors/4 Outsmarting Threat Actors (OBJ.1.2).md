# Setup & Utilize Deception & Disruption Technologies
*Type of Adversary; Threat Actor's TTPs*
- Honeypots 
- Honeynets
- Honeyfiles
- Honeytokens
# Tactics, Techniques, Procedures (TTP)
- specific methods & patterns of activities or behaviors associated with a particular threat actor or group of threat actors 
# Deceptive & Disruption Technologies
- designed to mislead, confuse & divert attackers from critical assets while simultaneously detecting & neutralizing threats 
## Honeypot 
- decoy system or network
- setup to attract potential hackers/attackers
- used against insider threats to detect internal fraud, snooping, malpractice 
- place within a screened subnet or isolated segment that's easily accessible by potential attackers 
## Honeynet
- network of honeypots to create more complex system 
- designed to mimic entire network of systems (incl servers, routers, switches)
- logs all activities to provide wealth of data about both successful & unsuccessful attacks
- both have RISKS that the attacker could use to learn how production systems are configured  
## Honeyfile
- decoy file placed within a system to lure in potential attackers 
- word-processing docs
- spreadsheets 
- presentation files 
- images 
- database files 
- executables 
## Honeytoken
- piece of data or resource that has no legitimate value/use but is monitored for access or use 
- useful for detecting insider threats 

# Disruption Technologies 
## Bogus DNS
- fake DNS entries introduced into a system's DNS server 
## Decoy Dirs
- fake folders & files placed within a system's storage 
## Dynamic Page Generation
- used in websites to present ever-changing content to web crawlers to confuse/slow down the Threat Actor (TA)
## Port Triggering 
- security mechanism where specific services/ports on a network device remain closed until a specific outbound traffic patter is detected 
## Fake Telemetry Data 
- system can respond to an attacker's network scan attempt by sending out fake telemetry/network data 
