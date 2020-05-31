---
title: Comprehensive guide for Installing Chrome OS with Play Store Support on
  any Laptop/PC - Not Cloudinary
path: /comprehensive-guide-for-installing-chromeos-with-playstore-support-on-any-laptop
tags:
  - The Internet
metaImage: assets/chromeos.png
featuredImage: ./assets/chromeos.png
excerpt: under construction
created: 2020-05-31T10:40:32.414Z
updated: 2020-05-31T10:40:32.501Z
---
## Introduction to chrome OS

If you follow the below mentioned process you will not lose your data, existing operating system (mostly useful for windows users). We are going to install Chrome OS in a Triple Boot Style. Just mentioning in case if you are not aware, the number of boots (Tripe, Dual - whatever is the number) will not affect the performance of your PC (Any booted operating system), it will just consume extra space in your hard disk. But this is not the case if you use any android emulator in your PC, most of the emulators consume a lot of ram which make your overall performance poor

I hope you are aware and clear about the advantages of Triple boot over installing Chrome OS in Virtual Machine/ Virtual Box and over some random Android emulators. With this clear, let's begin - grab a coffee if you can as it sure does take a lot of time in downloading, extracting, auto-configuring and Installing. Here is an overall idea of what we are going to do.

### Requirements

1. UEFI boot support in BIOS
2. Intel based CPU ( AMD CPUs are not tested)
3. 16GB (min. 8GB) USB Flash Drive
4. Unallocated GPT space in HDD (not MBR) (Don't worry here is an explanation)
5. Decent Internet connecting
6. Don't hurry, read each and every word I typed. I minimised as much as possible

### Downloads

1. Linux Mint Cinnamon Image
2. Rufus
3. Chrome Recovery Image
4. Brunch
5. Multi Installer

### Precautions

1. Get a second pendrive
2. Install windows 10 or Your OS in it

### Confirmations and Modifications if required

1. Convert your Windows from Legacy support to UEFI
2. Convert MBR to GPT

If you feel you have the required prerequisites go on and download all the necessary files. If you have any doubts or in need of any clarifications you can always google them or leave a comment in the comment section - you might not get the answer immediately but i'm sure I will try to help you ASAP.

So by now you should have the top 2 downloads mentioned above. One being Linux Mint Cinnamon and the Other being Rufus.

If you are aware of creating your own bootable pendrive without any external software like Rufus you can also follow that or else follow my instructions.

## Creating a bootable pendrive of Linux Mint Cinnamon

* 16gb pendrive
* Select the Linux Mint Cinnamon 64 bit ISO
* Keep all other options as per recommendations and proceed to next
* I would like to call this pendrive i.e., newly created Linux Mint bootable pendrive asNewly Created Bootable Pendriver

## Adding Files and Scripts in the newly created bootable pendrive for later use

* Create a new folder (named:Chrome OS) in our Newly Created Bootable Pendrive - I would like to call this new folder asManually Created Folder
* Extract "Bruch" - previously downloaded, Copy the files in extracted brunch folder, Paste the copied files in the Manually Created Folder of our Newly Created Bootable Pendrive, i.e., named as Chrome OS.
* Extract "Chrome Recovery Image" - previously downloaded, rename the extracted file asrammus_recovery.bin, copy and paste it in the Manually Created Folder of our Newly Created Bootable Pendrive
* Copy and paste Multi-installer.sh - previously downloaded in the Manually Created Folder of our Newly Created Bootable Pendrive
* Remember there should be a total of 6 files in the Manually Created ''Chrome OS" Folder of our Newly Created Bootable Pendrive

Before creating a partition I would like you to check if your device is using a MBR or GPT partition style. Why to check? Always remember by default windows will not allow users to install Windows 10 OS in MBR. So it is always a best practice to check the type of your disk.

## Creating a Partition for for Linux Mint and Chrome OS

## Instal Linux Mint

## Installing Chrome OS