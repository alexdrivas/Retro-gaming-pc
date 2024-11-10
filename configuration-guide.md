# RetroPie Configuration Guide

This guide will walk you through the essential configurations for RetroPie to create a dedicated gaming console experience.

## Step 1: Initial Controller Setup
1. When RetroPie boots for the first time, you’ll be prompted to configure a controller.
2. Follow the on-screen instructions to map each button. You can skip buttons by holding down any button if your controller doesn’t have them.

## Step 2: Wi-Fi Configuration (Optional)
If you want to connect to Wi-Fi for updates:
1. In the main menu, go to **RetroPie > WiFi**.
2. Select your network and enter the password.

## Step 3: Enable SSH (Optional)
For easier file management and remote access:
1. Navigate to **RetroPie > Raspi-Config**.
2. Go to **Interface Options > SSH** and enable it.

## Step 4: Adding Game ROMs
1. There are multiple ways to add games:
   - USB Drive: Create a folder named `retropie` on a USB drive, insert it into the Pi, and copy ROM files into the folders created on the drive.
   - Network: Use Samba to access RetroPie’s folders over the network and add games.
2. For a list of compatible emulators and ROMs, see the [RetroPie Documentation](https://retropie.org.uk/docs/).

## Step 5: Advanced Settings
For optimal performance, adjust video, sound, and controller settings in the RetroPie menu.
