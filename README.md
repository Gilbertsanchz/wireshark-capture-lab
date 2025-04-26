# 📡 Wireshark Capture & Protocol Analysis Lab

## 📝 Overview
This project captures and analyzes live network traffic using Wireshark on macOS.  
The goal was to capture key network protocols and demonstrate packet analysis using Wireshark display filters.

---

## 📦 Traffic Types Captured

- **ICMP** — Captured via `ping google.com`
- **DNS** — Captured via `nslookup openai.com`
- **TCP 3-Way Handshake** — Captured via a fresh web connection
- **TCP Port 80 Traffic (HTTP-related)** — Captured despite modern HTTPS enforcement

---

## 📸 Screenshots

### 1. ICMP (Ping Traffic)
> Captured Echo Request and Echo Reply packets.

![ICMP Traffic](screenshots/icmp.png)

---

### 2. DNS (Domain Name System Lookup)
> Captured DNS query and response during `nslookup`.

![DNS Traffic](screenshots/dns.png)

---

### 3. TCP 3-Way Handshake
> Captured the SYN → SYN-ACK → ACK sequence during a connection setup.

![TCP Handshake](screenshots/tcp-handshake.png)

---

### 4. TCP Port 80 Traffic (HTTP Attempt)
> Captured TCP packets directed to Port 80 (HTTP protocol port), even though direct HTTP traffic was force-upgraded to HTTPS.

![TCP Port 80 Traffic](screenshots/Captured%20TCP%20Port%2080%20Traffic%20(HTTP).png)

---

### 5. Random Traffic Snapshot (Extra)
> Captured miscellaneous background traffic.

![Random Traffic](screenshots/RANDOMTRAFFIC.png)

---

## 📂 Project Structure


---

## 🧠 Skills Practiced

- Packet capturing and saving
- Applying Wireshark filters
- Analyzing ICMP, DNS, TCP handshakes, and HTTP-related traffic
- Documenting findings with screenshots
- Real-world troubleshooting with HTTPS-only environments

---

## 🛡 Notes
Due to modern network and browser security policies, direct HTTP traffic could not be captured as it was auto-upgraded to HTTPS. TCP Port 80 traffic was still captured and analyzed as part of the lab.

---
