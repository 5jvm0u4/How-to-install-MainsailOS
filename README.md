# How-to-install-MainsailOS
A guide documenting the processes of installing MainsailOS on a Raspberry Pi, written for internal use but made public.
## Introduction
Mainsail is a web interface (front end) for klipper, that connects to klipper with an API called moonraker.

[MainsailOS](https://github.com/mainsail-crew/MainsailOS) is a pre-configured image for SBC(Single Board Computer) that include everything mentioned above plus a lot more.

One could install everything by it's own on a linux system, and connect everything togather, or thay could just install MainsailOS and everything is set.

For a SBC, the latter is recommended. Credit to the [Mainsail-Crew](https://github.com/mainsail-crew)

### Reference: 
https://docs.vorondesign.com/build/software/installing_mainsail.html

https://docs.mainsail.xyz/setup/getting-started
## Setup

For this guide you'll need the following:

 - Raspberry Pi 2/3/4/5 model B
 - SanDisk Extreme PRO microSDXC 64GB
 - MicroSD reader
 - 5V3A USB Type-C power supply
 - Internet conncetion for both your computer and the RPI, RPI 3/4/5B only support up to IEEE 802.11ac

For connecting via USB to slave controllers, you'll need the following:

 - Slave controller of choice.
 - Slave controller's manual.
 - High quality USB Type-A to Type-C cable.
