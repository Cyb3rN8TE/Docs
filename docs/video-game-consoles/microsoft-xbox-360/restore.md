# Restore

## Introduction

This section will guide you through **restoring** the data on your Xbox 360 Internal HDD and External HDD.&#x20;

Should anything happen to your console, Internal HDD, or External HDD, having backups in place will make it simple to restore everything to the way it was. You’ll learn how to properly recover both storage devices, ensuring your games, saves, and homebrew applications are back up and running with minimal hassle.

We're going to be using two programs to get the job done:

* **Rescuezilla Live OS**: Allows us to restore full disk image backups, ensuring a precise and reliable recovery of all the data on your storage devices.
* **FATXplorer**: Enables us to restore the content partition on the Xbox 360 internal hard drive, which contains all your games, DLC, XBLA titles, saves, and other important data.

## Equipment

You will need:

* Blank USB Flash Drive.
* Computer.
* SATA to USB Converter.
* Internal or External Storage that has enough available space to store the backups.

## External HDD

### Restore Xbox Games

1. Download [Rescuezilla](https://github.com/rescuezilla/rescuezilla/releases/download/2.5.1/rescuezilla-2.5.1-64bit.noble.iso).
2. Download [Rufus](https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe).
3. Use Rufus to create a bootable USB using the Rescuezilla ISO.
4. Boot the Rescuezilla OS.
5. Insert your External HDD.
6. Select **Restore** and follow the prompts.

## Internal HDD

### Restore Content Partition

1. Connect your Xbox 360 Internal HDD to your computer using a SATA to USB converter.
2. Run FATXplorer and select the **Devices** tab and click **Open with FATXplorer's**.

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

3. Click **Toolkit View**.

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

4. Click **Partition Tools**.

<figure><img src="../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

5. Select the **Restore** option.
6. Select the **Content Partition** and choose your backup to restore.

### Restore Aurora Cache

We need to run a special script for all of the games to show up in Aurora again without having to rescan the library and reselect the latest title updates for each game. This script will ensure that your game list, along with the necessary title updates, is restored correctly, saving time and effort during the recovery process.

1. Download [DeviceIDUpdater](https://github.com/jrobiche/xbox360-aurora-scripts/blob/main/DeviceIDUpdater/Main.lua).
2. Connect your Xbox 360 Internal HDD to your computer using a SATA to USB converter.
3. Run FATXplorer and select the **Devices** tab and click **Integrate into Windows**.

<figure><img src="../../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

4. Select the **Content Partition** and click **Done**.

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

5. Copy the file to aurora/user/scripts/utility on the Xbox 360 Internal HDD.
6. Run the script from Aurora.&#x20;
