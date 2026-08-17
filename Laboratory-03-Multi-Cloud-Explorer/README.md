# Laboratory 03 - Multi-Cloud Explorer
## Checkpoint 7 – Linux Investigation

### Linux Server Information

#### Operating System
- OS: Ubuntu 24.04.4 LTS
- Codename: Noble Numbat
- Command used: `cat /etc/os-release`

#### CPU Information
- CPU Sockets: 1
- Hypervisor: KVM
- Virtualization Type: Full
- Command used: `lscpu`

#### Memory
- Total Memory: 1.9 GiB
- Used Memory: 416 MiB
- Available Memory: 1.5 GiB
- Swap: 1.0 GiB
- Command used: `free -h`

#### Disk Space
- Main Disk: `/dev/vda1`
- Total Size: 19 GB
- Used: 5.4 GB
- Available: 13 GB
- Usage: 30%
- Command used: `df -h`

### Cloud Hosting Options

| Cloud Provider | Service | Purpose |
|---|---|---|
| AWS | Amazon EC2 | Hosts the Linux virtual machine |
| Microsoft Azure | Azure Virtual Machines | Hosts the Linux virtual machine |
| Google Cloud | Compute Engine | Hosts the Linux virtual machine |

The Linux server could be migrated to a virtual machine service from any of the three major cloud providers. AWS EC2, Azure Virtual Machines, and Google Compute Engine all support Linux operating systems and can provide scalable computing resources.
