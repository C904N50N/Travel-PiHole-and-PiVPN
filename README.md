# 🌐 Travel-PiHole-and-PiVPN 🌐

This is my journey of setting up a RaspberryPi and a Travel Router with PiHole and PiVPN.

## 🚀 Motivation

When I first stumbled upon this project online, I was immediately captivated. The only missing piece was a travel-sized wireless router. I already had a few Raspberry Pis gathering dust. As I delved deeper into the world of data privacy, I realized how pervasive data selling and public wifi vulnerabilities were. This sparked an idea for an upcoming trip - I wanted to ensure my data and personal information were secure while working on my computer.

## 🛠️ Equipment

I began by gathering all the necessary equipment for this project:

- 🖥️ Raspberry Pi 4s or Pi Zero W V2 -
- 📶 Linksys A750 Travel Router -
- 🔌 USB C power hubs or cables
- 🌐 Access to the Internet
- 📱 Micro USB cable or Charger

## 📋 Pre-Setup

The setup process began with installing the non-desktop version of the latest RaspberryPi OS onto the Pi. Following that, PiHole was installed on one device and PiVPN on the other.

When setting up the router for the most part it will come pre configured from the factory, I suggest changing the password and SSID to be more recognizable to you.

After the router is set up and running we can start setting up PiHole and/or PiVPN now that we IPs that we can make static.

## PiHole

To set up PiHole, all we need to do is run this command:

_Insert Command Here_

Then the installer will run through the setup.
During the setup make sure to set a static IP on the router for the RaspberryPi.
Once it has finsihed setting up, In the routers DHCP settings you need to set the DNS Server to to the RaspberryPis IP address you set earlier.
After this the network should accessible and should be blocking ads.
From here you can add more blocklists and configure other settings to your likings.
Of course from here you can set up Unbound to act as a private DNS Server to increase your privacy even more.

## PiVPN
