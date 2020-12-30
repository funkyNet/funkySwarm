# funkySwarm
NSM - Swarm
Goals
- Provide a entirely dockerized NSM (inspired by work/SO)
- Create a means to provide training (live network sim)
- Make this work hardware agnostic as possible
- Push as much as possible through gitlab 

#Layout
$ tree
.
├── p1
│   ├── Dockerfile
│   └── docker-compose.yml
└── p2
    ├── Dockerfile
    └── docker-compose.yml

# Multiple folders
Why - each secion is able to be tested individually, then called together (eg: docker-compose -f ~/funkySwarm/rocketChat/docker-compose.yml up -d)
### Current Tool List
- Portainer
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
- traefik