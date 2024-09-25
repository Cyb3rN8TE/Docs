# Restore

## Introduction

This section will guide you through **restoring** the data on your PlayStation 3 Internal HDD and External HDD.&#x20;

Should anything happen to your console, Internal HDD, or External HDD, having backups in place will make it simple to restore everything to the way it was. You’ll learn how to properly recover both storage devices, ensuring your games, saves, and homebrew applications are back up and running with minimal hassle.

We're going to be using two programs to get the job done:

* **Rescuezilla Live OS**: Allows us to restore full disk image backups, ensuring a precise and reliable recovery of all the data on your storage devices.
* **FileZilla**: Enables us to connect via FTP to the PlayStation 3's HDD0 partition, allowing us to restore our games, homebrew apps, and other data directly to the console's internal hard drive. This makes the restoration process straightforward and efficient, ensuring all your content is transferred back seamlessly.

## Equipment

You will need:

* Blank USB Flash Drive.
* Computer.
* Ethernet connection to your PS3.
* Internal or External Storage that has enough available space to store the backups.

## External HDD

### Restore PlayStation 3, PlayStation 1 Games

1. Download [Rescuezilla](https://github.com/rescuezilla/rescuezilla/releases/download/2.5.1/rescuezilla-2.5.1-64bit.noble.iso).
2. Download [Rufus](https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe).
3. Use Rufus to create a bootable USB using the Rescuezilla ISO.
4. Boot the Rescuezilla OS.
5. Insert your External HDD.
6. Select **Restore** and follow the prompts.

## Internal HDD

### Restore HDD0 Partition

1. Download [FileZilla](https://download.filezilla-project.org/client/FileZilla\_3.67.1\_win64\_sponsored2-setup.exe).
2. Launch FileZilla and FTP to your console.
3. Open the HDD0 folder.
4. Copy the following folders from your HDD0 backup to HDD0 on the console:

| Source | Destination |
| ------ | ----------- |
| PS2ISO |             |
| MAME   |             |
|        |             |
