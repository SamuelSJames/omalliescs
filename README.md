# Omallies Coffee Shop
***UNDER CONSTRUCTIONS***
Welcome to the Omallies Coffee Shop Network Design and Configuration repository! This repository contains all the necessary network configurations and design files for setting up and maintaining the network infrastructure of Omallies Coffee Shop. This was a totally emulated projected in GNS3! 

![network-design](/configs/assets/network-design-diagram.png)

## Table of Contents

- [Introduction](#introduction)
- [Network Overview](#network-overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Device Configurations](#device-configurations)
  - [PFsense Firewall](#pfsense-firewall)
  - [Cisco IOS Switch](#cisco-ios-switch)
  - [Cameras](#cameras)
  - [Proxmox Server](#proxmox-server)
  - [Registers](#registers)
  - [Juniper Mist Access Point](#juniper-mist-access-point)
  - [VoIP Phones](#voip-phones)
  - [Asterisk VM](#asterisk-vm)
  - [Uptime Kuma Monitoring](#uptime-kuma-monitoring)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project documents the network design and configuration for Omallies Coffee Shop. The network is designed to ensure security, reliability, and ease of management, accommodating all the essential devices and services required for the coffee shop's operations.

## Network Overview

The network includes the following devices and services:
- **PFsense Firewall:** Provides network security and routing.
- **Cisco IOS Switch:** Manages network traffic and device connectivity.
- **5 Cameras:** For security surveillance.
- **Proxmox Server:** Hosts virtual machines, including an Asterisk VM for VoIP services.
- **2 Registers:** For processing transactions.
- **Juniper Mist Access Point:** Provides wireless connectivity.
- **2 VoIP Phones:** For voice communication.
- **Asterisk VM:** Manages VoIP services, hosted on the Proxmox server.
- **Uptime Kuma:** Monitors network and device uptime, running in an AWS EC2 instance.

## Repository Structure

The repository is structured as follows:

```bash
Omalliescs/
├── configs/
│   ├── pfsense/
│   │   └── pfsense-config.xml
│   ├── cisco/
│   │   └── switch-config.cfg
│   ├── cameras/
│   │   └── camera-configs/
│   │       ├── camera1.cfg
│   │       ├── camera2.cfg
│   │       ├── camera3.cfg
│   │       ├── camera4.cfg
│   │       └── camera5.cfg
│   ├── proxmox/
│   │   └── proxmox-config.cfg
│   ├── registers/
│   │   ├── register1.cfg
│   │   └── register2.cfg
│   ├── juniper/
│   │   └── ap-config.cfg
│   ├── voip/
│   │   ├── phone1.cfg
│   │   └── phone2.cfg
│   └── asterisk/
│       └── asterisk-config.cfg
├── docs/
│   └── network-design-diagram.png
├── scripts/
│   └── setup-scripts.sh
├── README.md
└── LICENSE
```

## Getting Started

To get started with setting up the Omallies Coffee Shop network, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Omallies-Coffee-Shop.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd Omallies-Coffee-Shop
   ```
3. Follow the configuration guides for each device listed in the `configs` directory.

## Device Configurations

### PFsense Firewall

Configuration file: `configs/pfsense/pfsense-config.xml`

Ensure the PFsense firewall is correctly set up to manage traffic and provide security.

### Cisco IOS Switch

Configuration file: `configs/cisco/switch-config.cfg`

Configure the Cisco switch for optimal network performance and device connectivity.

### Cameras

Configuration files: `configs/cameras/camera-configs/`

Set up each camera using the respective configuration file to ensure proper surveillance coverage.

### Proxmox Server

Configuration file: `configs/proxmox/proxmox-config.cfg`

Configure the Proxmox server to host virtual machines, including the Asterisk VM.

### Registers

Configuration files: `configs/registers/`

Ensure the registers are configured to process transactions efficiently.

### Juniper Mist Access Point

Configuration file: `configs/juniper/ap-config.cfg`

Set up the Juniper Mist Access Point for wireless connectivity.

### VoIP Phones

Configuration files: `configs/voip/`

Configure the VoIP phones for clear and reliable voice communication.

### Asterisk VM

Configuration file: `configs/asterisk/asterisk-config.cfg`

Set up the Asterisk VM on the Proxmox server to manage VoIP services.

### Uptime Kuma Monitoring

The Uptime Kuma instance is running in an AWS EC2 instance to monitor the network and device uptime.

## Contributing

I welcome contributions to improve the network design and configurations. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please contact me at [snsnetworksolutions.net](mailto:samueljamesinc@snsnetworksolutions.net).


### 🧰 **Languages and Tools**

<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />

<img align="left" alt="Pfsense" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pfsense/pfsense-original.svg" />
          
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />

<img align="left" alt="Docker" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
<img align="left" alt="AWS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />

<img align="left" alt="XML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/xml/xml-original.svg" />
          
<img align="left" alt="Cisco" width="30px" style="padding-right:10px;" src="/configs/assets/cisco-svgrepo-com.svg" />
