# CodeAlpha Cyber Security Internship: Tasks Submission (October Batch)

**Intern:** YOUR NAME HERE

| # | Task | Status |
|---|------|--------|
| 1 | Basic Network Sniffer | Completed |
| 2 | Phishing Awareness Training | Completed |

---

## Task 1: Basic Network Sniffer

**GitHub (Task 1 README):** `(https://github.com/null000000000/Task1_Basic_Network_Sniffer)`

### What I built
A Python program that uses `scapy` to capture live network packets and break them down so the structure of network traffic is easy to understand. For every packet it displays:
- time, source and destination IP, protocol (TCP, UDP, ICMP) and size
- source and destination ports, and TCP flags
- DNS queries and ICMP type/code
- a payload preview in text and hex

It also supports filters (for example `tcp port 80`), a packet count, saving to a `.pcap` file for Wireshark, and a protocol summary at the end.

### How I tested it
I tested it on **Kali Linux inside VirtualBox**, on a lab network I own:
1. Ran `nmap -sn` on the lab subnet to find live hosts.
2. Ran the sniffer with `sudo ./snifer.py` and captured live traffic. It printed a UDP packet with its IPs, ports and payload (text and hex).

![Live capture](Task1_Basic_Network_Sniffer/screenshots/05_sniffer_live_capture.png)
![Nmap lab scan](Task1_Basic_Network_Sniffer/screenshots/04_nmap_lab_host_discovery.png)

### What I learned
How data moves through the network layers (Ethernet, IP, TCP/UDP, data), the differences between TCP, UDP and ICMP, and why encrypted traffic shows unreadable payloads.

Files: [`Task1_Basic_Network_Sniffer`](Task1_Basic_Network_Sniffer)

---

## Task 2: Phishing Awareness Training

**GitHub (Task 2 repository):** `https://github.com/null000000000/Task2_Phishing_Awareness`

**Live demo (Vercel):** https://snofsdidfvodnvsdnvov.vercel.app/

### What I built
An interactive web training module about phishing attacks. It covers:
- **6 attack types:** email phishing, spear phishing, smishing, vishing, whaling/BEC and clone sites
- **Live email inspection:** a realistic mail client with 6 clickable red flags
- **Fake website recognition:** the right-to-left domain reading rule plus a live domain parser that splits any URL into subdomain and real root domain
- **Social engineering:** 6 psychological triggers used by attackers
- **Real cases:** Google/Facebook, Twitter, RSA and Target
- **Best practices** and what to do after clicking a malicious link
- **An 8-question quiz** with a result at the end

![Landing page](Task2_Phishing_Awareness/screenshots/01_landing_page.png)
![Attack vectors](Task2_Phishing_Awareness/screenshots/02_attack_vectors_module.png)
![Domain parser](Task2_Phishing_Awareness/screenshots/03_fake_website_domain_parser.png)

Files and full explanation: [`Task2_Phishing_Awareness`](Task2_Phishing_Awareness)

---

## Legal note
The sniffer was used only on a lab network that I own. Use it only where you have permission.

#CodeAlpha
