# Mod

## Introduction

This section will guide you step by step through the process of turning your Nintendo Wii into a modded console. While this guide covers each step in a decent amount of detail, some parts that involve simple tasks—like locating your Wii’s date and time settings or finding the version number—are not elaborated on as they are straightforward. I've written this guide for people who have a basic level of technological understanding. If you’re comfortable navigating menus and logically know where things might be found, or if you don’t mind a quick Google search for more minor details, you'll be just fine.

However, if you don’t have a solid grasp of basic tech concepts, modding your Wii may not be the best option. If something goes wrong or needs attention, troubleshooting without a basic understanding could be frustrating. Having some foundational knowledge will not only make the process smoother but also help you effectively search for solutions when issues arise. Understanding the basics will set you up for success and ensure you enjoy the experience.

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
2. Launch `NUS Downloader.exe`
3. Database > IOS > IOS38 > v4123

