# Homelab

A small homelab built to learn, experiment, and gain practical
experience with IT infrastructure, networking, Linux, and cybersecurity.

## Motivation

I started this project to understand how the systems and services I use
every day actually work. Instead of relying only on theory, I want to
build and manage my own environment, break things safely, troubleshoot
problems, and document what I learn.

My main interests are cybersecurity, networking, self-hosting, and
server administration.

## Goals

-   Improve my Linux and Windows Server administration skills.
-   Learn networking, VLANs, firewalling, and traffic monitoring.
-   Host useful services locally instead of relying on multiple
    subscriptions.
-   Build a safe environment for cybersecurity practice.
-   Experiment with virtualisation, containers, and monitoring.
-   Document configurations, problems, and solutions as I go.

## Hardware

  -----------------------------------------------------------------------
  Device                              Purpose
  ----------------------------------- -----------------------------------
  GMKtec Mini PC (Intel N100)         Main services and always-on
                                      workloads

  Lenovo ThinkCentre M700 #1          Proxmox and virtual machines,
                                      including Kali Linux

  Lenovo ThinkCentre M700 #2          Ubuntu Server and Docker-based
                                      services

  NETGEAR GS308E                      Managed network switch
  -----------------------------------------------------------------------

The setup is evolving, so hardware roles and services may change over
time.

## Software & Services

-   **Proxmox** --- virtualisation and lab environments
-   **Ubuntu Server / Debian** --- Linux server administration
-   **Docker** --- running self-hosted applications
-   **Pi-hole** --- network-wide DNS filtering
-   **Tailscale** --- secure remote access
-   **Minecraft server** --- self-hosted game server
-   **Suricata** --- network threat detection
-   **Grafana + Loki** --- monitoring and log visualisation
-   **OWASP Juice Shop** --- web application security practice

Not every service runs on the same machine, and some are experimental.

## What I'm Learning

This homelab is a practical learning environment. I use it to practise
system administration, networking, monitoring, virtualisation, container
management, and defensive security. I also use isolated virtual machines
and intentionally vulnerable applications to explore security concepts
safely.

## Documentation

I'll add notes and guides as the lab develops, including:

-   Setup and configuration steps
-   Network changes
-   Useful commands
-   Issues and troubleshooting
-   Lessons learned

This is an ongoing project. The goal is not to build the biggest
homelab, but to understand what I build and keep improving it.
