---
author: "linux, bash"
title: "Unattended Upgrades"
description: "A simple bash script to automate updates using popular package managers such as apt, dnf, pacman, pip, etc."
tags: ["bash", "linux", "tui", "whiptail"]
categories: ["bash", "linux", "tui", "whiptail"]
ShowToc: true
TocOpen: true
---
# Unattended-upgrades 

|  |  |
| --- | --- |
![image](https://user-images.githubusercontent.com/83690012/228487734-3b08913c-bee2-48e8-a7d4-594659b8be87.png) | ![image](https://user-images.githubusercontent.com/83690012/228489221-5f9d52b3-8ef9-4535-b4ac-89de4f576e79.png)
# Why
A lightweight alternative to the popular unattended upgrades, made after it was consuming a lot of resources on my low power devices. It brings support for more than just apt, and works by just adding the non-interactive update commands to cron. 

Currently, it uses the @daily and @weekly time periods set by your distro, if using alternative times such as every 2 days or 3 days, it's set to 6pm. i plan to somehow add functionality to make cron do missed tasks if the device wasn't on at the time, maybe via anacron.

# How to Run
1) `git clone https://github.com/t3dium/unattended-upgrades.git`
2) `cd unattended-upgrades`
3) `sudo bash setup.sh`

# Todo

- [x] TUI, text based terminal GUI
- [x] Adding support for snaps, flatpaks, pip, and other package managers. (Optional)
- [x] Schedule system cleanups and docker prunes (Optional)

Currently Supported Package Managers  

- [x] Pacman (arch based)
- [x] Apt (debian/ubuntu based)
- [x] DNF (fedora based), option to set seperate times for security and normal os updates.
- [x] Pip
- [x] Flatpak
- [x] Snap
- [x] Ruby
- [ ] Docker 

-------------------|
Pacman (Arch)      |
Apt (debian/ubuntu)|
Pip                |
Flatpak            |
Snap               |
Ruby|
Docker (coming soon)



[Repo](https://github.com/t3dium/unattended-upgrades)

