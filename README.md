# wireshark-traffic-analysis-task-5
Captured and analyzed live network traffic using Wireshark as part of a cyber security internship task. Includes .pcap file and analysis report on identified protocols.


# 📡 Wireshark Network Traffic Analysis – Cyber Security Task 5

## 📁 Task Overview
Capture live network traffic using Wireshark and analyze protocols to understand how data flows over the internet.

---

## ✅ Steps Followed

1. **Installed Wireshark** on my system.
2. **Started packet capture** on the active network interface.
3. **Generated traffic** by browsing websites and pinging servers.
4. **Stopped the capture** after ~1 minute.
5. **Applied filters** such as:
   - `http`
   - `dns`
   - `tcp`
   - `tls`
6. **Identified protocols** involved in the traffic.
7. **Saved the capture** as `capture.pcap`.
8. **Wrote a report** describing key protocols and insights.

---

## 🔍 Protocols Identified

- **TCP** – Connection-based data transmission.
- **HTTP** – Unsecured web traffic.
- **DNS** – Domain resolution (e.g., `google.com` to IP).
- **UDP** – Lightweight data transfer.
- **TLS** – Encrypted traffic (HTTPS).

---

## 📦 Files in this Repository

- `capture.pcap` → Raw packet capture.
- `analysis_report.md` → Written report of findings.
- `README.md` → Task explanation and structure.

---

## 🎯 Key Learnings

- Used Wireshark to observe real-time traffic.
- Understood how filtering helps isolate relevant packets.
- Learned how TCP/IP and other protocols function.
- Saw how encryption (TLS) hides sensitive content.
