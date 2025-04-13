# Installing The Future Servers Operating System
### NOTICE: This .MD file ONLY covers the instalacion process.

Table of Content:
- Requirements
- Choosing the right OS
- Why Linux?
- Choose the right Distro
- Installing the ISO Image
- Installing Balena Etcher
- Flashing the ISO to a USB Thumbdrive
  -(Alternativley) Network Flash
- Booting into the USB
- Instalacion
- Oh Noes! Big Scary Terminal!
- Conclusion

## Requirements

Now, to make a project, you obviously need resources that you will use to create said project.
But some people might not want to buy a full blown computer, and try to re-use that old PC thats clogging up space in the closet or basement.
And thats fine! In fact, I actually highly recomend that you do this to get atleast familiar with home servers, and get that nice feeling
that you actually did something about that previously considered E-Waste. And hey! you probably paid good money back in the day,
so why not repurpose it? If you use a Work stacion or a laptop often or just for work, most requirements you might allready have.
### Needed
- Old PC or a PC in General
- Another PC to flash the ISO Image and to remotely controll old PC
- Keyboard that uses USB
- Monitor
- A USB Thumbdrive with ATLEAST 8 GB of storage.
- An Ethernet Cable
- And a place to put the PC thats relativly close or right next to your modem or router.
- alot of Patience

## Choosing the right OS

Now, if you use a work stacion or a laptop daily, then you have to atleast heard or used Windows on said devices,
As Windows comes with many laptops or mini PC preinstalled from the factory. Now, if you use Apple Devices, such as the Macbook Air, IPhone, or IWatch,
you will atleast be familiar with MacOS for MacBooks, IOS for Iphones, and whatever runs on the IWatch. Both Windows and MacOS are operating systems designed to work
on said hardware. but did you know that there is actually a third Operating system, mostly overshadowed until recently? Linux!

## Why Linux?

Linux is a UNIX based operating system like MacOS, and Dominates the charts when it comes to how many servers use it. It is 
highly customizable, and comes with a vast community developing Open Source software for it. As per this tutorial, we shall be 
using Linux for the OS of the device. Now, dont worry, a whole other operaing system does sound a little scary for you new users 
out there. but ill try to be as helpfull as can be to explain the process to you. In this tutorial, we shall be using a server 
instalacion, designed specifically for servers and service providers.

## Choosing the Right Distro

### NOTE: Now, by no means am I and expert in the subject of Linux, so keep that in mind, and im only talking from my perspective.

Distro, meaning Distribution, is actually one of the best parts of Linux. Linux, in itself, is an OS, but the vast community
have developed different versions that are tailored to the exact needs of the user, these alternet versions are what we call
distributions. Now, the most recognizable Distro that comes to mind when you think about Linux, is probably going to be Ubuntu,
as it has its own vast community supporting it, and forks of it that support different desktop enviorments. As per this turorial,
we shall be using Ubuntu Server, designed for what we will be doing today.

## Installing the ISO Image

### If you wish to do the Network Flashing, please skip to the next subject.

Something that we will be needing, is the ISO Image of the operating system. You can download the most recent ISO Image from their
webpage.
### WARNING: the following link, once clicked will download the most recent Ubuntu Server ISO, If you wish to go to the website and download it yourself, please verify that it is coming from the actual Ubuntu Webpage, as other ISO's from other sights may  potentially harbor malware.

Download Link:
    https://ubuntu.com/download/server/thank-you?version=24.10&architecture=amd64

## Installing Balena Etcher

Once your ISO Image is done installing, we will need a tool called Balena Etcher, this will allow us to flash the ISO to a Spare USB.
### Warning, the following link will take you to the oficial balena etcher site, if you wish to look up the webpage yourself, please confirm is is coming from the official balena etcher site.

Oficial Balena Etcher Site:
    https://etcher.balena.io/#download-etcher
    
