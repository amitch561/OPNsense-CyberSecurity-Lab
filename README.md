Security Lab Repository

Welcome to the Security Lab Repository. This repository contains the configuration files, network diagrams, tools, scripts, and documentation for a Proxmox-based security lab built with various VLANs and monitoring tools.

📖 Overview

This lab is designed to simulate a complex network environment with different VLANs for various purposes such as penetration testing, network monitoring, vulnerability scanning, and secure network management.

📁 Repository Structure

SecurityLab/

│
├── README.md               # This file, explaining the lab setup
├── /Diagrams               # Network diagrams and architecture visuals
├── /Configs                # Configuration files for various tools and systems
│   ├── OPNsense/           # OPNsense firewall configurations
│   ├── Proxmox/            # Proxmox network and VM configurations
│   └── Wazuh/              # Wazuh monitoring configurations
├── /Tools                  # Descriptions and setup instructions for installed tools
├── /LabNotes               # Experiment notes, penetration testing reports, monitoring reports
├── /Scripts                # Automation and configuration scripts
├── /Logs (Optional)        # Example logs (if applicable)

🔍 Lab Architecture

This lab consists of several VLANs, managed by an OPNsense Firewall hosted on Proxmox.

VLANs:

VLAN 110 (Metasploitable Net) - 172.16.110.0/24

VLAN 120 (Target Net) - 172.16.120.0/24

VLAN 130 (Security Tools) - 172.16.130.0/24

VLAN 140 (Client Net) - 172.16.140.0/24

Tools & Technologies Used:

Proxmox (Virtualization Platform)

OPNsense (Firewall / VLAN Management)

Wazuh (Monitoring Tool)

Nessus (Vulnerability Scanner)

Kali Linux / Parrot Security (Penetration Testing Tools)

Dockerized Applications (WebGoat, bWAPP, DVWA)

📊 Network Diagram

Network diagrams can be found in the /Diagrams folder. The diagrams illustrate the logical layout of the network and its components.

🔒 Configuration Files

All configuration files for OPNsense, Proxmox, and Wazuh can be found in their respective folders within /Configs.

⚙️ Scripts

Scripts created for automation, monitoring, or setup can be found in the /Scripts folder.

📚 Lab Notes

All reports, notes, and observations from experiments and tests are saved in the /LabNotes folder.

🌐 Future Expansion

The repository will be updated as the lab continues to expand and evolve. Future improvements may include additional VLANs, cloud integration, and more complex network scenarios.

📌 Usage

This lab is for educational purposes, providing a controlled environment to learn network security principles and improve cybersecurity skills.

📚 References

The following resources were helpful in building this lab framework:

Cybersecurity Video - YouTube Playlist - The deployment of some machines was done differently.

Mitre Caldera v5 Basics - https://www.youtube.com/playlist?list=PLF2bj1pw7-ZvLTjIwSaTXNLN2D2yx-wXH

📄 License

MIT License

Feel free to contribute, suggest improvements, or fork this repository for your own purposes. Happy learning and experimenting! 🚀

