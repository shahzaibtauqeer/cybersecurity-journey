# Week 1 — Networking Basics + Kali Linux Setup

**Phase:** 1 — IT Foundations
**Status:** ✅ Complete
**Date completed:** June 2026

---

## 🎯 Goal for the week
Understand how the internet works at a basic level and get my first hacking 
lab running.

## 📚 What I learned

- **IP addresses** — every device needs one to be identified on a network, 
  similar to a home address used to deliver mail to a specific location.
- **DNS (Domain Name System)** — works like a phone book. When I type a 
  website name, my browser doesn't understand it directly, so DNS looks up 
  the matching IP address and returns it so the browser can connect.
- **TCP vs UDP** — TCP is reliable and checks that all data arrives (used in 
  apps like WhatsApp and Discord). UDP is faster but doesn't confirm delivery 
  (used in live streaming and gaming).
- **Ports** — a port is a logical number (not a physical thing) that tells a 
  device which specific program incoming data is meant for. For example, 
  port 80 is for HTTP websites, port 443 is for HTTPS (secure) websites, 
  and port 22 is for SSH remote access.

## 🛠️ What I did hands-on

- Installed **VirtualBox** on my computer
- Downloaded and installed **Kali Linux** as a virtual machine
- Opened the Kali terminal and ran my first command:

```bash
whoami
```

Output confirmed: `kali`

## ✅ Milestone achieved

- [x] Can explain what an IP address is and why it's needed
- [x] Can explain what DNS does and how it works
- [x] Kali Linux is successfully running inside VirtualBox
- [x] Successfully ran my first terminal command

## 💭 Notes to myself

Ports were the trickiest concept this week — I initially thought a port was 
a physical part of the computer, but it's actually a logical number used by 
the operating system to route data to the correct application.

---

*Next week: OSI Model + Wireshark — learning to see real network traffic.*
