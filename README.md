# funkySwarm
NSM - Swarm
Goals
- Provide a entirely dockerized NSM (inspired by work/SO)
- Create a means to provide training (live network sim)
- Make this work hardware agnostic as possible
- Push as much as possible through gitlab 

# Multiple compose-docker.<tool>.yml files
Why - Each compose file allows to individually test each (docker-compose -f)
### Current Tool List
- Swarmpit
- Splunk
- TheHive
- rocket.chat 
- ELK
- Nessus

### Planned 
- CyberChef
- PCAP Viewer (TBD)
- Open Source Vuln Scanning (To replace/in addition to Nessus)
- Logical accountability of interactive components
- Filebeat
- Full Packet Capture (TBD)
- Zeek 
- Ansible / AWX