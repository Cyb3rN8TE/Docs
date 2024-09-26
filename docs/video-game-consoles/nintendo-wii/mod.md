# Mod

## Introduction

This section will guide you step by step through the process of turning your Nintendo Wii into a modded console. While this guide covers each step in a decent amount of detail, some parts that involve simple tasks—like locating your Wii’s date and time settings or finding the version number—are not elaborated on as they are straightforward. I've written this guide for people who have a basic level of technological understanding. If you’re comfortable navigating menus and logically know where things might be found, or if you don’t mind a quick Google search for more minor details, you'll be just fine.

However, if you don’t have a solid grasp of basic tech concepts, modding your Wii may not be the best option. If something goes wrong or needs attention, troubleshooting without a basic understanding could be frustrating. Having some foundational knowledge will not only make the process smoother but also help you effectively search for solutions when issues arise. Understanding the basics will set you up for success and ensure you enjoy the experience.

{% hint style="info" %}
This guide is written in a step-by-step format, so make sure to follow each step carefully and in order.
{% endhint %}

{% hint style="warning" %}
I don't recommend performing mods on your main console, as several steps in the guide could overwrite existing data or reset your settings. I only suggest using your main console if you're 100% confident that everything has been properly backed up. There are plenty of consoles available on the used market, such as on Facebook Marketplace or eBay, so I recommend picking up a cheap console to mod while keeping your main console stock with all your original saves, settings, etc., intact.
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

## Console

Nintendo Wii

{% hint style="info" %}
Compatible with all Nintendo Wii consoles running System Menu version 4.3
{% endhint %}

## Equipment

You will need:

* 2TB External Hard Drive (preferably with external power).
* SanDisk Ultra 256GB SDHC SDXC UHS-I Memory Card.

## Prerequisites

