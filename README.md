Project Overview
This repository documents the practical implementation of a dual-VM Linux architecture for the Operating Systems coursework. Over 7 weeks, I designed, deployed, secured, and analyzed a headless Ubuntu Server managed entirely via SSH from a separate Workstation VM.

The project demonstrates proficiency in:

System Architecture: Designing isolated networks (Host-Only) for secure testing.
Server Hardening: Implementing SSH keys, UFW firewalls, AppArmor, and Fail2Ban.
Performance Analysis: Benchmarking CPU, RAM, and Disk I/O using CLI tools.
Automation: Writing Bash scripts for security baselining and remote monitoring.
System Architecture
The setup consists of two Virtual Machines running on VirtualBox:

Role	OS Distribution	IP Address	Configuration
Server	Ubuntu Server 24.04 LTS	192.168.56.10	Headless, SSH only, Hardened
Workstation	Ubuntu Desktop 24.04 LTS	192.168.56.11	GUI Admin Console, Monitoring Station
Network: VirtualBox Host-Only Adapter (vboxnet0) for complete isolation.
Weekly Journal
Click the links below to view the detailed documentation for each phase.

Week	Phase	Key Activities
Week 1	System Planning	Architecture design, distro selection, and network setup.
Week 2	Security Planning	Threat modeling, security checklist, and testing plan.
Week 3	App Selection	Choosing and installing workloads (stress, fio, Minecraft).
Week 4	Initial Config	SSH hardening (Keys), Firewall (UFW) setup, and User management.
Week 5	Advanced Security	AppArmor, Fail2Ban, Auto-updates, and Bash scripting.
Week 6	Performance	Load testing, bottleneck analysis, and system optimization.
Week 7	Security Audit	Lynis auditing, Nmap scanning, and final evaluation.
Tools & Technologies Used
Virtualization: Oracle VirtualBox
Operating Systems: Ubuntu Linux 24.04 LTS
Security: OpenSSH, UFW, AppArmor, Fail2Ban, Lynis, Nmap
Performance: Htop, Iostat, Iperf3, Stress, Memtester, Fio
Scripting: Bash (Shell Scripting), Python (Data Visualization)
