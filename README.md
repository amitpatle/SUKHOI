
  
```
███████╗██╗   ██╗██╗  ██╗██╗  ██╗ ██████╗ ██╗
██╔════╝██║   ██║██║ ██╔╝██║  ██║██╔═══██╗██║
███████╗██║   ██║█████╔╝ ███████║██║   ██║██║
╚════██║██║   ██║██╔═██╗ ██╔══██║██║   ██║██║
███████║╚██████╔╝██║  ██╗██║  ██║╚██████╔╝██║
╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝
```
  


###  - A Powerful Linux Tool for Victim Source Gathering

**SUKHOI** is an advanced, open-source Linux tool specifically crafted for gathering victim source data in cybersecurity investigations, penetration testing, or digital forensics. With its robust functionality and user-friendly interface, **SUKHOI** allows security professionals and ethical hackers to efficiently collect and analyze sensitive information from target systems, network traffic, and online footprints.

---

### Key Features:

- **System Enumeration:**  
  Automatically scans and collects vital system information, such as user accounts, processes, network interfaces, active sessions, and more.

- **Network Traffic Sniffing:**  
  Monitors and logs network traffic on local and remote systems to capture key network details, including open ports, protocols, and active connections.

- **Credential Harvesting:**  
  Collects and analyzes potential password and credential-related data, including those exposed via unencrypted channels or weakly secured services.

- **Service & Vulnerability Mapping:**  
  Identifies active services and possible vulnerabilities on the target system, enabling better preparation for further penetration testing or exploitation efforts.

- **OS Fingerprinting:**  
  Quickly identifies the underlying operating system of remote machines, allowing users to tailor their attacks or recon strategies accordingly.

- **Log File Analysis:**  
  Extracts and analyzes system log files for any evidence of suspicious or anomalous activities, which might help in identifying compromised or vulnerable systems.

- **Web Scraping & Data Extraction:**  
  Gathers useful metadata from publicly accessible web pages, such as email addresses, usernames, and other potential targets for spear-phishing or social engineering attacks.

- **Comprehensive Reporting:**  
  After collecting the necessary information, **SUKHOI** generates detailed reports that can be exported in various formats (CSV, PDF, etc.) for easy analysis and documentation.

- **Stealth Mode:**  
  Operates with stealth capabilities to reduce detection by traditional security defenses, ensuring smooth gathering of victim-related data without alerting the target.

- **Compatibility:**  
  Fully compatible with all major Linux distributions (Ubuntu, Kali, Debian, Fedora, etc.) and integrates seamlessly with other pen-testing frameworks like Metasploit, Burp Suite, and Nmap.

---

### Use Cases:

- **Penetration Testing:**  
  Gather crucial information about your test environment and identify weak spots or misconfigurations before conducting in-depth exploitation.

- **Incident Response & Forensics:**  
  Quickly obtain actionable intelligence from compromised systems to track down the cause of the breach and determine the scope of the attack.

- **Social Engineering Campaigns:**  
  Collect data that could aid in crafting more targeted and effective social engineering tactics, such as phishing emails or phone scams.

- **Threat Intelligence Collection:**  
  Harvest information from public-facing sources, identify emerging threats, and gather intelligence on potential future targets.

---

### Installation:

To install **SUKHOI**, simply clone the repository from GitHub and follow the instructions in the README for setup.

```bash
git clone https://github.com/amitpatle/SUKHOI.git
cd SUKHOI
sudo bash install.sh

chmod +x SUKHOI.py

python2 SUKHOI.py
```

---

### Disclaimer:

**SUKHOI** is intended strictly for legal and ethical use. It is your responsibility to ensure compliance with local laws and regulations regarding data collection, cybersecurity, and penetration testing. Always obtain explicit permission before performing any gathering activity on a system or network that you do not own.

---

 ``` ⠀⠀⠀⠀⠀⠀⠀⠀⠀
           ⠀⠀⠀⠀⠀⠀⠀⠀⣀⣴⡖⠿⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣞⡻⠉⢀⠀⠈⠳⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⡏⠀⡂⣸⣦⠀⠀⠘⢦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⢻⠉⠻⠐⣭⡀⠀⠙⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⠀⢡⠤⠜⠂⠀⠀⠈⠘⠀⠀⠀⠱⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣠⠞⠁⠙⢦⣀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠣⡀⠀⠀⠀⠀⠀⠀⠀⣀⠤⠤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢸⡀⠀⠀⠀⠉⠳⣄⠀⠀⣹⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣠⣼⣶⣶⢒⣛⡻⢥⡤⣀⠀⢮⡗⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⢰⣶⣿⣿⣿⣾⣧⣤⣬⣤⣀⣙⣿⣤⣽⡆⠂⠂⡀⠀⠀⠀⠀⣀⠀⠠⠐⠂⠈⡋⣟⣿⣇⣠⡀⡼⣏⣉⡉⠱⣿⣿⣶⣶⠒⠒⠒⠒⠒⠒⠒⠒⠢⠤⢄⡀
⠀⠀⠀⠀⠉⠉⢛⣿⢿⣿⣿⣿⣿⣿⣿⡿⠁⠀⠀⠀⠀⠀⠀⠄⠀⠀⠀⠀⠂⠂⠀⠉⣟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣿⣷⣶⣶⣶⣶⣶⣶⣾⣿⠿⠛⠁
⠀⠀⠀⠀⠀⠀⠈⠛⢻⣿⣿⣿⣿⡏⢁⣀⣀⣠⣤⣤⡤⠀⢀⠀⠀⢀⡀⣀⣠⣤⣿⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⠿⢿⠟⠛⠋⠉⠉⠀⠀⠀⠀                               
⠀⠀⠀⠀⠀⠀⠀⠀⢻⣿⣿⣿⣿⣿⡿⠿⠛⠛⠉⠀⠀⠒⢾⠤⠤⠤⠀⠚⠛⠉⢩⠙⠛⠛⠟⠿⣿⡿⢿⡿⣿⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⣀⣿⣿⠟⢻⠁⠀⠀⢀⣀⣀⣀⣀⠤⠀⠀⠀⠀⠀⢀⣤⡤⠼⣴⣤⣤⣤⣤⣿⡿⠿⠛⠛⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠠⢶⣶⣶⣿⣦⣤⣠⣿⣿⣶⣾⣿⣶⣿⣿⠿⠿⠛⠁⠀⠀⠀⠀⠤⠤⠶⠿⢿⣿⣿⣿⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠉⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣤⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣾⠿⠿⠿⠿⠙⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣿⠟⢿⣿⣿⣿⣿⡿⢻⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣾⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⣸⡇⠀⣿⣿⣿⣿⠟⠀⢸⠋⠀⠀⠀⠀⠠⣤⣀⣄⣴⡿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢀⡟⠀⢠⣿⣿⡟⠁⠀⠀⡸⠁⠀⠠⠀⠀⠁⠀⢉⣿⠟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣾⠀⠀⣼⡟⠁⠀⠀⠀⢠⡇⢀⢄⡞⠀⠀⡳⣴⡿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠈⠙⠚⠋⠀⠀⠀⠀⢀⣾⠇⠡⠈⠀⠀⢀⣾⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠿⡆⠀⠀⢀⣴⠏⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣷⣶⣾⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀

```