1. Set the correct date and time in the consoles settings.
2. Connect your console to the Internet.
3. Update your console to the latest version (if it isn't already).
4. Make note of your Wii's version. It will be 4.3U, 4.3E, 4.3J or 4.3K depending on your consoles region.
5. Make note of your console's MAC Address.

## External HDD Preparation

Format the External HDD to Fat32 file system.

## SD Card Preparation

### Format SD Card

Format the SD Card to Fat32 file system.

### LetterBomb

1. Visit [HackMii](https://please.hackmii.com/) website.
2. Select the System Menu Version that matches your console.
3. Enter your consoles MAC Address.
4. Tick **Bundle the HackMii Installer for me!**.
5. Click **Cut the red wire** or **Cut the blue wire** (they both just download the files).
6. Extract ZIP to folder.
7. Copy the **private** folder and **boot.elf** to the root of  your SD Card.

### cIOS

1. Download [cIOS installer](https://wii.hacks.guide/assets/files/d2x-cios-installer.zip).
2. Extract ZIP to folder.
3. Copy the **apps** folder to the root of your SD Card.

### Homebrew Browser

1. Download [Homebrew Browser](https://hbb1.oscwii.org/api/contents/homebrew\_browser/homebrew\_browser.zip).
2. Extract ZIP to folder.
3. Copy the **homebrew\_browser** folder (containing .dol file) to the **apps** folder on your SD Card.

### Priiloader

1. Download [Priiloader](https://oscwii.org/library/app/priiloader) installer.
2. Extract ZIP to folder.
3. Copy the **priiloader** folder (containing .dol file) to the **apps** folder on your SD Card.

### NUS Downloader

1. Download [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest/download/NUSD-Mod-NUS-Fix.zip).
2. Launch **NUS Downloader.exe**.

#### IOS Packages

For each IOS package in the table below:

| Location       | IOS   | Version |
| -------------- | ----- | ------- |
| Database > IOS | IOS38 | v4123   |
| Database > IOS | IOS56 | v5661   |
| Database > IOS | IOS57 | v5918   |
| Database > IOS | IOS58 | v6175   |

1. Make sure **Pack WAD** is ticked.
2. Click **Start NUS Download**.
3. Once the download has complete, click the bin icon.

#### WADs

1. Close the NUS Downloader program, we're done with this.
2. In the NUS Downloader directory, open the **titles** folder.
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
2. Select **Install The Homebrew Channel** and press Ⓐ on your controller.
3. Select **Yes, continue** and press Ⓐ on your controller.
4. Wait for the installation to complete.
5. Once the installation is complete, select **Continue** and press Ⓐ on your controller.
6. Select **BootMii...**
7. If possible, select **Install BootMii as boot2** and press Ⓐ on your controller. Don't worry if you can't, move on to the next step. For any prompts, select **Yes, continue** and press Ⓐ on your controller.
8. Select **Install BootMii as IOS** and press Ⓐ on your controller. For any prompts, select **Yes, continue** and press Ⓐ on your controller.
9. Select **Exit** and press Ⓐ on your controller.

### Priiloader

1. Hover over **Priiloader Installer** and press Ⓐ on your controller.
2. Hover over **Load** and press Ⓐ on your controller.
3. Press Ⓐ  or + on your controller and wait for the install to complete, then press Ⓐ  to continue.
4. Turn off your console.
5. Whilst holding down the **reset** button on the front of your Wii, press the power button once and continue holding the **reset** button until you see Priiloader main menu.
6. Select **System Menu Hacks** and press Ⓐ on your controller.
7. Enable the following features by selecting each and pressing Ⓐ on your controller to toggle enabled/disabled.

| Feature                       | Status  |
| ----------------------------- | ------- |
| Block Disc Updates            | Enabled |
| Block Online Updates          | Enabled |
| Region Free EVERYTHING        | Enabled |
| Auto-Press A at Health Screen | Enabled |

8. Scroll down and select **Save Settings**, press Ⓐ on your controller.
9. On the Priiloader main menu, select **Homebrew Channel** and press Ⓐ on your controller.

### BootMii

1. From the Homebrew Channel menu, press the home button on your controller.
2. Select **Launch BootMii** and press Ⓐ on your controller.
3. From the BootMii main menu, press the power button on your console several times until the gears tile is selected, then press the reset button on your console.

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

4. Press the power button on your console several times until the backup NAND option is selected, then press the reset button on your console.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Wait for the backup process to complete. This process makes a NAND dump to your SD card which can be used to restore the console to stock should your console become bricked or you decide that you prefer a stock console.
6. Once the process is complete you should see the following message, press the **reset** button on your console to continue.

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

7. From the BootMii menu, press the **power** button on your console several times until the back arrow tile is selected, then press the **reset** button on your console.

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

8. From the BootMii menu, press the **power** button on your console several times until the homebrew channel tile is selected, then press the **reset** button on your console.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### cIOS Installer

1. From the homebrew channel menu, hover over **d2x cIOS Installer** and press Ⓐ on your controller.
2. Hover over **Load** and press Ⓐ on your controller.

#### IOS Install No. 1

1. Using your controller, match the following settings.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Once the settings match, press Ⓐ on your controller.
5. On the slots map page press Ⓐ again on your controller.
6. Wait patiently whilst the IOS is installed. Once completed and the slots map page is showing, press Ⓐ on your controller to continue.

#### IOS Install No. 2

1. Using your controller, match the following settings.

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

2. Once the settings match, press Ⓐ on your controller.
3. On the slots map page press Ⓐ again on your controller.
4. Wait patiently whilst the IOS is installed. Once completed and the slots map page is showing, press Ⓐ on your controller to continue.

#### IOS Install No. 3

1. Using your controller, match the following settings.

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

2. Once the settings match, press Ⓐ on your controller.
3. On the slots map page press Ⓐ again on your controller.
4. Wait patiently whilst the IOS is installed. Once completed and the slots map page is showing, press Ⓐ on your controller to continue.

#### IOS Install No. 4

1. Using your controller, match the following settings.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

2. Once the settings match, press Ⓐ on your controller.
3. On the slots map page press Ⓐ again on your controller.
4. Wait patiently whilst the IOS is installed. Once completed and the slots map page is showing, press Ⓐ on your controller to continue.
5. We're now done with the IOS installations, press the Ⓑ button on your controller to exit.
6. Turn off your console and remove the SD Card.

## Post-Installation

### BootMii Autostart

We need to prevent the Wii from launching BootMii whenever the console turns on:

1. Insert your SD Card into your computer.
2. Rename the **bootmii** folder to **bootmii\_x**.

### Backup NAND Dump

As discussed earlier in the guide, we created a NAND dump of the console, which will allow us to recover from a bricked system or restore the console to its original state. This process generated two files: **keys.bin** and **nand.bin**. Copy these files from the root of your SD card and store them in a secure location. I recommend creating a folder named **Wii Backup** on your Google Drive and uploading the files there for safekeeping.

## WiiFlow Prepartion

Now that we’re ready to dive into the fun part of modding, let’s begin by gathering everything needed to install WiiFlow on your console.

Start by inserting your SD card and External HDD into your computer. Once that's done, we’re ready to begin downloading the necessary packages and transferring the files.

{% hint style="info" %}
During the process of copying files to your SD card or external HDD, if your OS prompts you with options to either replace the files or skip them, you must choose to **replace the files**.
{% endhint %}

### WiiFlow Application

WiiFlow is an application used for loading backup games from a USB device or SD card. It presents your game library in a visually appealing format, making it super easy to browse and launch your games.

1. Download [WiiFlow](https://github.com/Fledge68/WiiFlow\_Lite/releases/download/v.5.5.4\_1/wiiflow\_v5.5.4-1.zip).
2. Extract ZIP to folder.
3. Open the folder and copy the **apps** and **wiiflow** folders to the root of your SD Card.

### Some YAWMM Mod

YAWMM is used to manage **WAD files**, which are packages containing data like channels, system menus, or games.

1. Download Some [YAWMM Mod](https://github.com/FIX94/Some-YAWMM-Mod/releases/download/v1.0/some-yawmm-mod-v1.0.zip).
2. Extract ZIP to folder.
3. Locate the folder which contains the file **boot.dol** and copy the folder to the **apps** folder on your SD Card.

### WiiFlow Forwarder

A WiiFlow Forwarder is a custom channel installed on the Wii's system menu that acts as a shortcut to launch the WiiFlow application directly from the home screen. Instead of navigating through the Homebrew Channel to start WiiFlow, the forwarder allows you to access it quickly with just one click.

1. Download [WiiFlow Forwarder](https://repo.mariocube.com/WADs/Forwarders/WiiFlow%20Forwarders/Wii/Blue%20Circles-FIX94v14b-DWFA.wad).
2. Create a new folder on the root of your SD Card called **wads**.
3. Copy the Blue Circles .wad file to the **wads** folder on your SD Card.

### WiiFlow Plugins Pack

The WiiFlow Plugins Pack is a collection of plugins that expand the functionality of WiiFlow. These plugins allow WiiFlow to not only load Wii games, but also emulate and play games from various other systems such as NES, SNES, Game Boy, Sega Genesis, and more.

1. Download [WiiFlow Plugins Pack](https://www.mediafire.com/file/w8smzw3iwm041cz/WiiFlow\_Plugins\_Pack\_2024.7z/file).
2. Extract ZIP to folder.

#### SD Card

1. Locate the folder called **COPY\_TO\_SD\_OR\_USB** and copy the entire folder contents to the root of your SD Card.
2. Locate the folder called **COPY\_TO\_SD** and copy the entire folder contents to the root of your SD Card.

#### External HDD

1. Locate the folder called **COPY\_TO\_USB** and copy the entire folder contents to the root of your External HDD.
2. Create a folder called **wbfs** on the root of your SD Card.
3. Create a folder called **games** on the root of your SD Card.

### WiiFlow Emulator Database

The WiiFlow Emulator Database is a collection of information that helps WiiFlow manage and organise emulated games from various consoles. This database is used in conjunction with WiiFlow’s plugins to properly categorise, display, and launch games from different systems, such as NES, SNES, Game Boy, Sega Genesis, and more.

1. Download [WiiFlow Emulator Database](https://www.mediafire.com/file/4blrpsqqn5g0bdu/Wiiflow\_Database.7z/file), [WiiFlow Snapshots](https://www.mediafire.com/file/3k3geemnnx06049/Wiiflow\_Snapshots\_MOD.7z/file) and [WiiFlow CartDisk](https://www.mediafire.com/file/xegmyb7uxid4nki/Wiiflow\_CartDisk.7z/file).
2. Extract each ZIP to a separate folder.

#### WiiFlow CartDisk

1. Open the folder called **Wiiflow\_CartDisk**.
2. Copy the **wiiflow** folder to the root of your SD Card.

#### WiiFlow Database

1. Open the folder called **Wiiflow\_Database**.
2. Copy the **wiiflow** folder to the root of your SD Card.

#### WiiFlow Snapshots

1. Open the folder called **Wiiflow\_Snapshots\_MOD**.
2. Locate the **wiiflow** folder and copy this folder to the root of your SD Card.

### Rhapsodii Shima WiiFlow Theme

The Rhapsodii Shima theme is a custom visual theme designed for WiiFlow. It features unique graphics, backgrounds, and icon designs that enhance the visual appeal of WiiFlow, making your game library more engaging and visually appealing.

1. Download [Rhapsodii Shima Theme](https://gbatemp.net/download/rhapsodii-shima.36278/version/40103/download).
2. Extract ZIP to folder.
3. Locate the **wiiflow** folder and copy this folder to the root of your SD Card.

## WiiFlow Configuration

### WiiFlow Forwarder

To install the WiiFlow forwarder, we need to use Yet Another Wad Manager Mod (YAWMM). This tool will allow us to install the forwarder as a custom channel on your Wii's system menu. Once the installation is complete, you should see a new WiiFlow channel on your system menu. This channel provides a convenient shortcut, enabling you to launch WiiFlow directly with just one click.

1. Power on your console.
2. Launch the Homebrew Channel.
3. Hover over **Some YAWMM Mod** and press Ⓐ on your controller.
4. Hover over **Load** and press Ⓐ on your controller.
5. Make sure that **Select source device** shows **Wii SD Slot** and then press Ⓐ on your controller.

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

6. Scroll until you have selected **wads** and then press Ⓐ on your controller.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

7. Select the Blue Circles .wad and press Ⓐ on your controller.

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

8. Make sure that select action shows **Install WAD** and then press Ⓐ on your controller.

<figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

9. Wait for the installation process to complete and then press Ⓐ on your controller to continue.
10. Press the 🏠︎ button on your controller to restart the console.

### WiiFlow Settings

Launch the WiiFlow app using the WiiFlow channel on your consoles system menu.

#### Set Game Partitions

1. Press the 🏠︎ button on your controller.
2. Hover over **Settings** and press Ⓐ on your controller.
3. Locate **Game Partitions** hover over **Set** and press the Ⓐ button on your controller.
4. Set **Wii Partition** and **GameCube Partition** to **USB2**.

#### Apply Rhapsodii Shima WiiFlow Theme

1. Press the 🏠︎ button on your controller.
2. Hover over **Settings** and press Ⓐ on your controller.
3. Locate **Theme** and change this to **Rhapsodii Shima**.
4. Press **Back** and wait for WiiFlow to reload.

#### Rhapsodii Shima WiiFlow Theme Configuration

1. Press the 🏠︎ button on your controller.
2. Hover over **Settings** and press Ⓐ on your controller.
3. Locate **Sourceflow settings**, hover over **Set** and press Ⓐ on your controller.
4. Enable Sourceflow by changing toggle to **On**.
5. Press **Back**.
6. To exit back to the game library press Ⓑ on your controller.

### WiiFlow AutoBoot

WiiFlow Auto Boot is a feature that allows the WiiFlow application to start automatically when the Wii console is turned on.

1. Power off the console.
2. Whilst holding down the **reset** button on the front of your Wii, press the **power** button once and continue holding the **reset** button until you see Priiloader main menu.
3. Select **Settings** and press Ⓐ on your controller.
4. Select **Autoboot** and change this to **Installed File**.
5. Select **Save Settings** and press Ⓐ on your controller.
6. Select **Exit**.
7. Select **Load/Install File** and press Ⓐ on your controller.
8. Select **WiiFlow WFL** and press Ⓐ on your controller.
9. Wait for the installation to complete and then press Ⓑ on your controller.
10. Select **Exit**.
11. Select **Installed File**.
12. Reboot the console to confirm that WiiFlow automatically starts.

## Games

### Wii

{% hint style="info" %}
Wii game backups need to be in **.wbfs** format.
{% endhint %}

#### Wii Backup Manager

1. Download [Wii Backup Manager](https://wiibackupmanager.co.uk/ad/WiiBackupManager\_Build78.html).
2. Extract ZIP to folder.
3. Launch Wii Backup Manager.
4. Make sure that the **files** tab is active and select **Add** and then **Folder**.

<figure><img src="../../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

5. Select the folder that contains your Wii games in .wbfs format.
6. Click **Select** and then **All**.

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

7. Click **Transfer** and then **WBFS File**.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

8. Select the **wbfs** folder on your External HDD.
9. Once the progress bar reaches 100%, the game backups have been successfully transferred, and you can close the program.

### GameCube

{% hint style="info" %}
GameCube game backups need to be in **.iso** format.
{% endhint %}

#### GameCube Backup Manager

1. Download [GameCube Backup Manager](https://github.com/AxionDrak/GameCube-Backup-Manager/releases/download/2.6.1.9/GCBM.zip).
2. Extract ZIP to folder.
3. Launch GameCube Backup Manager.
4. Make sure the **Files (Destination)** tab is active, then click the dropdown to select the drive letter of your external HDD.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Select the **Files (Source)** tab and then click **More Directories**.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

6. Select the folder that contains your GameCube games in .iso format.
7. Tick the box next to each game and then click **Install Game**.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

8. Once the progress bar reaches 100%, the game backups have been successfully transferred, and you can close the program.

### Emulators

Please see the table below to know what file types each console supports, as well as recommended emulators and game file locations.

#### Handhelds

| Device                   | Emulator                           | File Type | File Location                   |
| ------------------------ | ---------------------------------- | --------- | ------------------------------- |
| Game and Watch           | Nintendo GW (Retroarch)            | TBA       | usb1:/ROMS/Nintendo/GW          |
| Game Boy                 | Nintendo GB (Gambatte-RA)          | TBA       | usb1:/ROMS/Nintendo/GB          |
| Game Boy Advance         | Nintendo GBA (mGBA-RA)             | TBA       | usb1:/ROMS/Nintendo/GBA         |
| Game Boy Color           | Nintendo GBC (Gambatte-RA)         | TBA       | usb1:/ROMS/Nintendo/GBC         |
| SNK Neo Geo Pocket       | SNK Neo Pocket (Wiimednafen)       | TBA       | usb1:/ROMS/Neo/Neo Pocket/BW    |
| SNK Neo Geo Pocket Color | SNK Neo Pocket Color (Wiimednafen) | TBA       | usb1:/ROMS/Neo/Neo Pocket/Color |
| Nintendo Virtual Boy     | Nintendo VB (WiiMednafen)          | TBA       | usb1:/ROMS/Nintendo/VB          |
| Sega Game Gear           | Sega Game Gear (Hexaceo)           | TBA       | usb1:/ROMS/Sega/Game Gear       |
| WonderSwan               | WonderSwan (WiiMednafen)           | TBA       | usb1:/ROMS/WonderSwan/BW        |
| WonderSwan Color         | WonderSwan Color (Hexaeco)         | TBA       | usb1:/ROMS/WonderSwan/Color     |
| Atari Lynx               | Atari Lynx (WiiMednafen)           | TBA       | usb1:/ROMS/Atari/Lynx           |

#### Consoles

| Device                              | Emulator                       | File Type | File Location                    |
| ----------------------------------- | ------------------------------ | --------- | -------------------------------- |
| Coleco Vision                       | Colecovision (WiiColem)        | TBA       | sd:/wiicolem/roms                |
| vtech creativision                  | CreatiVision                   | TBA       | usb1:/ROMS/funny                 |
| Family Computer Disk System         | Nintendo FDS (wiimednafen)     | TBA       | usb1:/ROMS/Nintendo/FDS          |
| Intellivision                       | Intellivsion (JzintvWii)       | TBA       | sd:/jzintvWii/roms               |
| Magnavox Odyssey 2                  | Odyssey2 (O2EM-Wii)            | TBA       | usb1:/ROMS/romsodd               |
| Nintendo Entertainment System       | Nintendo NES (FCEUmm-HEX)      | TBA       | usb1:/ROMS/Nintendo/NES/FCEUmm   |
| Nintendo 64                         | Nintendo N64 (Not64)           | TBA       | sd:/not64/roms                   |
| NEC PC Engine                       | NEC PCE (Fast-RA)              | TBA       | usb1:/ROMS/NEC/PCE               |
| NEC PC Engine CD-ROM 2              | NEC PCE CD (Fast-RA)           | TBA       | usb1:/ROMS/NEC/PCE CD            |
| NEC PC Engine Super Grafx           | NEC SGFX (Hexaeco)             | TBA       | usb1:/ROMS/NEC/SGFX              |
| NEC PC FX                           | NEC PC-FX (WiiMednafen)        | TBA       | usb1:/ROMS/NEC/PC-FX             |
| PlaySation                          | PlaySation (WiiStation)        | TBA       | usb1:/ROMS/Sony/isos             |
| Nintendo Satellaview                | Nintendo Satellaview (Hexaeco) | TBA       | usb1:/ROMS/Nintendo/Satellaview/ |
| Sega Genesis 32X                    | Sega 32X (Retroarch)           | TBA       | usb1:/ROMS/Sega/32X              |
| Sega Genesis                        | Sega Mega Drive (GX-RA)        | TBA       | usb1:/ROMS/Sega/Mega Drive       |
| Sega Master System                  | Sega Master System (GX-RA)     | TBA       | usb1:/ROMS/Sega/Master System    |
| Sega Mega CD                        | Sega Mega CD (GX-RA)           | TBA       | usb1:/ROMS/Sega/Mega CD          |
| Sega SG-1000                        | Sega SG-1000 (Hexaeco)         | TBA       | usb1:/ROMS/Sega/SG-1000          |
| Super Nintendo Entertainment System | Nintendo SNES (Hexaeco)        | TBA       | usb1:/ROMS/Nintendo/SNES         |
| GCE Vectrex                         | Vectrex (VectrexWii)           | TBA       | usb1:/ROMS/Vectrex/              |
| Amstrad GX 4000                     | Amstrad GX4000 (Retroarch)     | TBA       | usb1:/ROMS/Amstrad/GX4000        |
| Atari 2600                          | Atari 2600 (Retroarch)         | TBA       | sd:/wii2600/roms                 |
| Atari 5200                          | Atari 5200 (Retroarch)         | TBA       | sd:/wiixl/software/5200          |
| Atari 7800                          | Atari 7800 (Wii7800)           | TBA       | sd:/wii7800/roms                 |
| Atari XE Video Game System          | Atari XEGS (Retroarch)         | TBA       | sd:/wiixl/software/XEGS          |

#### Computer Systems

| Device                 | Emulator                | File Type | File Location            |
| ---------------------- | ----------------------- | --------- | ------------------------ |
| BBC Micro              | BBC MICRO               | TBA       | sd:/apps/beebem/games    |
| Commodore 64           | C64 (C64-Network.org)   | TBA       | sd:/frodo/Games          |
| Dragon32               | Dragon 32/64            | TBA       | usb1:/ROMS/Dragon        |
| MSX                    | MSX (Retroarch)         | TBA       | sd:/MSX/Games            |
| Nec PC-8800            | NEC PC-8801             | TBA       | sd:/quasi88/disk         |
| Philips VG 5000        | VG5000 (dcvg5k)         | TBA       | sd:/apps/dcvg5k/software |
| Thomson                | Thomson MO5 (Retroarch) | TBA       | usb1:/ROMS/Thomson       |
| TRS-80 Colour Computer | Tandy CoCo 1/2          | TBA       | usb1:/ROMS/Coco          |
| TRS-80 Micro Computer  | TRS-80 (sdltrs-wii)     | TBA       | usb1:/ROMS/TRS80/disks   |
| Sinclair ZX Spectrum   | ZX Spectrum (Hexaceo)   | TBA       | sd:/fbzx-wii             |
| Commodore Amiga        | Amiga                   | TBA       | sd:/uae/floppies/        |
| Amstrad CPC            | Amstrad CPC (Retroarch) | TBA       | usb1:/ROMS/Amstrad/CPC   |
| Apple II               | Apple II                | TBA       | sd:/wiiapple/            |
| Atari 800              | Atari XL (WiiXL)        | TBA       | sd:/wiixl/software/800xl |
| Atari ST               | Atari ST                | TBA       | sd:/hatari/fd            |

## Credits

Below are some of the key individuals and teams who deserve special recognition for their efforts in making tools, mods, and resources available to the Wii community.

| Product | Creator |
| ------- | ------- |
|         |         |
|         |         |
|         |         |
