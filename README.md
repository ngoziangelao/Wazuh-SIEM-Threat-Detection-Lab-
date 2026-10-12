 Wazuh SIEM & Threat Detection Lab 🛡️

A hands-on SOC lab where I set up Wazuh SIEM to monitor a network, catch suspicious activity using Suricata, and automatically check files for viruses using VirusTotal.


📌 Setup at a Glance
* Wazuh Manager: Kali Linux (The central brain & dashboard)
* Wazuh Agent: Ubuntu (The monitored machine)
* Traffic Inspector: Suricata NIDS (Watches network activity)
* File Scanner: VirusTotal API (Scans files for malware)
* Lab Environment: VirtualBox



# 🚀 What I Did & How It Works

1. *Connected Monitored Systems:*Linked my Ubuntu virtual machine to my Wazuh manager on Kali Linux so logs flow into one central dashboard.
2. *Set Up Network Defense (Suricata):*Installed Suricata on Ubuntu to inspect network traffic and send live threat alerts straight to Wazuh.
3. *Automated Virus Scanning (VirusTotal):*Configured Wazuh to automatically send file signatures to VirusTotal whenever a new file appears or changes on the system.
4. *Tested Everything:*Triggered test alerts and downloaded a safe test malware signature (EICAR) to confirm that alerts appear on the dashboard in real time.

---

# 💡 Key Takeaway
"Cybersecurity isn't always about getting everything right immediately. It's about breaking things, troubleshooting, learning from errors, and building stronger defenses."