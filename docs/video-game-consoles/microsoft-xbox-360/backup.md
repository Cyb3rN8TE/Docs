# Backup

## Introduction

This section will guide you through **backing up** the data on your Xbox 360 Internal HDD and External HDD.&#x20;

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

## Preparation

1. Download [Rescuezilla](https://github.com/rescuezilla/rescuezilla/releases/download/2.5.1/rescuezilla-2.5.1-64bit.noble.iso).
2. Download [Rufus](https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe).
3. Use Rufus to create a bootable USB using the Rescuezilla ISO.

## External HDD

1. Boot the Rescuezilla OS.
2. Insert your External HDD.
3. Select **Backup** and follow the prompts.

## Internal HDD

1. Connect your Xbox 360 Internal HDD to your computer using a SATA to USB converter.
2. Run FATXplorer and select the **Devices** tab and click **Open with FATXplorer's**.

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

3. Click **Toolkit View**.

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

4. Click **Partition Tools**.

<figure><img src="../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

5. Select the **Backup** option.
6. Select the **Content Partition** and choose a destination to save the backup.
