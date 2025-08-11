# Firewall Documentation 

**Last Updated:** 2025-08-11  
**Purpose:** Secure and manage traffic in home network

### Device Information 
Model: Protectli Vault FW4B  
Firmware/OS: 2.8.0  
Location: Closet


### Interfaces

I'll have these interfaces go as follows:  
**INTERFACE | NAME | SUBNET | VLAN | PURPOSE**

`igb0 | WAN  | DHCP (ISP)  | Internet Access`  
`igb1 | LAN  | X.X.X.X     | Home Network`  
`igb2 | OPT1 | N/A         | Planned to be used to segment lab equipment`  
`igb3 | OPT2 | N/A         | N/A`

### Firewall Rules

As of `2025-08-11` these are the firewall rules. *Excludes the default rules*.

**FORMAT**:  
**Name | Protocol | Source | Src Port | Destiniation | Dst Port | Gateway**  
**WILL NOT DISPLAY IPS OR PORTS FOR OBVIOUS SECURITY REASONS**

`WIREGUARD | TCP/UDP | * | * | X.X.X.X | XXX | * `

### Extra Services 

`Snort 4.1.6`  
`Suricata 7.0.8`  
`ACME .9`



