# RHCSA-study-labs
Follow my journey as I study to earn my RHCSA Certificate in 2026!

# RHCSA Study Journey & Labs (RHEL 10)

This repository documents my hands-on preparation for the **Red Hat Certified System Administrator (RHCSA)** exam (EX200) on Red Hat Enterprise Linux 10.

**Goal**: Pass the RHCSA performance-based exam and build practical Linux system administration skills to pursue junior/mid-level roles such as Linux Administrator, Systems Engineer, or IT Support with Linux focus.

### Current Learning Resources
I'm following these two main resources in parallel:

1. **Udemy Course**  
   - Title: Unofficial Linux Red Hat Certified System Administrator (RHCSA)  
   - Link: https://www.udemy.com/course/unofficial-linux-redhat-certified-system-administrator-rhcsa/  
   - Style: Video lessons + guided labs → used for explanations, walkthroughs, and initial practice.

2. **Book**  
   - Title: RHCSA Red Hat Enterprise Linux 10: Training and Exam Preparation Guide  
   - Author: Asghar Ghori  
   - Amazon link: https://www.amazon.com/dp/177506218X  
   - Style: Detailed written explanations, step-by-step labs, exercises, and exam-style questions → used as primary reference and for deep understanding.

Both resources are aligned with the official RHCSA exam objectives (EX200) on Red Hat Enterprise Linux 10.

### My Study Plan & Progress
I'm combining video + book for maximum understanding and retention.

**Planned Timeline**: 3–6 months (depending on daily study time)

**Study Phases**:

1. **Lab Environment Setup & Basics** (Week 1–2)  
   - Build VMware Workstation Pro lab (Windows 11 host)  
   - 2–3 RHEL 10 VMs on host-only network (192.168.100.0/24 subnet)  
   - Install RHEL 10 Minimal Install  
   - Register with Red Hat Developer subscription  
   - Basic CLI, package management (dnf), users/groups, file permissions  
   → Udemy intro videos + Book Chapter 1–2

2. **Core RHCSA Objectives** (Weeks 3–10)  
   - File systems & storage (LVM, Stratis, VDO, NFS, iSCSI)  
   - Networking (static IP, firewalld rich rules, bonding, routes)  
   - Security (SELinux contexts, booleans, policies, ACLs, LUKS)  
   - Services & processes (systemd, scheduling, boot management)  
   - Containers (Podman rootless, quadlets)  
   → Follow Udemy section-by-section + Book chapters + hands-on labs in this repo

3. **Troubleshooting & Exam Practice** (Weeks 11–14)  
   - Break/fix scenarios (SELinux denials, storage failures, network issues)  
   - Full timed mock exams (performance-based)  
   - Review weak areas from Udemy quizzes + Book practice questions  
   → Use Book's mock exams + Udemy practice tests

4. **Final Review & Exam Readiness** (Last 2–4 weeks)  
   - Re-do all labs without looking at notes  
   - Review official RHCSA objectives line-by-line  
   - Practice under exam conditions (no external help, 2.5–3 hours)

### Lab Structure in This Repo
Each major topic has its own folder:

- `01-setup-and-install/`  
  → VMware config, RHEL 10 install steps, registration, snapshots

- `02-users-groups-permissions/`  
  → useradd, sudoers, ACLs, password policies

- `03-filesystems-storage/`  
  → LVM creation/resizing, Stratis, VDO, NFS exports, iSCSI targets

- `04-networking/`  
  → Static IP config, firewalld rich rules, bonding, static routes

- `05-selinux/`  
  → Contexts, booleans, policy troubleshooting

- `06-containers/`  
  → Podman rootless containers, quadlets

- `07-services-boot/`  
  → systemd units, scheduling (cron/at), boot process

- `practice-exams/`  
  → Mock exam notes, scripts, results, weak area reviews

- `screenshots/`  
  → Visual proof of successful configurations and tests

Each folder contains:
- Step-by-step markdown notes (.md)
- Custom scripts (.sh)
- Configuration snippets (firewalld, fstab, etc.)
- Screenshots of working setups

### How to Follow or Use This Repo
1. Clone:  
   `git clone https://github.com/cloudliness/RHCSA-Study-Labs.git`
2. Browse folders for each topic.
3. Reproduce labs in your own RHEL 10 VM environment.
4. Use my notes/scripts as a reference **after** attempting tasks yourself.

### Current Status
- [x] Built VMware lab environment (host-only network)  
- [x] Installed RHEL 10 Minimal (registered with Developer sub)  
- [ ] Completed Udemy intro + Book basics  
- [ ] In progress: Users, groups, file systems  
- [ ] Next: Networking & firewalld

**Last updated**: February 2026

This repo shows my real progress and hands-on work.  
Feel free to open issues or fork if helpful.  
#RHCSA #RHEL10 #Linux #RedHat #SystemAdministration
