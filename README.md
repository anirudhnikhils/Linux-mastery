Linux Mastery – SRE/DevOps Level

This repository contains a complete, end-to-end Linux roadmap designed for
FAANG-level DevOps, SRE, Platform Engineering & Cloud Engineering roles.

It follows a phase-wise, step-by-step structured learning path
that builds knowledge from fundamentals → internals → kernel → production troubleshooting.

📘 Why This Repo?

To master Linux from zero to FAANG level

To understand Linux internals used by Docker & Kubernetes

To learn production debugging like SREs at Google, Uber, Nutanix

To build a strong foundation for Kubernetes, cloud, DevOps, infra

📂 Repository Structure

linux-mastery/

 ├── phase-1-foundations/
 │    ├── step-01/
 │    ├── step-02/
 │    ├── ...
 ├── phase-2-networking-system/
 │    ├── step-11/
 │    ├── step-12/
 │    ├── ...
 ├── phase-3-advanced/
 │    ├── step-21/
 │    ├── step-22/
 │    ├── ...
 ├── projects/
 ├── interview-questions/
 ├── notes/
 ├── cheatsheets/
 └── README.md


Each Step will contain:

Explanation/notes

Commands

Diagrams (if required)

Assignments

Interview questions

🟩 SECTION 1 — LINUX

🟦 PHASE 1 — FOUNDATIONS

Step 1: Linux architecture (Kernel, Shell, User-space)

Step 2: Linux file system layout

Step 3: Basic commands (ls, cat, mv, cp, find)

Step 4: Users & Groups, sudo, passwd

Step 5: Permissions, chmod, chown, umask

Step 6: Processes, ps, top, htop, signals

Step 7: Systemd — services, journalctl

Step 8: Text editors — nano, vim basics

Step 9: Disk basics — df, du, lsblk, mount

Step 10: Bash basics — variables, loops, functions

🟦 PHASE 2 — NETWORKING & SYSTEM

Step 11: IP, ports, net-tools, iproute2

Step 12: DNS, resolv.conf, dig

Step 13: Routing tables, ip route

Step 14: Firewalls — iptables fundamentals

Step 15: IPVS — kube-proxy base

Step 16: Linux logs architecture

Step 17: Performance tools — vmstat, iostat, sar

Step 18: Process internals — fork/zombie/orphan

Step 19: Boot process — BIOS → GRUB → kernel → systemd

Step 20: Package managers — apt, yum, dnf

🟦 PHASE 3 — FAANG-LEVEL ADVANCED

Step 21: Namespaces (PID, NET, MNT, UTS, IPC, USER)

Step 22: Network namespaces deep dive

Step 23: cgroups v1/v2, resource control

Step 24: OOMKill internals, QoS mapping

Step 25: OverlayFS (Docker image layers)

Step 26: SELinux — contexts, domains

Step 27: AppArmor

Step 28: Linux capabilities

Step 29: Seccomp

Step 30: FAANG-level debugging scenarios

🧪 Projects Included

1-Build a “mini container” using namespaces + cgroups

2-Log analysis system

3-Process & resource monitoring tools

4-Write custom Bash utilities

5-Service management automation scripts

6-Disk monitoring + alerting script

7-Production-like performance debugging labs

🎯 Who Should Use This Repo?

Aspiring DevOps, SRE, Platform Engineers, Cloud/Infra engineers

Anyone who wants deep Linux internals mastery
