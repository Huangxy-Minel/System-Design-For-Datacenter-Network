# System-Design-For-Datacenter-Network
A paper list of high-performance technologies in data center network, system-oriented.

## Catalog
**For some selected papers, we have provided reading blogs in Chinese.**

#### 1 [Federated Learning Foundation](#survey)
#### 2 [Research Areas](#areas)

- 2.1 [RDMA-based Optimization](#RDMA)
- 2.2 [SmartNic](#smartnic)


---------------------------------------------------

<h2 id="survey">Datacenter Network Survey & Foundation</h2>

---------------------------------------------------

<h2 id="areas">Reasearch Areas</h2>
<h3 id="RDMA">2.1 RDMA-based Optimization</h3>

- [(DCQCN) Congestion Control for Large-Scale RDMA Deployments](https://dl.acm.org/doi/pdf/10.1145/2829988.2787484).2015.SIGCOMM
- [TIMELY: RTT-based Congestion Control for the Datacenter](https://dl.acm.org/doi/pdf/10.1145/2829988.2787510).2015.SIGCOMM
- [RDMA over Commodity Ethernet at Scale](https://dl.acm.org/doi/pdf/10.1145/2934872.2934908).2016.SIGCOMM
- [Multi-Path Transport for RDMA in Datacenters](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-lu.pdf).2018.NSDI
- [(IRN) Revisiting Network Support for RDMA](https://dl.acm.org/doi/pdf/10.1145/3230543.3230557).2018.SIGCOMM
- [HPCC: High Precision Congestion Control](https://dl.acm.org/doi/pdf/10.1145/3341302.3342085).2019.SIGCOMM
- [Gentle Flow Control: Avoiding Deadlock in Lossless Networks](https://dl.acm.org/doi/pdf/10.1145/3341302.3342065).2019.SIGCOMM
- [FreeFlow: Software-based Virtual RDMA Networking for Containerized Clouds](https://www.usenix.org/system/files/nsdi19-kim.pdf).2019.NSDI
- [Swift: Delay is Simple and Effective for Congestion Control in the Datacenter](https://dl.acm.org/doi/pdf/10.1145/3387514.3406591).2020.SIGCOMM
- [Re-architecting Congestion Management in Lossless Ethernet](https://www.usenix.org/system/files/nsdi20spring_cheng_prepub_0.pdf).2020.NSDI
- [FileMR: Rethinking RDMA Networking for Scalable Persistent Memory](https://www.usenix.org/system/files/nsdi20-paper-yang.pdf).2020.NSDI
- [1RMA: Re-envisioning Remote Memory Access for Multi-tenant Datacenters](https://dl.acm.org/doi/pdf/10.1145/3387514.3405897).2020.SIGCOMM
- [Breaking the Transience-Equilibrium Nexus- A New Approach to Datacenter Packet Transport](https://www.usenix.org/system/files/nsdi21-liu.pdf).2021.NSDI
- [Congestion Detection in Lossless Networks](https://dl.acm.org/doi/pdf/10.1145/3452296.3472899).2021.SIGCOMM
- [Gimbal: Enabling Multi-tenant Storage Disaggregation on SmartNIC JBOFs](https://dl.acm.org/doi/pdf/10.1145/3452296.3472940).2021.SIGCOMM

---------------------------------------------------

<h3 id="smartnic">2.2 SmartNIC-based Optimization</h3>

- [Enabling Programmable Transport Protocols in High-Speed NICs](https://www.usenix.org/system/files/nsdi20-paper-arashloo.pdf).2020.NSDI
- [Corundum: An Open-Source 100-Gbps NIC](https://ieeexplore.ieee.org/iel7/9108348/9114534/09114811.pdf).2020.FCCM
- [PANIC: A High-Performance Programmable NIC for Multi-tenant Networks](https://www.usenix.org/system/files/osdi20-lin.pdf).2020.OSDI
- [StRoM: Smart Remote Memory](https://dl.acm.org/doi/pdf/10.1145/3342195.3387519).2020.EuroSys
- [FpgaNIC: An FPGA-based Versatile 100Gb SmartNIC for GPUs](https://www.usenix.org/system/files/atc22-wang-zeke.pdf).2022.ATC
- [SRNIC: A Scalable Architecture for RDMA NICs](https://cse.hkust.edu.hk/~kaichen/papers/srnic-nsdi23.pdf).2022.NSDI