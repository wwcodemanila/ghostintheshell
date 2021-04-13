# How to install Ubuntu as a Virtual Machine (VM)

## Who is this for?

If you are a Windows user and you don't want to use WSL2, this is for you.

Mac and existing Linux users do not need to install this for the Tech Up event.

## Download resources

You will first need to install VirtualBox on your machine. You can download this from the VirtualBox 6.x.x platform packages at https://www.virtualbox.org/wiki/Downloads. Choose `Windows hosts` as the platform package.

You will also need to download the Ubuntu LTS image from OSBoxes (https://www.osboxes.org/ubuntu/). As of this writing, that would be version `20.04.2 Focal Fossa`. 

## Install VirtualBox

Installing VirtualBox is straightforward. Just run the VirtualBox installer and follow the instructions shown to you. Just choose the default settings.

## Use the Ubuntu LTS image

1. Unzip the image. 
2. Open the VirtualBox program.
3. Go to `File` > `Virtual Media Manager`.
	1. Choose `Add Disk Image`.
	2. Choose the Ubunti image you had unzipped earlier.
	3. Close the window.
4. Click on the `New` icon.
5. Enter the following information.
	1. Choose a `Name` for your virtual machine.
	2. Choose the `Machine Folder` where you unzipped the Ubuntu image.
	3. Set `Type` as Linux.
	4. Set `Version` as Ubuntu (64-bit).
	5. Under `Hard Disk`, choose `Use an existing virtual hard disk file`. Then choose `Ubuntu`.
	6. `Create` the virtual machine.

To test it, just double click on the name of the virtual machine you had just created.

To log in, the password is `osboxes.org`.
