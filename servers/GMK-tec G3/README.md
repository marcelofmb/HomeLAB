# GMKtec N100

## Overview

The GMKtec mini PC with an Intel N100 processor is intended to be the low-power, always-on machine in my homelab. It will host lightweight services that I want available without keeping the larger lab machines running.

## Hardware

- Device: GMKtec Mini PC
- Processor: Intel N100
- RAM / Storage: 8GB / 254GB

## Operating System – CasaOS

CasaOS is an open-source home server management platform designed to make self-hosting easier. It provides a web-based graphical interface that allows users to manage applications, Docker containers, storage and system resources without relying entirely on command-line tools.

CasaOS runs on top of an existing Linux distribution rather than being a standalone operating system. It integrates with Docker, allowing applications to be installed and managed through its interface.

<img width="2558" height="1365" alt="Screenshot 2026-08-25 183308" src="https://github.com/user-attachments/assets/80a44912-c995-4337-9a9f-784f175f8561" />


### Main Features

- **Web Dashboard:** Centralised interface for managing the server.
- **App Store:** Easily install and manage supported self-hosted applications.
- **Docker Management:** Deploy and control Docker containers.
- **File Management:** Browse and organise files and storage.
- **System Monitoring:** View resource usage and application status.

CasaOS is used on this machine because its graphical interface makes everyday server management straightforward while keeping the system lightweight.

## Services

| Service          | Purpose                        | Status |
|------------------|--------------------------------|--------|
| Minecraft server | Host a Minecraft world         | Online |
| Pi-hole          | Network-wide DNS filtering     | Online |
| Twingate         | Secure remote access           | Online |
| Immich           | photo and video management     | Online |

---

<p align="center">
  
  <img src="https://github.com/user-attachments/assets/2158bb55-6f8e-4c2d-9e90-c42de4ee3cfa" width="100%" alt="GMKtec N100 server dashboard">
  <br>
  <strong>GMKtec N100 – Crafty -> Minecraft Server</strong>
  
</p>

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/2e64fc13-a20f-4c8b-a640-f45b07239cd1" width="100%" alt="GMKtec N100 service overview">
  <br>
  <strong>Homelab – Immich/strong>
    
</p>

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/653cb9a3-35a5-45a6-8ea6-1c67df92c877" width="100%" alt="GMKtec N100 server configuration">
  <br>
  <strong>GMKtec N100 – Twingate</strong>
  
</p>

---
The aim is to keep this machine focused on everyday services. More experimental workloads can run on the ThinkCentre machines so testing does not unnecessarily affect these services.

The N100 acts as the foundation of the homelab, providing essential services while the other machines are used for learning, experimentation and security testing.
