---
layout: webserve
title: Web Services
permalink: /webservices/
---

I run a series of personal web services for myself, fellow students, and
interested third parties.  Also a good showcase of my personal system administration
experience.  Note that the subdomains of fssnow.com are not meant to host websites,
connecting to these with a web browser may produce unexpected results.

## seattleprime.cloud.fssnow.com

Vultr VPS ([referral code](https://www.vultr.com/?ref=8127346-4F)) running a self-maintained Arch Linux instance.

* Web Server - nginx mainline with PHP7.x and MariaDB (where this site is hosted)
* [Git and Build Server](https://git.nclf.net) - GitLab, GitLab CI replacing jenkins
* [Wiki](https://wiki.nclf.net) - MediaWiki
* Minecraft Hosting - Lapito's Galacticraft, connect to mc.nclf.net

## master.seattle.fssnow.com - Now Defunct

Self maintained and hosted VMWare ESXi 6.7 server running on custom 
built server hardware circa 2012.  Slated for decommissioning as its
duties are migrated to cloud hosts and the old Xenon V3 is losing
VMWare support.

* Web Server - nginx mainline with PHP7.x and MariaDB
* VMWare ESXi
* General Purpose Game Server - Hosting mainly 7 Days to Die, Terraria, and Starbound

## pi.seattle.fssnow.com

An always on Raspberry Pi 3b

* VPN - OpenVPN utilizing strong RSA key exchanges
* Unifi Controller - Controller for the local Ubiquity Unifi deployment

## moon13.renton.fssnow.com

An always on Raspberry Pi 3b+

* VPN - OpenVPN utilizing strong RSA key echanges
* Unifi Controller - Controller for the local Ubiquity Unifi deployment
* Pi-Hole - DNS server for the local network

## deep13.renton.fssnow.com

An always on Raspberry Pi 3b

* Pi-Hole - Redundant DNS server for the local network
* ADSB Receiver - Sending airplane tracking data to FlightRadar24 and FlightAware
