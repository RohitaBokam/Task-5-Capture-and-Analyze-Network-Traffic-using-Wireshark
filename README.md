# Task-5-Capture-and-Analyze-Network-Traffic-using-Wieshark
# 🧪 Network Traffic Capture & Analysis using Wireshark

**Introduction:**
This project demonstrates the process of capturing live network traffic using **Wireshark**, identifying key internet protocols in action, and analyzing the behavior of network packets during everyday activities such as browsing and pinging.

---

## 📌 Objective

- Capture live network packets using Wireshark.
- Identify and analyze at least three different network protocols.
- Save the packet capture in `.pcap` format.
- Generate a short report summarizing findings.

---

## 🛠️ Tools Used

- [Wireshark](https://www.wireshark.org/) – Free and open-source packet analyzer  
- Operating System: Windows / Linux / macOS  
- Internet connection (for generating traffic)

---

## 📋 Steps Performed

1. **Installed Wireshark** on the system.
2. **Started packet capture** on the active network interface.
3. **Generated traffic** by:
   - Visiting a website: `https://example.com`
   - Using the `ping` command to reach `google.com`
4. **Filtered and analyzed** packets by protocol using Wireshark filters (`http`, `dns`, `icmp`, `tcp`).
5. **Saved the captured packets** as `network_capture.pcap`.
6. **Documented findings** in a detailed report.

---

## 🔍 Protocols Identified

| Protocol | Port | Purpose                        |
|----------|------|--------------------------------|
| **DNS**  | 53/UDP | Resolving domain names to IP addresses |
| **HTTP** | 80/TCP | Requesting and receiving web content |
| **ICMP** | N/A  | Diagnostics and ping operations |
| **TCP**  | Varies | Reliable transport layer communication |

---

## 📄 Sample Observations

* DNS queries resolved domain names before TCP connections were initiated.
* HTTP GET requests retrieved web content from `example.com`.
* ICMP echo request and reply packets were seen during the ping test.
* TCP handshake (SYN, SYN-ACK, ACK) was visible before HTTP communications.

---

## 📌 How to Reproduce

1. Install Wireshark from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
2. Start a new capture on your active interface.
3. Open a browser and navigate to any website.
4. Open a terminal and run:

   ```bash
   ping google.com
   ```
5. Stop the capture after 30–60 seconds.
6. Filter protocols and save your capture as `.pcap`.

---

## 📘 Report

A detailed report (`Report.pdf`) includes:

* Summary of steps
* Protocol analysis
* Packet examples
* Conclusion

---

## ✅ Deliverables

* ✔️ `network_capture.pcap`
* ✔️ `Report.pdf` summarizing captured traffic


