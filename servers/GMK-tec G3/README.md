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
| Tailscale        | Secure remote access           | Online |

## Notes

The aim is to keep this machine focused on everyday services. More experimental workloads can run on the ThinkCentre machines so testing does not unnecessarily affect these services.

The N100 acts as the foundation of the homelab, providing essential services while the other machines are used for learning, experimentation and security testing.
