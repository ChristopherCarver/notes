---
layout: post
title: Notability Guide
subtitle: Getting started with Notability today
categories: Notability
tags: [guide, notetaking]
---

-=DRAFT=-

## About

This Notability guide assists newcomers in creating and taking digital notes on their Apple iPad. Beginning with setup, various features and functions will be explored to get users started. The journey from a new user to a power expert covers many topics, providing valuable insights along the way. Enjoy!

### Setup

To start, you need either an iPad or iPad Pro with Notability installed. This is the bare minimum to begin. This guide recommends having a keyboard and a pen compatible with your iPad. While you don't need a Magic Keyboard or an Apple Pencil, owning the latter will significantly enhance your experience. Having both will greatly improve your experience.

**Note:** The guide will not be covering Notability for MacOS, because the author works 100% from an iPad Pro.

## Start Here

For all things Notability and the source of truth concerning Notability, go directly to the [**Notability's**](https://notability.com) website. There, you'll find their [**Blog**](https://blog.notability.com) offering tips and tricks, and their [**Support**](https://support.gingerlabs.com/hc/en-us) with troubleshooting resources.

This guide is a suppliment to and not a replacement for Notability's documentation. If in doubt, trust Notability's documentation and direction.

> [!NOTE]
> The [**Support**](https://support.gingerlabs.com/hc/en-us) page takes you to a URL owned by **Ginger Labs** because Ginger Labs is the parent company that creates the Notability application.

{% include alert.html type="info" title="Info!" content="The [**Support**](https://support.gingerlabs.com/hc/en-us) page takes you to a URL owned by **Ginger Labs** because Ginger Labs is the parent company that creates the Notability application." %}

{% include alert.html type="warning" title="Warning!" content="This is a warning alert." %}

{% include alert.html type="danger" title="Danger!" content="This is a danger alert." %}

### Support

Notability offers a few channels to get both direct support and community help. 

**Direct support** is found both in online chat and within the Notability app. 
- *Online chat*: 
    1. Go to [**Ginger Labs**](https://support.gingerlabs.com)
    2. In the bottom right click **Help** 
    3. Enter your question in the *How can we help?*
- *Notability app*:
    1. From the Library screen (where Subject and Dividers are shown), click **Settings** (⚙️) > **Help** > **Contact Support**
    2. Fill in all of the fields with as much details and clarity as you can provide

**Community support** is found on both on Reddit and Discord.
- *Reddit*: Go to [**r/notabilityapp**](https://www.reddit.com/r/notabilityapp/)
- *Discord*: Go to [**Notability**](https://discord.gg/8tBaR2EF) 

Like any form of community involvement your mileage will vary in the tone and assistance from others. 

## First Things First

Life is filled with rough and tough days. These two topics of *Auto-Backup* and *iCloud Sync* might help you prevent turning rough days into terrible days. 

### Auto-Backup

**Before you create your first note**, turn on auto-backup. You might be thinking, *"I'm safe, I have iCloud sync turned on."* Plain, simple, and to the point: iCloud Sync is not enough and will not protect you. Not because you cannot trust Notability or Apple, but because life happens and iCloud Sync doesn't cover all of the scenarios.

**Instructions:**
1. From **Library** window, go to __Settings__ (⚙️).
2. Select __Auto-Backup__.
3. Choose one of the cloud service providers listed in the **Select Service**. If you do not see your cloud provider, then I suggest you choose one of the ones provided. They all have free-tier options. 
4. Select the **Destination** folder to store your backups into.
5. Under **File Format** it is suggested, if you are in a position where you do not have a spare iPad, iPhone, or Mac, then select **PDF + Recording**; else select **Note**. 

**PDF + Recording** is suggested in the event your device stops working and you need access to your notes, a PDF is a universal format that most systems can open from anywhere. If you have another device that you can install Notability on, storing the backups as **Note** is preferred. You can always export **Note** to **PDF** later. 

**Pros & Cons**

There are some unique pros and cons for both formats. Choose the right one accordingly.

| Type | Pros | Cons |
|:------|:------|:------|
| PDF | PDF format is universally accepted. This means notes can be easily accessible and easy to print. | Once you convert a note to PDF, then those elements you added are locked in place and cannot be edited later. |
| Note| If you need to restore from backup, then you can resume editing your note as needed. | Can only be viewed by the Notability application. |

### iCloud Sync (WARNING)

Notability supports iCloud Sync to synchronize your notes across your iPhone, iPad/Pro, and Mac devices. However, carefully consider whether you truly need to use iCloud Sync.

There is a common misconception that iCloud Sync is the same as iCloud Drive. iCloud Sync is an Apple service of iCloud Drive, however iCloud Sync does not behave like that of Box, Dropbox, Google Drive, or OneDrive. iCloud Sync, not Notability, determines where your data resides. Your data should reside on iCloud Drive regardless, but iCloud Sync determines (not Notability) if a local copy resides on your device. You will also notice, you do not have direct access to your Notability files on iCloud Drive and that's because iCloud Sync protects them within your iCloud Drive and you can only access your Notability files from Notability. All of this comes into play when addressing iCloud Sync issues.

The most common issue involves missing or empty notes. This is not a Notability issue but an Apple one. Many apps that leverage iCloud Sync suffer from the same issues. Typically what happens is iCloud Sync determines to free up space on your device and then removes the local copy of those notes; even if you have 10GB of free space for a 10MB note. Normally this is not a problem until you need access to those notes in a timely fashion.

The biggest problem with iCloud sync arises when there is little to no internet service available or the amount of notes that need to be synced back to the device. This frequently impacts individuals in older buildings that lack stable internet connectivity. Typically, this happens to students and faculty located in outdated buildings with unstable WiFi connections.

**Advice:**
- **Only** use iCloud sync if you plan on editing notes on **more than one device**.
- **Consider** not using iCloud sync if you plan on editing on **only one device**.
- **Turn on** auto-backup.

Notability has no control over iCloud Sync, so problems that arise from iCloud Sync should be directed to Apple. Notability has a page dedicated to [troubleshooting iCloud sync issues](https://support.gingerlabs.com/hc/en-us/articles/205688797-Troubleshooting-iCloud-Sync). 

### Restoring Notes

If you are here, you are having a rough day. Let's see if we can make it better.

If you have iCloud Sync turned on and there are missing or empty notes, then follow Notability's [troubleshooting iCloud sync issues](https://support.gingerlabs.com/hc/en-us/articles/205688797-Troubleshooting-iCloud-Sync).

#### From Notability

If you manually deleted a note (intentionally or accidentally) **within the last 30 days**, follow these steps.

**Instructions:**
1. Open the **Notability** application.
2. From **Library** window, go to **Settings** (⚙️).
3. Select **Recently Deleted**.
4. Select the notes to recover and click **Recover Notes**.

#### Restore From Backup

In order for these instructions to work, you must have turned on and configured Auto-Backup.

Currently there is no bulk import of either Note or PDF files within Notability. You will have to restore each individually.

**If Auto-Backup was saved as Note:**
1. From the device that has **Notability** installed, open your **cloud storage application** where the notes were saved to.
2. Go to the **folder** where the **Note(s)** were saved.
3. Click on the **file**. This will trigger an automatic import into Notability. You will be prompted where to place the Note.

**If Auto-Backup was saved as PDF:**
1. From the device that has **Notability** installed, open your **cloud storage application** where the notes were saved to.
2. Go to the **folder** where the **Note(s)** were saved.
3. Long-press on the **file** and select **Share**.
4. Select **Notability**. You will be prompted where to place the PDF.

## Note Taking 101

### Flat vs Dynamic Note Taking
