## Завдання 1
1. Install a Type II Hypervisor (VirtualBox)
Download VirtualBox:

Go to the VirtualBox website.

Download the installer for your operating system (Windows, macOS, or Linux).

Install VirtualBox:

Run the installer and follow the on-screen instructions.

Accept the default settings unless you have specific requirements.

Install VirtualBox Extension Pack (optional but recommended):

Download the Extension Pack from the same website.

Open VirtualBox, go to File > Preferences > Extensions, and add the Extension Pack.

## Завдання 2

Creating a New Virtual Machine
Open VirtualBox and click New.

Enter a name for your VM (e.g., "Ubuntu Desktop").

Select the type (Linux) and version (e.g., Ubuntu 64-bit).

Allocate RAM (e.g., 2048 MB or more depending on your system).

Create a virtual hard disk (VDI format, dynamically allocated, e.g., 20 GB).

Selecting/Adding Hardware
Select your VM and click Settings.

Go to System > Processor and allocate CPU cores (e.g., 2 cores).

Go to Storage and add an ISO file for the operating system installation.

Go to Audio, USB, or other sections to enable additional hardware.

Setting Up a Network
Go to Settings > Network.

Set Attached to to Bridged Adapter to allow the VM to connect to your Wi-Fi network.

Alternatively, use NAT for internet access without direct network visibility.

Working with External Media
Go to Settings > USB.

Enable USB controller and add filters for specific devices (e.g., flash drives).

Insert the USB device, and it will be available in the VM.

##
