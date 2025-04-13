# Installing the Future Server's Operating System

### ⚠️ NOTICE: This `.md` file ONLY covers the installation process.

## Table of Contents
- Requirements  
- Choosing the Right OS  
- Why Linux?  
- Choosing the Right Distro  
- Downloading the ISO Image  
- Installing Balena Etcher  
- Flashing the ISO to a USB Thumb Drive  
- Booting into the USB  
- Installation  
- Oh Noes! Big Scary Terminal!  
- Conclusion  

---

## Requirements

To build a project, you obviously need resources. But not everyone wants to buy a brand-new computer—many prefer to repurpose an old PC collecting dust in the closet or basement. And that’s a great idea! In fact, I highly recommend it. It’s a great way to get familiar with home servers and breathe new life into what might otherwise be considered e-waste. Plus, you probably paid good money for that machine back in the day—why not repurpose it?

If you already use a workstation or laptop for everyday tasks, you might have most of the needed tools on hand.

### What You’ll Need:
- An old PC or just a PC in general  
- Another computer to flash the ISO image and remotely control the old PC  
- A USB keyboard  
- A monitor  
- A USB thumb drive with **at least 8 GB** of storage  
- An Ethernet cable  
- A place for your PC that’s relatively close to your modem or router  
- **A lot** of patience 

---

## Choosing the Right OS

If you’ve used a workstation or laptop before, you’ve likely encountered Windows, since it comes pre-installed on many devices. If you’re an Apple user, you're probably familiar with macOS (for MacBooks), iOS (for iPhones), and whatever Apple’s calling the OS for the Apple Watch nowadays.

But did you know there’s a third major operating system? One that’s been quietly powering the internet and servers around the world: **Linux**.

---

## Why Linux?

Linux is a UNIX-based operating system like macOS. It's incredibly popular in the server world and offers a high level of customization. Thanks to its massive open-source community, Linux supports a wide range of software and configurations.

For this tutorial, we’ll be installing a Linux-based operating system specifically designed for servers. Don’t worry if you’re new—I'll guide you through the process as clearly as possible.

---

## Choosing the Right Distro

> ⚠️ NOTE: I'm not an expert in Linux—just someone sharing my experience. Take my advice with a grain of salt and do your own research, too!

"Distro" stands for "distribution"—a version of Linux tailored to different needs. This flexibility is one of Linux's best features. There are many different distros out there, each with its own focus, user interface, and level of complexity.

The most well-known distro is probably **Ubuntu**, which has a large support community and many variations (or “forks”) that cater to different use cases.

For our purposes, we’ll be using **Ubuntu Server**, a version of Ubuntu specifically designed for server environments.

---

## Downloading the ISO Image

We’ll need the official ISO image for Ubuntu Server. You can download the latest version directly from their website:

> ⚠️ WARNING: The link below will automatically begin the ISO download. If you prefer to visit the website manually, make sure you’re on the **official Ubuntu website** to avoid downloading malicious software.

[Download Ubuntu Server ISO](https://ubuntu.com/download/server/thank-you?version=24.10&architecture=amd64)

---

## Installing Balena Etcher

Next, you’ll need a tool called **Balena Etcher**, which allows you to "flash" the ISO image onto a USB drive.

> ⚠️ WARNING: The link below leads to the official Balena Etcher site. If you’d rather search for it yourself, make sure the URL matches the official domain.

[Visit Balena Etcher](https://etcher.balena.io/#download-etcher)

---

## Flashing the ISO to a USB Thumb Drive

> ⚠️ NOTE: Your USB drive must have **at least 8 GB** of storage, and **everything on it will be erased**, so make sure to back up any important data.

1. Launch Balena Etcher.  
2. Select the Ubuntu Server ISO file you downloaded (usually in your Downloads folder).  
3. Insert your USB drive and choose it as the target device.  
4. ⚠️ **Be careful not to select your main hard drive!** Flashing to the wrong drive can permanently damage your system.  
5. Click "Flash" and allow any permissions or prompts that appear.  

Once it’s done, you're ready to boot from the USB!

## Booting into the USB

Now that your USB thumb drive is ready, it’s time to start setting up your future server.

### Step-by-Step:

1. **Take your future server (the old PC you’re repurposing)** and bring it near your modem or router.  
2. **Plug an Ethernet cable** from the PC directly into the router. This gives the server access to the internet and your network.  
3. **Connect the power cable** and turn on the PC.  
4. **Plug in the USB drive** that you flashed with Ubuntu Server.  
5. **Connect a monitor and a USB keyboard** to the PC so you can interact with it.  

---

### Accessing the Boot Menu

Every PC has a different method for entering the **boot menu**—this is the screen where you choose which device to boot from (like your USB drive).

When you power on the PC, you’ll need to **press a key during startup**. Common keys include:

- `F12`  
- `F10`  
- `F2`  
- `DEL`  
- `ESC`  

You’ll usually see a quick message like _“Press F12 for Boot Menu”_ when the PC first powers on. If you’re unsure, you can look up your PC’s brand and model online along with the words “boot menu key.”

Once you’re in the boot menu, **select your USB drive** and press Enter.

