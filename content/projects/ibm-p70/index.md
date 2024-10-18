---
title: IBM PS/2 Model P70 Restoration
seo_title: IBM PS/2 Model P70 Restoration
summary: Repair, archiving, and modernizing an IBM PS/2 Model P70 Luggable computer
description: Repair, archiving, and modernizing an IBM PS/2 Model P70 Luggable computer
slug: ibm-ps2-p70
author: AJ Fite

draft: false
date: 2023
lastmod: 2023-09-19
expiryDate: 
publishDate: 

feature_image: 
feature_image_alt: 

project types: 
    - Personal

techstack:
    - Hardware
---

This is a work in progress, pictures coming at some point!

## Repair

8/18/2023 - The floppy drive does not read/seek and the machine has a dead CMOS battery.  These old PS/2s require a "reference diskette" to serve as BIOS configurator so the machine presently doesn't boot.  I am waiting on parts to swap in a GoTek, I'll look into repairing the drive as well once I'm sure the computer is otherwise in working shape.

## Modernization

I've outfitted the machine with a new to me IBM SCSI card part number 84F8015.  I haven't found reference to that part number online anywhere.  It came with a 3.5" option diskette that I haven't found online, [I have archived it here](IBMOptionDisk84F8015.img).

In order to get away from the ancient spinning drive (which I'm not yet sure works) I'm using a [ZuluSCSI](https://zuluscsi.com/) in conjunction with the above card to allow a MicroSD to stand in for the hard drive (and other devices).  If I had known about it at the time I may have instead chosen this modern MCA SCSI reproduction, the [McIDE](https://zzxio.com/product/mcide/).  Its possible I will revisit the McIDE in the future since the SCSI card while more period accurate is more cumbersome.

# Thanks and Sources

Lots of help on this project has come from [ardent-tool.com](https://ardent-tool.com/), an invaluable source on the IBM PS/2.