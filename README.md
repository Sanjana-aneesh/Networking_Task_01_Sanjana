# Networking Task 01 — Understanding Your Network Environment

**Intern:** Sanjana
**Date:** 04 June 2026
**Organization:** White Band Associates

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `screenshots/ipconfig_all.png` | Part A — ipconfig /all output showing all network details |
| `screenshots/ping_google.png` | Part D — ping google.com output |
| `screenshots/tracert_google.png` | Part D — tracert google.com output |
| `network_diagram.jpeg` | Part C — hand-drawn network diagram |
| `answers.md` | Part B — Basic networking concepts explained |
| `command_outputs.md` | Part D — Command outputs with screenshots and answers |

---

## 📋 Summary of Findings

- My device hostname is **Pookie**, connected via Wi-Fi using a Realtek RTL8822CE 802.11ac adapter.
- It was assigned a private IPv4 address of **192.168.1.106** by the router through DHCP.
- The MAC address of my Wi-Fi adapter is **94-BB-43-48-20-77**.
- Both the Default Gateway and DNS Server are **192.168.1.1** — my router handles both roles.
- Ping test to google.com was successful — 4/4 packets received, 0% packet loss, average response time of **9ms**.
- Traceroute showed **15 hops** to reach Google's server at `142.250.146.139`. Hops 9–14 timed out which is normal behaviour, and hop 15 confirmed the route completed successfully.
