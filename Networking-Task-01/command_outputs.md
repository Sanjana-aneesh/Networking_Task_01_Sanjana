# Part D — Command Outputs

**Submitted by:** Sanjana
**Date:** 04 June 2026

---

## 1. ipconfig /all

![ipconfig output](screenshots.png)

---

## 2. ping google.com

![ping output](ping_google.png)

---

## 3. tracert google.com

![tracert output](tracert_google.png)

---

## Answers

**1. Was the ping successful?**

Yes, the ping was completely successful. All 4 packets were sent and all 4 were received with 0% packet loss. The average response time was 9ms, which indicates a fast and stable internet connection.

**2. How many hops were shown?**

15 hops were shown in total. Hops 9 through 14 showed "Request timed out" — this is normal behaviour because those routers are configured to block traceroute probes for security reasons. Hop 15 successfully reached Google's server at `pu-in-f139.1e100.net [142.250.146.139]`, confirming the route completed successfully.

**3. What is the purpose of traceroute?**

Traceroute (`tracert` on Windows) maps the exact path that data packets travel from your device to a destination. It shows every router (hop) along the way and how long it takes to reach each one. This is useful for diagnosing network issues — if one hop has very high latency or times out unexpectedly, you can pinpoint exactly where the problem is occurring in the network.
