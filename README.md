# NetAutSol
## Brief
Network in configured using *Ansible using GitLab, CI/CD and Ansible AWX API.*
MPLS network consisting of;
* 8 x Junos Olives in EVE-NG.
Note: *IOS devices shown for reference only*

## Dependencies
* Ansible AWX
* junos-eznc
* GitHub/GitLAB
* CI/CD

## Playbook Details
[Playbook Information](https://github.com/johnsondnz/NetAutSol/blob/master/DETAILS.md)

## Homework submissions
- [CHANGELOG](https://github.com/johnsondnz/NetAutSol/blob/master/CHANGELOG.md)

## Todo
- [TODO](https://github.com/johnsondnz/NetAutSol/blob/master/TODO.md)

## Current Objectives
* Provision provider fabric and services via automated solution.
* Scalability is key, addition of new devices, links, VPNs etc must be easy.
* Verification of models pre-execution and network state post-execution.

## Implimented
- [x] MPLS Fabric and associated core routing protocols.
- [x] mBGP.
- [ ] Layer-2 and Layer-3 VPNs for customer access.
- [ ] Network state verification.
  - [x] IS-IS Adjacencies
  - [x] Ping Tests

# LAB Information
## Network Setup
### P Nodes
* LAB-COR1
* LAB-COR2
* LAB-COR3
* LAB-COR4

### PEs
* LAB-PE1
* LAB-PE2
* LAB-PE3
* LAB-PE4

### Route Reflector Cluster
* LAB-COR1
* LAB-COR2

### Management
em0 on all nodes connected to physical VLAN 22

### Topology
![Topology](https://i.imgur.com/T3AaoIQ.png)
