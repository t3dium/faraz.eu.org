---
author: "linux, bash"
title: "Systemd sandboxing templates"
description: "Systemd sandboxing templates for popular services"
tags: ["bash", "security", "linux"]
categories: ["bash", "security", "linux"]
ShowToc: true
TocOpen: true
featured: true
---

## Installation
Simply copy the `*.service.d` files to `/etc/systemd/system/`.

## Services covered
* Network Manager
* Bluetooth
* DictD
* Dovecot
* Fail2ban
* Haveged
* iwd
* Nginx
* Nitter
* Opendkim
* Openrgb
* Cups
* Pkgstats
* Postfix
* PostGrey
* Radicale
* Redis
* Sshd
* Systemd-logind
* Systemd-networkd
* USBguard

Credit goes to [krathalan](https://github.com/krathalan/systemd-sandboxing) for making the original repo, my fork adds openrgb support as well.

[Repo](https://github.com/t3dium/systemd-sandboxing)
