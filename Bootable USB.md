# EP-250318
## BOOTABLE USB
[this is the video link for creating usb](https://www.youtube.com/watch?v=wmqX1-kQKa0)
[this is a 2nd link](https://www.youtube.com/watch?v=NSRCZEKDMK8)
## steps for creating USB
Step 1: Download the Windows ISO File


Step 2: Get a USB Drive
Use a USB flash drive with at least 8GB of storage.
Backup any important data, as this process will erase everything on the USB.

Step 3: Use Rufus (or Windows Media Creation Tool)
Option 1: Using Rufus (Recommended for Advanced Users)
Download Rufus and install it.
Insert the USB drive into your computer.
Open Rufus and select:
Device: Choose your USB drive.
Boot selection: Click "Select" and choose the Windows ISO.
Partition scheme:
GPT for UEFI
MBR for Legacy BIOS
File system: NTFS (recommended)
Click Start, and wait for Rufus to create the bootable USB.
Select "Create installation media for another PC".
Choose your preferred language, edition, and architecture (64-bit or 32-bit).
Select USB flash drive and choose your USB from the list.
Click Next, and the tool will create the bootable USB.

Step 4: Boot from the USB
Insert the USB into the target PC.
Restart the PC and enter the BIOS/Boot Menu (usually F2, F12, Del, or Esc).
Select the USB drive as the boot device.
Follow the Windows installation process.






