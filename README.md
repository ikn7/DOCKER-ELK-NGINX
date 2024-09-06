## TP on Docker and ELK
### Description
This repository is the result of a M2 TP whose goal was to:
- Make a PoC of ELK
- Use only Docker
- Discover in particular Docker Compose
- Have an Nginx server that forwards its logs to ELK

### How does it work?
There are two folders, in each one you just have to type `sudo docker compose up`.
- CLIENTS: Contains a simple Nginx server that forwards its logs to the ELK
- ELK: Contains the ELK stack (Elsatic - Logstash - Kibana)