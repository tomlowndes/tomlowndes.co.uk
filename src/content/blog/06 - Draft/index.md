---
title: "Proxmox and Homeassistant"
description: "Creating a proxmox server."
date: "12/12/2024"
---

For years now I have had Home Assistant running on a Raspberry PI 3 with great sucsess and hardly any issues, but as I have added more sensors and automations I noticed the lack of 
prosessing power was starting to take its toll, and performance and reliability was starting to show it's ugly head.

My solution was to install HA (Home assistant) on a windows pc I was using as a Plex server, Plex is a system that allows you to watch your saved media on compatible devices.(plex link). So with a coffee and a Remote connection to that pc I installed HA on a virtualbox, which was pretty streight foward, then took a few hours to pass a USB Zigbee device through to that Virtual Machince. (Remember this is not a tuturial this is the ramblings of a madman...)  

### Moving to Proxmox

A few months of Virtual machines crashing or the PC just turning off I knew a solution was needed to make this A) more steamlined, and B) more reliable. Enter Proxmox a way on spinning up virtual machines for a specific app quickly and easily. 

So with a USB stick with Proxmox i plugged it in and did a full install on my windows pc Sever and within 30mins we where done. With the IP adress i remoted into the controll panel, and followed a tuturial to install HA. It worked sucsess, and even the USB zigbee controller just works, no messing around.



### Conclusion


