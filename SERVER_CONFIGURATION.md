1. Sao Paulo - Brazil (Primary Mainnet) To be implemented for the MianNet
- Type: Cloud AWS x1.16Xlarge
  - CPU: 64 cores
  - RAM: 1T
  - SSD: 20(EBS)
  - Network: 25Gbps

2. Fortaleza - Brazil (Testenet/Backup Node)
- Type: Bare Machine (Up and Running)
  - CPU: 24 cores
  - RAM: 128GB
  - SSD: 500GB RAID 10
  - Network: 1Gbps

3. Virginia (Testenet /Mainnet Redundancy/Backup Node) (Up and Running)   
- Type: Bare Machine (Cluster)
  - CPU: 72 cores
  - RAM: 320GB
  - SSD: 2T GlusterFS
  - Network: 1Gbps

### Hardware capacity upgrade plan 
We plan to monitor the main server load, as well the testnet and backup servers, upgrading processor and memory as required by the network, ensuring that the server does not exceed 70% of the hardware capacity.

In the first two years, we plan to add several redundancy nodes across Brazil.
