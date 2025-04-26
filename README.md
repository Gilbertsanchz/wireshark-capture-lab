# Wireshark Capture & Protocol Analysis Lab

## Overview
This lab involved capturing and analyzing real network traffic using Wireshark on macOS.  
The goal was to capture key protocols (ICMP, DNS, TCP Handshake, and HTTP/TCP Port 80 Traffic) and apply Wireshark filters to analyze them.

## Traffic Captured
- **ICMP** — Captured using `ping google.com`
- **DNS** — Captured using `nslookup openai.com`
- **TCP 3-Way Handshake** — Captured using a new HTTP request
- **TCP Port 80 Traffic** — Attempted HTTP capture; modern HTTPS enforcement upgraded most connections, but TCP port 80 traffic was successfully captured and analyzed.

## Folder Structure


## Skills Practiced
- Network traffic capture
- Display filtering in Wireshark
- Understanding protocol structures (ICMP, DNS, TCP handshake)
- Real-world troubleshooting when HTTP traffic is auto-upgraded to HTTPS

## Notes
Due to current network and browser security policies, direct HTTP traffic was not captured — however, TCP Port 80 traffic was successfully filtered and captured to demonstrate the HTTP initiation process.
