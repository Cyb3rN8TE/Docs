# Mod

## Introduction

This section will guide you step by step through the process of turning your Xbox 360 into a modded console. I've written this guide for people who have a basic level of technological understanding. If you're comfortable navigating menus, finding system information, or using Google for smaller details, you should have no trouble following along.

However, if you're not familiar with basic tech concepts, modding your Xbox 360 might not be the best choice. If something goes wrong, troubleshooting without this foundational knowledge could be frustrating. Having a basic understanding of how your console works will not only make the process smoother but also help you effectively search for solutions when issues arise. Understanding the fundamentals will set you up for success and ensure you enjoy the modding experience.

{% hint style="info" %}
This guide is written in a step-by-step format, so make sure to follow each step carefully and in order.
{% endhint %}

## Goals

* Play Microsoft Xbox 360 backups from an external HDD and/or internal HDD.
* Play Microsoft Xbox backups from an external HDD and/or internal HDD.

{% hint style="info" %}
Backups refer to file-level copies of games that you have lawfully purchased and already own, either digitally or on physical media such as a CD, DVD, floppy disk, cartridge, etc.
{% endhint %}

{% hint style="warning" %}
It is both illegal and unethical to pirate or obtain games that you have not purchased or do not own a legitimate physical or digital copy of. This guide is intended solely to help you modify your console so you can back up and play games you already own. I do not endorse or support any form of software piracy.

By following this guide, you assume full responsibility for your actions. I will not be held liable for any legal issues or consequences that may arise should you choose to engage in piracy or any other illegal activity. Always respect copyright laws and the intellectual property of game developers.
{% endhint %}

## Equipment

You will need:

* Microsoft Xbox 360 Slim (Trinity)

{% hint style="info" %}
This guide is intended exclusively for the Trinity Xbox 360 Slim consoles. **Use the image below** to compare the power supply rating and **manufacture date** of your console. If the power rating matches **12V - 10.83A, 135 watts** and the manufacture date falls between **mid-2010 and early 2011**, you have a **Trinity Xbox 360 Slim**.



![](../../../.gitbook/assets/Untitled-2.jpg)
{% endhint %}

* Xbox 360 Hard Drive Disk Cover Replacement
* Seagate BarraCuda 2.5" Notebook HDD - 2TB 128MB
* 10k Ohm 0.5 Watt Metal Film Resistor
* X-Clamp Removal Tool
* Heat Shrink Tubing
* ARCTIC MX-4 Thermal Compound Paste
* Digital Microscope
* SRA Soldering Products Rosin Paste Flux #135 in a 2 oz Jar
* Seagate 2TB Expansion Portable HDD
* MG Chemicals 99.9% Isopropyl Alcohol
* MG Chemicals Lead Free No Clean Flux 1L
* Soldering Iron
* Solder
* 30AWG Kynar wire
* Raspberry Pi Pico
* Heat Gun
* Screwdriver set with T8/T10
* X-Acto Knife
* Paper Towel
* Computer

## Prerequisites

1. Update your console to the latest version.
2. Transfer your main profile to a USB drive and keep it safe. This guide won’t cover going online, and even if it did, I don’t recommend using your main profile on the console, as it may risk getting you banned.

## Teardown

Tearing down an Xbox 360 Slim can be tricky to explain in writing, so I’ve provided a link to an excellent guide by 7Heavens on the WeMod forum. Their detailed instructions and visuals will help you through the process step by step. Click [here ](https://community.wemod.com/t/how-to-open-a-xbox-360-slim/351)to visit the guide.

<figure><img src="../../../.gitbook/assets/IMG20240801121247.jpg" alt=""><figcaption></figcaption></figure>

## Preparation

### Heatsink and Processor Cleaning

Now that you have fully removed the motherboard and heatsink covering the processor, take the time to clean off the old thermal paste using a paper towel and isopropyl alcohol. Ensure it is thoroughly cleaned, as this will help the new thermal paste bond effectively. This step is crucial for the Xbox 360, as the console tends to run hot.

<figure><img src="../../../.gitbook/assets/IMG_20240103_170945.jpg" alt=""><figcaption></figcaption></figure>

### Wire and Resistor

1. Grab your 10k Ohm 0.5 Watt Metal Film Resistor and trim each leg to about 2-3 cm on each side. This will make it easier to work with during the installation.
2. Next, take 20 cm of 30AWG Kynar wire and cut it in half. We can always shorten the wires later if needed.
3. Strip a small section off each end of the Kynar wire, then dip the exposed wire ends in flux.
4. Solder one 10 cm piece of Kynar wire to one side of the resistor, and then solder the other 10 cm piece of Kynar wire to the other side.
5. Once you're confident that there are good solder joints holding each piece of wire to the resistor, cover the entire resistor and solder joints with heat shrink tubing to ensure a secure and insulated connection.

<figure><img src="../../../.gitbook/assets/IMG20240801133725.jpg" alt=""><figcaption></figcaption></figure>

### Prepare Solder Points

At this stage, we want to start preparing our solder points for the RGH 3 mod. Below is an image of a Trinity Xbox 360 Slim motherboard that highlights each of the points we will be preparing and soldering to.

<figure><img src="../../../.gitbook/assets/Xbox_360_Trinity.png" alt=""><figcaption></figcaption></figure>

#### POST

1. Clean the point with isopropyl alcohol.
2. Apply flux to the point.
3. Tin the point with solder.

#### PLL\_BYPASS

1. Clean the point with isopropyl alcohol.&#x20;
2. Using an X-Acto Knife, carefully expose the VIA.

<div align="left">

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

</div>

1. Apply flux to the point.&#x20;
2. Tin the point with solder.

SMC\_POST

1. Clean the point with isopropyl alcohol.
2. Apply flux to the point.
3. Tin the point with solder.

#### SMC\_PLL

1. Clean the point with isopropyl alcohol.
2. Apply flux to the point.
3. Tin the point with solder.

## Aurora Dashboard

## Games

### Xbox 360

### Xbox

## DLC

### Xbox 360



## Credits

Below are some of the key individuals and teams who deserve special recognition for their efforts in making tools, mods, and resources available to the Xbox 360 community.

| Product | Creator |
| ------- | ------- |
|         |         |
|         |         |
|         |         |











