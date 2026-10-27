# CodeAlpha Cyber Security Internship — October Batch

**Intern:** Ahmed Mahdy

## Tasks Submission

| Task | Status |
|---|---|
| Task 1: Basic Network Sniffer | Completed |
| Task 2: Phishing Awareness Training | Completed |

---

## Task 1: Basic Network Sniffer

**GitHub Repository:** https://github.com/null000000000/Task1_Basic_Network_Sniffer

### What I Built
A Python network sniffer using Scapy to capture live network packets and make network traffic easier to understand.

Features include:
- Displays timestamps, source and destination IP addresses, protocols, and packet sizes.
- Extracts source and destination ports and TCP flags.
- Identifies DNS queries and ICMP type/code.
- Displays payload previews in text and hexadecimal.
- Supports BPF filters, packet count, interface selection, and PCAP export.
- Prints a protocol summary after capture.

### How I Tested It
Tested on Kali Linux inside VirtualBox using a lab network I own.

- Used `nmap -sn` to discover active hosts on the lab subnet.
- Captured live traffic using the Python sniffer.
- Inspected packet addresses, ports, and payload data.

### What I Learned
Network encapsulation, TCP/UDP/ICMP fundamentals, packet inspection, and the differences between readable plaintext traffic and encrypted HTTPS traffic.

---

## Task 2: Phishing Awareness Training

**GitHub Repository:** https://github.com/null000000000/Task2_Phishing_Awareness

**Live Demo:** https://snofsdidfvodnvsdnvov.vercel.app/

### What I Built
An interactive web-based training module designed to teach users how to recognize and avoid phishing attacks.

Features include:
- **Six attack types:** Email phishing, spear phishing, smishing, vishing, whaling/BEC, and clone sites.
- **Email inspection:** A realistic email interface with six clickable red flags.
- **Fake website recognition:** Domain-reading guidance and an interactive URL parser.
- **Social engineering:** Six psychological triggers commonly exploited by attackers.
- **Real-world cases:** Google/Facebook, Twitter, RSA, and Target.
- **Security best practices:** Guidance on prevention and responding to malicious links.
- **Interactive quiz:** Eight questions with a final result.

---

## Legal Notice

The network sniffer was tested only on a lab network I own. Network monitoring should only be performed on systems and networks where you have permission.
