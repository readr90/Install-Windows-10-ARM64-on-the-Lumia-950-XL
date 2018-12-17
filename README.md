# Install-Windows-10-ARM64-on-the-Lumia-950-XL
Look for the scripts in the Installation folder.
The main script is FullSetup.ps1
If you have a fresh device (just unlocked and able to get into Mass Storage Mode) execute FullSetup.ps1 directly
If you already have WoA but you want to reinstall it, run ReinstallWindows.ps1. Bear in mind that it will wipe the current installation!
If you want to use the script as a reference, it's also OK. Just take a look and execute each script in order, doing what they tell you to do :)
There are many sub-scripts that are called from the main script. They are thought to be use by experienced users that know about the correct order and steps, so if you don't know exactly what they do, don't run them!
Binaries (AKA "the Files")
For the scripts to run, you have to copy the contents of this Folder inside the folder named Installation, so you you end up having "Installation\Files...". Anyways, the script will check if you did it right ;)
Inside you will find Drivers, the UEFI, flashing tools... everything the scripts need to work :)
