# PortalFetch 🍰

> *"I'm making a note here: HUGE SUCCESS."*

PortalFetch is a custom bash wrapper for fastfetch that mirrors the Aperture Science terminal from the end credits of Portal 1. 

Unlike standard fastfetch configs that break ASCII borders when system information changes length, this calculates and locks the grid in place to make sure it stays in the boxes. 

![PortalFetch Screenshot](portalfetchss.png) 

## Features
* **Pixel-Perfect Layout:** Replicates the exact dual-pane structure of the Portal end credits.
* **Unbreakable Borders:** Uses a custom rendering script so dynamic data (like changing RAM or Uptime) never misaligns the ASCII walls.
* **Randomized Quotes:** Features a built in database of quotes from classic games (Portal, Half-Life, Halo) and tech figures. Pulls a new quote every time you run it.
* **Powered by Fastfetch:** Fast, lightweight, and uses your existing Fastfetch backend to grab accurate system stats.

## Prerequisites
You must have fastfetch installed on your system before running this. 
See: https://github.com/fastfetch-cli/fastfetch on how to install it on your system

## Installation

Clone the repository and run the install script:

```bash
git clone https://github.com/linuxgen/portalfetch.git
cd portalfetch
chmod +x install.sh
./install.sh


