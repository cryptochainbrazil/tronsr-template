Our nodes are placed in different continents, we are using cloud service and also bare metal servers. 

### Server Specs
1. São Paulo - Brazil (Primary Mainnet node) 
- Cloud AWS x1.32Xlarge
  - CPU: 128 cores
  - RAM: 1952GB
  - SSD: 2 x1952GB
  - Network: 25Gbps

2. Fortaleza - Brazil (Testenet/Backup Node)
- Bare metal server
  - CPU: 24 cores
  - RAM: 128 GB
  - SSD: 500GB RAID 10
  - Network: 1Gbps 
  
3. Virginia - US (Testenet /Mainnet Redundancy/Backup Node) 
- Bare metal server
  - CPU: 72 cores
  - RAM: 728 GB
  - SSD: 2TB GlusterFS
  - Network: 10Gbps

### Hardware capacity upgrade plan 
We plan to monitor the main server load, as well the testnet and backup servers, upgrading processor and memory as required by the network, ensuring that the server does not exceed 70% of the hardware capacity.

In the first two years, we plan to add several redundancy nodes across Brazil.
