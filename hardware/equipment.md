# Equipment

A quick inventory of the hardware currently used in my homelab. The
setup is evolving, so I will update this page when equipment or roles
change.

  ------------------------------------------------------------------------
  Device                                    Quantity Main role
  --------------------- ---------------------------- ---------------------
  GMKtec Mini PC (Intel                            1 Lightweight,
  N100)                                              always-on services

  Lenovo ThinkCentre                               2 Virtualisation, Linux
  M700                                               server and security
                                                     labs

  NETGEAR GS308E                                   1 Managed network
                                                     switching
  ------------------------------------------------------------------------

## GMKtec N100

-   Processor: Intel N100
-   Intended role: Run lightweight services that should remain
    available.
-   Intended services: Minecraft server, Pi-hole and Twingate.

## Lenovo ThinkCentre M700 #1

-   Current software: Proxmox VE
-   Current lab VM: Kali Linux
-   Role: Virtualisation and isolated cybersecurity experiments.

## Lenovo ThinkCentre M700 #2

-   Operating system: Ubuntu Server
-   Container platform: Docker
-   Known workloads/tools: Suricata, Grafana, Loki, Promtail, OWASP
    Juice Shop and RackPeek.

## NETGEAR GS308E

-   8-port Gigabit Easy Smart Managed Switch
-   Role: Connect homelab devices and support managed-network
    experiments.

## Power

A previous idle measurement for the three computers and the switch
together was approximately **23 W**. Consumption varies with workload.

## Future updates

I will add exact CPU, RAM, storage and power details when I have
verified them.

