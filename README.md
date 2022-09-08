# networking
A collection of vagrant, docker and k8s scripts for maintaining a fully fledged enterprise network. Including personal documentation

## Network component schematica:

- Cisco Router (vagrant)
- Fortinet Firewall (vagrant)
- Cisco virtual L2 switch (vagrant)
- Windows DHCP & DNS (vagrant)
- Windows 10 Client (vagrant)
- Debian Client (vagrant, docker)
- Fortinet Loadbalancer QoS (vagrant)
- Fileserver (vagrant)
- Backupserver Veeam (vagrant)
- Windows Active Directory (vagrant)
- Webserver/CMS/SFTP (docker)
- ERP Software (SAP if possible, (vagrant))

## Intended practices

- Maintenance and structured problem solving of network failures
- Installation and configuration of common enterprise level components such as (DHCP, DNS, AD, Veeam)
- DHCP Ranges, Reservations
- DNS common entries
- Installation of a domain controller and configuring own domain
- Getting stronger in Cisco Routing and Fortinets Fortigates.
- Cisco Router: Installation and configuration of common services including QoS, L3 features etc.
- Fortinet Firewall: Get better at: ACL, IDS/IPS, configuring rules and evaluating network failures
- Installing veeam and maintaining a backup logic
- Network security achieved through LAN segmentation and micro-segmentation
- Configuring VLAN access
- Installing SCCM and provisioning virtual machines through network boot

# What even is Vagrant and why should I bother using it?

# Suggested Pre-requesities

I heavily suggest the use of the new Microsoft Windows Terminal which is available here: https://apps.microsoft.com/store/detail/windows-terminal

# Installing and configuring Vagrant on Windows 10/11 Host

## Synopsis

In this section I will cover how to setup vagrant and how to prepare your host-environment for the re-production of this lab-environment.

## Download Vagrant

You can simply download Vagrant from this link: https://www.vagrantup.com/downloads. In my case, I use a Windows 11 64bit Host, so I chose amd64. 
After the download you should be able to run the .msi file and accept the license agreement. After that a UAC Elevation windows should popup which you need to confirm.
