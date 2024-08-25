# VPN-Deployment-with-BDF-XDP-Technology-by-Path-Network

This project demonstrates how to set up a DDoS-protected VPN server using BDF/XDP Technology by Path Network on Linux Ubuntu 20.04. We'll be installing the Pritunl panel, configuring DDoS protection using FranTech Stallion, and setting up the necessary firewall rules.

## Prerequisites

- Access to FranTech Stallion: You'll need this for managing firewall settings and implementing DDoS protection.
- A VPN Server: This will be used to whitelist protocols such as SSH, HTTP, HTTPS, and Pritunl, ensuring only authorized traffic is allowed.
- SSH Access to the Server: Secure remote access is necessary to configure and manage the server.

*Hardware Requirements*
- **Linux Server:** A Linux server (Ubuntu preferred) with:
  - **CPU:** 1 GHz or higher
  - **RAM:** 2 GB or more
  - **Disk Space:** 10 GB free space
- **Network Configuration:** Static IP address for consistent network communication.

*Software Requirements*
- **Operating System:** Ubuntu 20.04 LTS or later.


## Installation Steps

### 1. Update and Upgrade the System
First, make sure your system is up-to-date.
```bash
sudo apt-get update && sudo apt-get upgrade -y
sudo apt update && sudo apt -y full-upgrade
