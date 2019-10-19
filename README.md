# docker-explorer-mainnet
Mincoin Block Explorer - helper files for mainnet image

These instructions are written for a linux environment based upon Ubuntu 16.04 (Xenial). Docker and Docker-compose are needed.

Create a Mincoin Block Explorer instance
NOTE: Tests have shown hardware requirements to be a minimum of 2 CPU / 4GB RAM / 30GB SSD

Docker image:
    docker pull mincoin/explorer-mainnet
    
Helper files:
    wget https://github.com/gotaproblem/docker-explorer-mainnet.git
    
Run:
    docker-compose -f docker-compose.yml -f docker-compose.override.prod.yml up
