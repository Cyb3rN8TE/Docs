# Mod

## Introduction

This section will guide you step by step through the process of turning your PlayStation 1 into a modded console. I've written this guide for people who have a basic level of technological understanding. If you're comfortable navigating menus, finding system information, or using Google for smaller details, you should have no trouble following along.

However, if you're not familiar with basic tech concepts, modding your PlayStation 1 might not be the best choice. If something goes wrong, troubleshooting without this foundational knowledge could be frustrating. Having a basic understanding of how your console works will not only make the process smoother but also help you effectively search for solutions when issues arise. Understanding the fundamentals will set you up for success and ensure you enjoy the modding experience.

{% hint style="info" %}
This guide is written in a step-by-step format, so make sure to follow each step carefully and in order.
{% endhint %}

{% hint style="info" %}
This guide assumes you already have a modded PlayStation 2 running FreeMcBoot, are familiar with navigating the file system using LaunchElf, and know how to use homebrew applications such as Memory Card Annihilator. If you're unsure about anything, Google is your friend, and there are plenty of great YouTube videos that cover the basics.
{% endhint %}

{% hint style="warning" %}
I don't recommend performing mods on your main console, as several steps in the guide could overwrite existing data or reset your settings. I only suggest using your main console if you're 100% confident that everything has been properly backed up. There are plenty of consoles available on the used market, such as on Facebook Marketplace or eBay, so I recommend picking up a cheap console to mod while keeping your main console stock with all your original saves, settings, etc., intact.
{% endhint %}

## Goals

* Play Sony PlayStation 1 Game Backups via CD-R.

{% hint style="info" %}
Backups refer to file-level copies of games that you have lawfully purchased and already own, either digitally or on physical media such as a CD, DVD, floppy disk, cartridge, etc.
{% endhint %}

{% hint style="warning" %}
It is both illegal and unethical to pirate or obtain games that you have not purchased or do not own a legitimate physical or digital copy of. This guide is intended solely to help you modify your console so you can back up and play games you already own. I do not endorse or support any form of software piracy.

By following this guide, you assume full responsibility for your actions. I will not be held liable for any legal issues or consequences that may arise should you choose to engage in piracy or any other illegal activity. Always respect copyright laws and the intellectual property of game developers.
{% endhint %}

## Console

Sony PlayStation 1

{% hint style="info" %}
All fat and slim models are supported except SCPH-3000.
{% endhint %}

## Equipment

You will need:

* 2 x Genuine Sony PS1 Memory Card 1mb (SCPH 1020).
* Computer
* PlayStation 2 with Memory Card Annihilator and wLaunchELF installed.
* Verbatim CD-R 700MB
* External Slim USB DVDRW Burner, I suggest LG GP60NB50.
* USB flash drive formatted to FAT32.

## Homebrew

### FreePSXBoot Setup

1. Identify your console model.

{% hint style="info" %}
You can find out which model you have by looking at the official Sony label at the bottom of your PlayStation. In the top-right hand corner of the label, there should be a "Model No." followed by a code starting with "SCPH-" and ending with four numbers. These four numbers are your model number.
{% endhint %}

1. Click [here ](https://github.com/brad-lin/FreePSXBoot)to visit the FreePSXBoot GitHub Repository.
2. Scroll down to **Downloads** and select the **Download Link Slot 2** that matches your **console model**.
3. Insert your blank USB flash drive formatted to FAT32.
4. Copy the **freepsxboot-unirom-fastload-slot2.mcd** file to the root of your USB flash drive.
5. Click [here ](https://www.psx-place.com/resources/memory-card-annihilator-coded-by-ffgriever-gfx-by-berion.673/download?version=2165)to download Memory Card Annihilator.
6. Extract the archive to a folder.
7. Copy the folder to the root of your USB flash drive.
8. Insert your USB flash drive and memory cards into your PS2, making sure to match the following:

<table><thead><tr><th width="193">Port</th><th width="131">Console Path</th><th>Hardware</th></tr></thead><tbody><tr><td>Left USB Port</td><td>mass0:/</td><td>USB flash drive</td></tr><tr><td>Left MC Port</td><td>mc0:/</td><td> PlayStation 2 FMCB Memory Card</td></tr><tr><td>Right MC Port</td><td>mc1:/</td><td>PlayStation 1 Memory Card</td></tr></tbody></table>

6. Power on your PS2.
7. Run **LaunchElf**.
8. Locate the .elf file for Memory Card Annihilator and launch it.
9. Wait for Memory Card Annihilator to load.
10. Select **Slot 2** and press the X button on your controller.

<figure><img src="../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

11. Select **Restore MC Image** and press the X button on your controller.

<figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

12. Select **mass0:/** and press the X button on your controller

<figure><img src="../../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

13. Press the R2 button on your controller to show all files, then select the FreePSXBoot .MCD file and press the A button on your controller.

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

14. Select **Yes** and press the X button on your controller to begin the process.

<figure><img src="../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

15. Once the process has completed, you can power off your PS2 and remove your PS1 memory card.

### FreePSXBoot Testing

1. Insert your PS1 memory card (with FreePSXBoot installed) into memory card slot 1 (right side port) on your PS1 console.
2. Insert your PS1 memory card (blank) into memory card slot 0 (left side port) on your PS1 console.
3. Make sure that there is no disc in the console.
4. Power on your console.
5. Select **MEMORY CARD** and press X on your controller.
6. Wait for UNIROM to load.

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

7. Press the start button on your controller.

<figure><img src="../../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

8. Power off your console.

### FreePSXBoot Usage

Now that we've tested that UNIROM successfully loads, I'll run you through the process for playing a game.

#### Hardware Configuration

* FreePSXBoot PS1 Memory Card is inserted into memory card slot 1 (right side port) on your PS1 console.
* PS1 Memory Card containing your game saves is inserted into memory card slot 0 (left side port) on your PS1 console.
* Make sure that there is no disc in the console.

#### Playing a game

1. Power on your console.
2. Select **MEMORY CARD** and press X on your controller.
3. Wait for UNIROM to load.

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

4. Press the start button on your controller.

<figure><img src="../../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

5. Select **Boot CD** and press the X button on your controller.

<figure><img src="../../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

6. Insert your game backup CD-ROM into the console's disc tray and close the lid.
7. Select **Play** and then press the X button on your controller.

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

8. Your game of choice should now load - happy gaming!

## Games

{% hint style="info" %}
PlayStation 1 game backups must be in **bin/cue** format.
{% endhint %}

### Preparation

1. Download [Iso2God](https://github.com/r4dius/Iso2God/releases/download/1.3.7/iso2god-v1.3.7.zip).
2. Launch Iso2God.
3. Add your Xbox 360 game backups in .iso format.
4. Make sure the padding settings match below.

### Burning Game Backup Discs

## Credits

Below are some of the key individuals and teams who deserve special recognition for their efforts in making tools, mods, and resources available to the Xbox 360 community.

| Product | Creator |
| ------- | ------- |
|         |         |
|         |         |
|         |         |
