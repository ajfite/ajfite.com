---
layout: webserve
title: Web Services
permalink: /webservices/
---

I run a series of personal web services for myself, fellow students, and
interested third parties.  Also a good showcase of my personal system administration
experience.  Note that the subdomains of fssnow.com are not meant to host websites,
connecting to these with a web browser may produce unexpected results.

## fremont.linode.fssnow.com

Linode VPS running a self-maintained Arch Linux instance.

* Web Server - nginx mainline with PHP7.x and MariaDB (where this site is hosted)
* [Git and Build Server](https://git.nclf.net) - GitLab, GitLab CI replacing jenkins
* [Wiki](https://wiki.nclf.net) - MediaWiki
* Forum - PHPBB3 based forum - Work In Progress
* Minecraft Hosting - Lapito's Galacticraft, connect to mc.nclf.net

## master.seattle.fssnow.com

Self maintained and hosted VMWare ESXi 6.7 server running on custom 
built server hardware circa 2012.  Slated for decommissioning as its
duties are migrated to cloud hosts and the old Xenon V3 is losing
VMWare support.

* Web Server - nginx mainline with PHP7.x and MariaDB
* VMWare ESXi
* General Purpose Game Server - Hosting mainly 7 Days to Die, Terraria, and Starbound

## pi.seattle.fssnow.com

An always on Raspberry Pi 3

* VPN - OpenVPN utilizing strong RSA key exchanges
* Unifi Controller - Controller for a Ubiquity Unifi deployment

## pi.sanluisobispo.fssnow.com

An always on Raspberry Pi 3, presently out of service pending a new home.
