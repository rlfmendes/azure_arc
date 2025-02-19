# Welcome to Junpstart Local

## Getting Started
There are two ways to get started:

> Please note all scripts referenced in this readme are meant to run directly on a Linux shell running on one of the supported distros.

### Deploying over existing supported Linux Distro
Run the install script diorectly from a terminal

`curl -sfL https://aka.ms/get-jumpstart-local | sh`

### Baremetal imaging via USB
1. Create a ISO Image using the following script:

`curl -sfL https://aka.ms/create-jumpstart-local-iso | sh`

2.  Burn the ISO to a USB stick

3. Plug the ISO image to your NUC and have fun! :)