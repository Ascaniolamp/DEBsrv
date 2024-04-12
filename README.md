# DEBsrv
A set of scripts, configurations and utilities to operate a basic home server.

Turn an old debian-running laptop into a mobile server by uploading the DEBsrv utilities pack on your machine!

## Requirements
- Docker
- Apache2
- Cockpit
- Samba

## Setup instructions
Every folder inside the repo corresponds to a root folder inside the linux filesystem.
For example, files in the repo's `etc` folder must be moved into linux's `/etc` folder.

The configuration files are placed in the `etc` folder, we reccomend you change these, based on your preferences and necessities.

The `usr` directory contains CLI scripts to facilitate tasks such as turning off the laptop's display, restarting every 

The `srv` folder contains a `docker` directory in which docker compose files are located, and a `www` directory containing the apache2 webpage.
