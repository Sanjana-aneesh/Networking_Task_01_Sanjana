# Part B — Basic Networking Concepts

**Submitted by:** Sanjana
**Date:** 04 June 2026

---

### 1. What is an IP Address?
An IP address is basically a unique number given to every device on a network. Just like every house has its own address so the postman knows where to deliver letters, every device has an IP address so data knows where to go. My device's IP address is `192.168.1.106`.

### 2. What is a MAC Address?
A MAC address is a permanent ID that is physically built into your network card. It never changes no matter what — even if you reinstall Windows or change your network. Think of it like a serial number on your device. My device's MAC address is `94-BB-43-48-20-77`.

### 3. What is a Default Gateway?
The default gateway is your router's address. Whenever your device wants to talk to something outside your home network — like a website — it first sends the data to the gateway and the router takes it from there. Without it your device would have no way out to the internet. My default gateway is `192.168.1.1`.

### 4. What is DNS?
DNS is like a contacts app for the internet. When you type `google.com` your device has no idea what that means — it only understands numbers. So DNS converts that name into an actual IP address like `142.250.146.139` so your device knows where to go. Without DNS you would have to type a bunch of numbers every time you want to visit a website. My DNS server is `192.168.1.1`.

### 5. Difference Between Public IP and Private IP

| Feature        | Private IP                        | Public IP                        |
|----------------|-----------------------------------|----------------------------------|
| Where used     | Inside your home network          | On the internet                  |
| Assigned by    | Your router                       | Your internet provider (ISP)     |
| Example        | 192.168.1.106                     | Assigned by ISP, visible online  |
| Unique?        | Only inside your network          | Unique across the whole internet |
| Visible online | No                                | Yes                              |

Simply put — your private IP is your address inside your home network and your public IP is what the rest of the internet sees. My device has a private IP of `192.168.1.106` and the outside world only sees my router's public IP.
