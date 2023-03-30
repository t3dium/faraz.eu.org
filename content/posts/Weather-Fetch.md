---
author: "linux, bash"
title: "Weather Fetch"
description: "A simple bash script utilising the wttr.in api to create a neofetch but for weather."
tags: ["bash", "security", "linux", "tui", "whiptail"]
categories: ["bash", "security", "linux", "tui", "whiptail"]
ShowToc: true
TocOpen: true
---

![image](https://user-images.githubusercontent.com/83690012/207031953-99e67767-53af-416d-ba3c-8303440495fc.png)


## How to install

install [gum](https://github.com/charmbracelet/gum#installation)

``cd ~/Downloads && git clone https://github.com/t3dium/weather-fetch && echo "bash ~/Downloads/weather-fetch/weather-fetch.sh" >> ~/.zshrc && echo "installed and added weather fetch to your terminal startup"``

If you dont use zsh, the 2nd to last command will fail, so change it to ~/.bashrc or whatever shell is used, and re-run the command.

[Repo](https://github.com/t3dium/weather-fetch)