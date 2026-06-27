# Week 2 — OSI Model + Wireshark

**Phase:** 1 — IT Foundations
**Status:** ✅ Complete
**Date completed:** June 2026

---

## 🎯 Goal for the week
Understand the OSI Model and use Wireshark to capture and analyze real 
network traffic for the first time.

## 📚 What I learned

- **The OSI Model** — the 7 layers describing how data travels across a 
  network: Physical, Data Link, Network, Transport, Session, Presentation, 
  Application. Each layer adds a different type of information as data 
  moves from a sender to a receiver.
- **Wireshark** — a tool that captures live network packets passing through 
  a network interface, letting you see exactly what data is being sent and 
  received in real time.
- **DNS record types** — an **A record** returns the IPv4 address for a 
  domain, while an **AAAA record** returns the IPv6 address (a newer, 
  longer address format).
- **DNS transaction IDs** — every DNS query includes a random hex ID 
  (e.g., `0x3e49`). The response includes the exact same ID, which lets 
  the requesting computer match each answer to the correct question, even 
  when several queries are sent within milliseconds of each other.
- **VirtualBox networking** — my Kali VM connects to the internet through 
  VirtualBox's NAT mode, which shares my host laptop's existing connection. 
  This is why Kali shows a private `10.0.2.15` address rather than a 
  WiFi-assigned IP.

## 🛠️ What I did hands-on

- Opened Wireshark on Kali and selected the `eth0` interface
- Captured live traffic while browsing real websites (Google, TryHackMe)
- Applied filters to isolate specific traffic:

```bash
dns
dns.qry.name == "www.google.com"
