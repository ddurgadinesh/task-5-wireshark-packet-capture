# 📡 Task 5 – Wireshark Packet Capture & Protocol Identification

##  Objective
The aim of this task was to capture live network packets using Wireshark and identify at least three common protocols such as DNS, TCP, and ICMP. I used my phone's hotspot for the internet connection and observed the traffic generated while using basic tools.

##  Tools Used
- **Wireshark** – For capturing and analyzing network packets
- **Windows Command Prompt** – To generate ping (ICMP) traffic
- **Chrome Browser** – For browsing websites
- **Mobile Hotspot** – Used as the active internet source

##  What I Did

1. Started Wireshark and selected the active Wi-Fi adapter (from phone hotspot).
2. Began live packet capture.
3. Visited a few websites like Google and YouTube to generate DNS and TCP traffic.
4. Opened Command Prompt and ran `ping 8.8.8.8` to generate ICMP traffic.
5. Stopped the capture after about a minute.
6. Applied protocol filters in Wireshark (`dns`, `tcp`, and `icmp`) to inspect different types of traffic.
7. Took relevant screenshots of each protocol’s packets to include in this report.

##  Protocols Captured

### 🔹 DNS – Domain Name System
I saw multiple DNS queries resolving domain names like `google.com` to their corresponding IP addresses.

### 🔹 TCP – Transmission Control Protocol
TCP packets appeared while connecting to websites. I was able to observe the SYN and ACK flags during the connection setup.

### 🔹 ICMP – Internet Control Message Protocol
ICMP packets were visible after I ran the ping command in Command Prompt. Both Echo Request and Echo Reply packets were captured between my device and the Google DNS server (8.8.8.8).

## Files Included
- Wireshark capture file (`.pcap`)
- Four screenshots showing the captured packets and ping output
- This `README.md` report

## ✅ Summary
This task gave me hands-on experience with packet-level network traffic. It was interesting to see how basic internet activity results in various types of traffic, and how protocols like DNS, TCP, and ICMP are involved in everyday browsing and connectivity.
