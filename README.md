# Proxmox Home Lab with Self-Hosted Services

## Project Overview

This repository documents my home network setup using Proxmox VE (Virtual Environment) to host various network services. The project aims to create a robust, efficient, and secure home network infrastructure.

### Key Components

- **Proxmox VE**: The core hypervisor platform
- **Docker**: For containerized service deployment
- **TrueNAS**: Network-attached storage solution
- **Pi-hole**: Network-wide ad blocking
- **Nginx Proxy Manager**: Reverse proxy for web services

## Features

- **Centralized Management**: All services are managed through the Proxmox web interface
- **Containerization**: Utilizing Docker for efficient resource usage and easy deployment
- **Data Redundancy**: Implemented RAIDZ1 for improved data protection
- **Network Security**: Enhanced with Pi-hole for network-wide ad blocking
- **Custom Monitoring**: Grafana dashboards for comprehensive system and network monitoring

## Services Deployed

1. TrueNAS
2. Pi-hole
3. Nginx Proxy Manager
4. Portainer
5. Custom monitoring (InfluxDB, Grafana): [check it](https://github.com/nattycoder/Proxmox-monitoring-InfluxDB-Grafana)
6. Homepage
7. more services will be deployed

## Future Plans

- Implement automated backups
- Enhance network segmentation for improved security
- Explore integration with home automation systems

## Configurations

Detailed configuration files and setup instructions for each service will be added to this repository very soon. Stay tuned for updates!

## Contributing

This is a personal project, but suggestions and ideas are welcome. Feel free to open an issue for discussion.

---

Last updated: [Current Date]
