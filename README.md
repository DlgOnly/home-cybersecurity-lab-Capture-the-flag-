# Home Cybersecurity Lab

## Objective

Build a home cybersecurity environment to practice:

- Network Enumeration
- Web Server Administration
- Blue Team Defense
- Red Team Reconnaissance
- Remote Administration
- VPN Networking

---

## Hardware

- HP Desktop
- Raspberry Pi 5
- Raspberry Pi Mini Keyboard

---

## Software

- Windows
- VirtualBox
- Ubuntu Server
- Kali Linux
- Apache2
- Tailscale
- GitHub

---
| Week | Attacker Goal                      | Defender Goal                   | Flag                       |
| ---- | ---------------------------------- | ------------------------------- | -------------------------- |
| 1    | Discover the network               | Build and inventory the network | Find a hidden text file    |
| 2    | Enumerate services                 | Secure services                 | Retrieve a banner          |
| 3    | Web application assessment         | Harden the web server           | Find a secret page         |
| 4    | Password auditing on test accounts | Strengthen authentication       | Crack a weak test password |
| 5    | Persistence detection exercise     | Detect unauthorized changes     | Find a planted file        |
| 6    | Log analysis challenge             | Identify attack timeline        | Determine attack time      |
| 7    | Blue vs. Red Team                  | Defend while attacks occur      | Keep services available    |
| 8    | Full CTF                           | Attack and defend               | Capture all flags          |


## Network Diagram

Internet
        |
   Tailscale VPN
        |
------------------------
|                      |
HP Server VM       Raspberry Pi 5
(Ubuntu)           (Kali Linux)

---

# Step 3: Add a folder structure

Create:

---

# Step 4: Upload screenshots

Take screenshots of:

- Ubuntu Server login
- Kali Raspberry Pi
- Apache installed
- Tailscale connected
- VirtualBox running
- Terminal commands

Example:
<img width="1733" height="625" alt="image" src="https://github.com/user-attachments/assets/5143c1f2-1f3b-48d0-af45-7f1027d42653" />
<img width="962" height="728" alt="image" src="https://github.com/user-attachments/assets/1487062b-110d-44f8-9122-e2dfae2be170" />
<img width="1161" height="530" alt="tail devices" src="https://github.com/user-attachments/assets/ff9336cd-bf06-4671-8d4a-1a293b4a6468" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/ffd238b7-4666-46aa-961e-fb0682642f06" />

---

# Step 5: Create a Commands file

commands/linux-commands.md

````markdown
# Useful Commands

## Update

```bash
sudo apt update

---

# Step 6: Document your CTF

Create:

```
ctf/week1.md
```

Example:

````markdown
# Week 1

Objective:

Discover hidden flag.

Flag:

```
FLAG{network_discovery}
```

Attacker:

- Network scan

Defender:

- Log monitoring

Lessons Learned:

- Enumeration
- Apache basics
Internet

     |

Tailscale VPN

     |

-------------------------

|                       |

HP Server VM        Raspberry Pi

(Ubuntu)            (Kali)

     |

Apache

SSH

CTF
git init

git add .

git commit -m "Initial Cybersecurity Lab"

git branch -M main

git remote add origin https://github.com/YOUR_USERNAME/home-cybersecurity-lab.git

git push -u origin main
