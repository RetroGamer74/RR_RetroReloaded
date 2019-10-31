# RR (RetroReloaded - Boot Manager)

Very Important: For new users, or users updating to RetroReloaded 2.XX for the first time, delete the atmosphere and ReiNX folder on your microSD if they exist. This will provide a clean state before installing.
You can see the changes of each version in the [Releases.] (Https://github.com/RetroGamer74/RR_RetroReloaded/releases)

### Important changes
* Whenever you download a version of RetroReloaded, it may be that the payload.bin that you will extract from the package and will be stored in your microSD in the root folder has been updated. If you use TegraRCMGUI to boot from your PC you must copy this file to your PC. Do not delete it from the SD. Just copy it, then launch it from TegraRCMGUI.

Tinfoil has been removed.

You can remove the Tinfoil and Mercury folders from your microSD folder if you still have them. They will no longer be used in the current context. Tinfoil now requires an ad-hoc version of Atmosphere prepared for this tool and is not acceptable.

When you use the Hekate tool from RetroReloaded there is a button that puts Back RR that allows you to return to the RetroReloaded boot manager whenever you want.

### What is RetroReloaded?

It is a Boot Manager for Switch that allows custom firmwares such as Atmosphere, ReiNX and SX OS to be started in a preconfigured way, from a single menu. In addition to useful tools.

(See CREDITS for more information)

! [alt text] (rr_boot_v3.jpg)

! [alt text] (Settings-RR.jpg)

! [alt text] (Service-RR.jpg)

! [alt text] (Overlay.jpg)

Custom Overlay

! [alt text] (sample-update.jpg)



[! [Chat on Discord] (https://camo.githubusercontent.com/b4175720ede4f2621aa066ffbabb70ae30044679/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742e72676d7676d7676d7676d7676e7d7c7c7c6d7c7c7c6d7c7c6d7c7c6d7c7c6c7c6d7c7c7c6d7c6d7c6d7c7c6d7c7c6d7c7c6d7c7c6d7c7c6d7c7c6d7c7c6d7c6d7c7c6d7c6d7aaaaaaaaaaaaaaaaaaaaaaz

## Installation

### Download

You have two options. Use the Windows Installer, or download the zip in the [Releases] section (https://github.com/RetroGamer74/RR_RetroReloaded/releases) and extract it yourself on your microSD.

#### Option 1
Download the [Windows RetroReloaded Installer] (https://github.com/RetroGamer74/RR_RetroReloaded-RetroReloaded-Switch-RR/blob/master/RR_Installer.rar) to prepare your microSD automatically.

! [alt text] (RR_Installer.jpg)

#### Option 2
Download the latest available release (https://github.com/RetroGamer74/RR_RetroReloaded/releases), extract it by overwriting existing files on your microSD. It does not overwrite configuration files of your applications or delete data.

### Start

To start RetroReloaded you can use the following options.

#### Using a USB-C cable and a PC

If you use this option you will never have to update the payload.bin. Download [NX_Payload_Forwarder] (https://github.com/RetroGamer74/NX_Payload_Forwarder) that I myself developed, using the following link [link] (https://github.com/RetroGamer74/NX_Payload_Forwarder), and copy it to some folder your PC This payload does not require updates because when you run it all it does is load the payload that is in the microSD. Therefore the functionality of this payload is always the same and that way you avoid having to copy the payload.bin that comes updated in the RetroReloaded release.

Once downloaded and copied, using a payload injector such as TegraRCMGui, (see CREDITS), select the payload file you previously downloaded (NX Payload Forwarder). Connect your Switch and your PC via USB-C cable. Enter RCM mode, using your JIG and pressing Vol + and Power. If you do not know how to do this you can enter our discord to ask for help.

[Link to RetroGamer_74 support forums] (https://discord.gg/cUnjkPH)

#### Using Dongles

##### Using the SX OS (TX) dongle

Since version 3.50, the SX OS dongle can be used to start RetroReloaded. Click on the Dongle and start as you usually do. Instead of starting SX OS, the RetroReloaded menu will start, unless you have activated the Autoboot option in RetroReloaded, in which case you will have to press and hold the Vol button - so that the menu appears when it is restarting.

##### Using the R4S dongle

You can use the R4i dongle. Using the following official link to download we flash a payload forwarder.

https://bit.ly/2EsOeKj

