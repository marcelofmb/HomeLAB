# Network Topology

This is a high-level overview of the homelab network. The setup is
evolving; this diagram does not claim to show configured VLANs, firewall
rules or exact IP addresses.

## Physical layout

``` mermaid
flowchart TD
    Internet((Internet)) --- Router[Home router]
    Router --- Switch[NETGEAR GS308E]
    Switch --- N100[GMKtec N100]
    Switch --- M700A[ThinkCentre M700 #1<br/>Proxmox VE]
    Switch --- M700B[ThinkCentre M700 #2<br/>Ubuntu Server]
```

## Network goals

-   Understand IP addressing, DNS and DHCP.
-   Practise managed switching and VLAN configuration.
-   Learn firewall rules and network segmentation.
-   Monitor traffic and investigate suspicious activity.
-   Keep security experiments isolated from important services.

## Services and technologies

  Technology       Purpose                            Status
  ---------------- ---------------------------------- --------------------
  NETGEAR GS308E   Managed switching                  In use
  Tailscale        Secure remote access               Intended for N100
  Pi-hole          DNS filtering                      Intended for N100
  Suricata         Network threat detection           Lab use
  VLANs            Separate devices and experiments   Learning / planned

## Configuration details to add

-   Router / gateway:
-   LAN subnet:
-   DHCP range:
-   DNS server:
-   Switch management address:
-   VLAN IDs and purpose:
-   Important firewall rules:

Do not publish public IP addresses, passwords, VPN keys, private
certificates or other sensitive information. Redact these values before
committing configuration examples.
