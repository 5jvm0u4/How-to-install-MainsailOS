# How-to-install-MainsailOS-on-RPI
A guide documenting the processes of installing MainsailOS on a Raspberry Pi, written for internal use but made public.
## Introduction
Mainsail is a web interface (front end) for klipper, that connects to klipper via an API called moonraker.

[MainsailOS](https://github.com/mainsail-crew/MainsailOS) is a pre-configured image for SBC(Single Board Computer) that include everything mentioned above plus a lot more.

One could install everything by it's own on a linux system, and connect everything togather, or thay could just install MainsailOS and everything is set.

For a SBC, the latter is recommended. Credit to the [Mainsail-Crew](https://github.com/mainsail-crew)

### Reference: 
https://docs.vorondesign.com/build/software/installing_mainsail.html

https://docs.mainsail.xyz/setup/getting-started
## Setup

### For this guide you'll need the following: ###

 - Raspberry Pi 2/3/4/5 model B
 - SanDisk Extreme PRO microSDXC 32~256GB
 - MicroSD reader
 - 5V3A USB Type-C power supply
 - Internet conncetion for both your computer and the RPI, RPI 4/5B only support up to IEEE 802.11ac

### For connecting via USB to slave controllers, you'll need the following: ###

 - Slave controller of choice.
 - Slave controller's manual.
 - High quality USB Type-A to Type-C cable.

## Install MainsailOS
First, open this link: https://docs.mainsail.xyz/setup/getting-started

Choose this:  
<img width="600" alt="image" src="https://github.com/user-attachments/assets/f5a2c21c-041f-454d-9899-390fdde84bc5" />

Then this:  
<img width="600" alt="image" src="https://github.com/user-attachments/assets/5189bdbb-8069-4281-9193-969e8acf4082" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/8ffdd9bf-8976-48bc-b2ea-825889250c59" />  


Follow the page but stop before "Select Settings", that select setting guide is out-of-date, follow this instead:  
Choose this:  
<img width="600" alt="image" src="https://github.com/user-attachments/assets/25511a0b-dc39-4ede-ace8-ab01de29ac9a" />

Set the password, leave the host name and username as is unless you know what you're doing, also configure WiFi here.  
Region code for Taiwan is TW(ISO 3166-2:TW).  
<img width="400" alt="image" src="https://github.com/user-attachments/assets/7852f8d6-723f-4f69-9db3-b0a1acb7d03a" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/1522aa5f-7906-4d30-9101-742ab6302a6a" />

Save and click Yes  
<img width="600" alt="image" src="https://github.com/user-attachments/assets/b6e0784e-eaab-47fb-a36d-1eb3e3cdd3d6" />


After finishing, remove the SD card from your computer and plug it into your RPI, continue to the "First boot" section and follow it for the rest.  
Notice sometimes only accessing via IPv4 address will work consistantly, and also, Mainsail is unprotected, never open it to WAN unless you know what you're doing.  
<img width="600" alt="image" src="https://github.com/user-attachments/assets/7286a54b-02eb-47b0-b29e-b2262fd97dd7" />

After finishing "First boot" section, move to How to flash klipper to BigTreeTech Octopus V1.0 for further instructions.








