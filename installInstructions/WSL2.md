# How to install Ubuntu using the Windows Subsystem for Linux (WSL 2)

## Who is this for?

We recommend this method to install Linux if you are a Windows user. You must be running a supported Windows 10 version for your system architecture:

  * For x64-based systems: Windows version 1903 or higher
  * For arm64-based systems: Windows version 2004 or higher

To check your system architecture and Windows version, open the **Settings** app, navigate to **System** > **About**, then look for the *System type* and *Version* fields.

If you do not meet this requirement or would rather use a virtual machine, go [here](virtualBox.md).

## Enable Windows features

1. Open the Windows Control Panel. You can locate this via search or inside the **Windows System** folder in the Start Menu.

2. In the Control Panel, navigate to Programs > Programs and Features > Turn Windows features on or off.

3. Enable *Virtual Machine Platform* and *Windows Subsystem for Linux*.

4. Restart your computer.

## Install and configure Linux

1. Download and install the appropriate Linux kernel update package for your system architecture:

  * For x64-based systems: https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
  * For arm64-based systems: https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_arm64.msi

2. Open PowerShell and run the following command: `wsl --set-default-version 2`

3. Open the [Microsoft Store](https://aka.ms/wslstore) and install your favorite Linux distribution. If you do not have a preference, install Ubuntu.

4. Create your user account and password when prompted. Congratulations, you now have a working Linux distribution in Windows!

## Optional: Install additional utilities

The following utilities are not required to install WSL 2, but will improve your development experience.

  * [Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/get-started): an improved command-line experience
  * [Scoop](https://scoop.sh/): a package manager for installing applications from the command-line

## References

* [Official Microsoft documentation](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
