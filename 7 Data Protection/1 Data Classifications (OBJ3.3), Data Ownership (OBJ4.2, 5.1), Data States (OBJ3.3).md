# Data Classifications OBJ 3.3
- category based on the orgs value & sensitivity of the info if it were to be disclosed 
## Sensitive Data
- info that can result in loss of security or advantage to a company if accessed by an unauth person 
## Public Data
- no impact on company if released and often posted if open-source env 
## Sensitive Data
- minimal impact if released (orgs financial data)
## Private Data
- contains data that should only be used within the org 
## Confidential Data 
- contains items such as trade secrets, intellectual property data, & source code that affect the business if disclosed 
## Critical
- contains valuable information 

---
# Data Ownership OBJ 4.2 & 5.1
- process of identifying the person responsible for the confidentiality, integrity, availability, & privacy of the information assets 
## Data Owner
- senior exec role that has responsibility for maintaining the confidentiality, integrity, & availability of the information asset 
## Data Controller
- entity that holds responsibility for deciding the purposes & methods of data storage, collection, & usage, & for guaranteeing the legality of processes 
## Data Processor 
- group or individual hired by the data controller to help with tasks like collecting, storing, analyzing data 
## Data Steward
- focused on the quality of the data & the associated metadata 
## Data Custodian
- responsible for handling the management of the system on which the data assets are stored 
## Privacy Officer
- role that's responsible for the oversight of any kind of privacy-related data, like PII, SPI, or PHI

---
# Data States OBJ 3.3
## Data at Rest
- data stored in databased, file systems, or other storage systems 
- prime target for TA's
### Full Disk Encryption (FDE)
- encrypts the entire hard drive 
### Partition Encryption
- encrypts specific partitions of a hard drive, leaving other partitions unencrypted 
### File Encryption
- encrypts individual files 
### Volume Encryption
- encrypts a set of selected files or directories 
### Database Encryption
- encrypts data stored in a database 
### Record Encryption
- encrypts specific fields within a database record 
## Data in Transit/Data in Motion
- data actively moving from 1 location to another, like across the internet or through a private network 
### Secure Sockets Layer (SSL) Transport Layer Security (TLS)
- cryptographic protocols designed to provide secure communication over a computer network 
### Virtual Private Network (VPN)
- technology that creates a secure connection over a less secure network (internet)
### Internet Protocol Security (IPSec)
- protocol suite used to secure IP communications by auth & encrypting ea IP packet in a data stream 
## Data in Use
- refers to data in the process of being created, retrieved, updated, or deleted 

