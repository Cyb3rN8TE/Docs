# Mod

## Introduction

This section will guide you step by step through the process of turning your Nintendo Wii into a modded console. While this guide covers each step in a decent amount of detail, some parts that involve simple tasks—like locating your Wii’s date and time settings or finding the version number—are not elaborated on as they are straightforward. I've written this guide for people who have a basic level of technological understanding. If you’re comfortable navigating menus and logically know where things might be found, or if you don’t mind a quick Google search for more minor details, you'll be just fine.

However, if you don’t have a solid grasp of basic tech concepts, modding your Wii may not be the best option. If something goes wrong or needs attention, troubleshooting without a basic understanding could be frustrating. Having some foundational knowledge will not only make the process smoother but also help you effectively search for solutions when issues arise. Understanding the basics will set you up for success and ensure you enjoy the experience.

{% hint style="info" %}
This guide is written in a step-by-step format, so make sure to follow each step carefully and in order.
{% endhint %}

## Goals

* Play Nintendo Wii and Nintendo GameCube backups from an external HDD and/or SD Card.
* Play and emulate games from over 50 retro consoles, including handhelds and arcade machines, directly from an external HDD or SD card.

{% hint style="info" %}
Backups refer to file-level copies of games that you have lawfully purchased and already own, either digitally or on physical media such as a CD, DVD, floppy disk, cartridge, etc.
{% endhint %}

{% hint style="warning" %}
It is both illegal and unethical to pirate or obtain games that you have not purchased or do not own a legitimate physical or digital copy of. This guide is intended solely to help you modify your console so you can back up and play games you already own. I do not endorse or support any form of software piracy.

By following this guide, you assume full responsibility for your actions. I will not be held liable for any legal issues or consequences that may arise should you choose to engage in piracy or any other illegal activity. Always respect copyright laws and the intellectual property of game developers.
{% endhint %}

## Equipment

You will need:

* Nintendo Wii.
* 2TB External Hard Drive (preferably with external power).
* SanDisk Ultra 256GB SDHC SDXC UHS-I Memory Card.

## Prerequisites

1. Set the correct date and time in the consoles settings.
2. Connect your console to the Internet.
3. Update your console to the latest version (if it isn't already).
4. Make note of your Wii's version. It will be 4.3U, 4.3E, 4.3J or 4.3K depending on your consoles region.
5. Make note of your console's MAC Address.

## SD Card Preparation

### Format SD Card

1. Format the SD Card to Fat32 file system.

### LetterBomb

1. Visit [HackMii](https://please.hackmii.com/) website.
2. Select the System Menu Version that matches your console.
3. Enter your consoles MAC Address.
4. Tick 'Bundle the HackMii Installer for me!'.
5. Click 'Cut the red wire' or 'Cut the blue wire' (they both just download the files).
6. Extract ZIP to folder.
7. Copy the 'private' folder and 'boot.elf' to the root of  your SD Card.

### cIOS

1. Download [cIOS installer](https://wii.hacks.guide/assets/files/d2x-cios-installer.zip).
2. Extract ZIP to folder.
3. Copy the 'apps' folder to the root of your SD Card.

### Homebrew Browser

1. Download [Homebrew Browser](https://hbb1.oscwii.org/api/contents/homebrew\_browser/homebrew\_browser.zip).
2. Extract ZIP to folder.
3. Copy the 'homebrew\_browser' folder (containing .dol file) to the 'apps' folder on your SD Card.

### Priiloader

1. Download [Priiloader](https://oscwii.org/library/app/priiloader) installer.
2. Extract ZIP to folder.
3. Copy the 'priiloader' folder (containing .dol file) to the 'apps' folder on your SD Card.

### NUS Downloader

1. Download [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest/download/NUSD-Mod-NUS-Fix.zip).
2. Launch 'NUS Downloader.exe'.

#### IOS Packages

For each IOS package in the table below:

| Location       | IOS   | Version |
| -------------- | ----- | ------- |
| Database > IOS | IOS38 | v4123   |
| Database > IOS | IOS56 | v5661   |
| Database > IOS | IOS57 | v5918   |
| Database > IOS | IOS58 | v6175   |

1. Make sure 'Pack WAD' is ticked.
2. Click 'Start NUS Download'.
3. Once the download has complete, click the bin icon.

#### WADs

1. Close the NUS Downloader program, we're done with this.
2. In the NUS Downloader directory, open the 'titles' folder.
3. Copy all files ending in .wad to the root of your SD Card.

## Installing to Wii

### LetterBomb

1. Insert the SD Card into the Wii.
2. Turn on your console.
3. Click Wii Message Board.
4. Open the calendar view and click the day which shows a yellow letter.
5. Hover over the red letter and press Ⓐ to start the process.

### HackMii Installer

1. Press Ⓐ on your controller.
2. Select 'Install The Homebrew Channel' and press Ⓐ on your controller.
3. Select 'Yes, continue' and press Ⓐ on your controller.
4. Wait for the installation to complete.
5. Once the installation is complete, select 'Continue' and press Ⓐ on your controller.
6. Select 'BootMii...'
7. If possible, select 'Install BootMii as boot2' and press Ⓐ on your controller. Don't worry if you can't, move on to the next step. For any prompts, select 'Yes, continue' and press Ⓐ on your controller.
8. Select 'Install BootMii as IOS' and press Ⓐ on your controller. For any prompts, select 'Yes, continue' and press Ⓐ on your controller.
9. Select 'Exit' and press Ⓐ on your controller.

### Priiloader

1. Hover over 'Priiloader Installer' and press Ⓐ on your controller.
2. Hover over 'Load' and press Ⓐ on your controller.
3. Press Ⓐ  or + on your controller and wait for the install to complete, then press Ⓐ  to continue.
4. Turn off your console.
5. Whilst holding down the 'reset' button on the front of your Wii, press the power button once and continue holding the 'reset' button until you see Priiloader main menu.
6. Select 'System Menu Hacks' and press Ⓐ on your controller.
7. Enable the following features by selecting each and pressing Ⓐ on your controller to toggle enabled/disabled.

| Feature                       | Status  |
| ----------------------------- | ------- |
| Block Disc Updates            | Enabled |
| Block Online Updates          | Enabled |
| Region Free EVERYTHING        | Enabled |
| Auto-Press A at Health Screen | Enabled |

8. Scroll down and select 'Save Settings', press Ⓐ on your controller.
9. On the Priiloader main menu, select 'Homebrew Channel' and press Ⓐ on your controller.

### BootMii

1. From the Homebrew Channel menu, press the home button on your controller.
2. Select 'Launch BootMii' and press Ⓐ on your controller.
3. From the BootMii main menu, press the power button on your console several times until the gears tile is selected, then press the reset button on your console.

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

4. Press the power button on your console several times until the backup NAND option is selected, then press the reset button on your console.

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

5. Wait for the backup process to complete. This process makes a NAND dump to your SD card which can be used to restore the console to stock should your console become bricked or you decide that you prefer a stock console.
6. Once the process is complete you should see the following message, press the reset button on your console to continue.

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
