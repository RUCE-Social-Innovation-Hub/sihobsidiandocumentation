---
{"dg-publish":true,"permalink":"/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/windows-computer-setup/"}
---

# WINDOWS COMPUTER SETUP

Windows computer setup will be broken down into three parts:


1. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/windows-iso-and-software/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# WINDOWS ISO & SOFTWARE


We keep all our ISO(s) and ISO installation software downloaded and stored locally on a flash drive as shown below, ==as well as on Google Drive on this link: ------==. This enables us to work both offline in situations where there is no internet access, as well as work faster in that we wont have to wait for an ISO file to download before setting up a bootable flashdrive. 

![WindowsISO.jpg](/img/user/Obsidian%20For%20Eric%20to%20organize%20his%20mind/ASSETS%20&%20DEVICES/Device%20Maintenance/WindowsISO.jpg)



#### WINDOWS ISO(S)

The flash drive shown above has the following list of windows ISO files in the main OS ISO folder:
1. en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso which can also be downloaded from https://archive.org/details/en-us_windows_10_enterprise_ltsc_2021_x64_dvd_d289cf96_202212
2. Win_10_Pro_Build_18363.1909.476.iso which can also be downloaded from https://archive.org/details/win10pro1909.476lite


Details of the two ISO(s) are as follows:

1. en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso is our version 1 windows installation ISO and the one we use on a regular at the Social Innovation Hub. It is a Long Term Servicing Channel, a version of Windows 10 that is designed for use cases where stability and compatibility are more important than access to new features. LTSC releases of Windows 10 are intended for devices that are used in critical systems, such as medical equipment or air traffic control systems or industrial controllers. The primary reason why we use this in the Social Innovation Hub is to reduce the number of windows feature updates, and get a more cleaner version of windows with minimum bloatware.
    
2. Win_10_Pro_Build_18363.1909.476.iso is our windows lean version 2 windows installation. Windows 10 Lean is a smaller edition of Windows 10 for devices with 16GB of storage or less. It is also known as Windows 10 CloudE or Windows 10 S. It has a smaller footprint and less features than the regular Windows 10, such as no Registry Editor, no Microsoft Management Console, no wallpapers, no drivers for CD/DVD drives, and so on. It is designed to run faster and more efficiently on low-end devices. We use this as our version 3 windows installation because it does not have bloatware at all and can run efficiently on low specs devices. However, we will have to hunt down for drivers for this version of windows.
    
The rest of the ISO files in the Archive folder are experimental and have not been fully implemented. 
	Please feel free to play around with them as per requirements. However, Windows 10 Lite Edition 19H2 x64.iso seemed to run slow for some strange reason after installation. It slowed down the computer using this version of windows and i needed more time to investigate. tiny10 21H2 x64 2209.iso is still untested.


#### WINDOWS INSTALLATION SOFTWARE(S)
The flash drive shown above also has the following list of installation software:
1. rufus-3.20.exe
2. YUMI-2.0.9.4.exe
3. YUMI-UEFI-0.0.4.5.exe
4. MediaCreationTool21H2.exe
5. balenaEtcher-Setup-1.7.9.exe
6. balenaEtcher-Portable-Legacy-1.7.9.exe





</div></div>




2. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/windows-os-installation/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Windows OS installation

A bootable flash drive is one which can be used to install an operating system to a computer, which in our case, Windows 10 operating system. 

In order to create a bootable flash drive, we need both the Windows ISO and Software (RUFUS) described in [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/WINDOWS ISO & SOFTWARE\|WINDOWS ISO & SOFTWARE]]. 



## Creating Windows 10 USB using Rufus

![](https://cdn.shopify.com/s/files/1/0381/7642/4068/files/How-to-use-Rufus-to-install-Windows-10.png)

To create a Windows 10 USB using Rufus (UEFI or Legacy), you can follow these steps:  
_Note_: Before proceeding, make sure you have a Windows 10 ISO file and a USB flash drive with at least 8 GB of storage capacity.


1. Go to the Rufus website ([https://rufus.ie/](https://rufus.ie/)) and download the latest version of Rufus.

2. Once downloaded, run the Rufus executable file to launch the application.

3. Select your USB drive 
	- In the “Device” drop down menu, select the USB flash drive you want to use for creating the Windows 10 USB. (1) in the image above

4. Choose the partition scheme (4) in the image above.
	- MBR is compatible with older BIOS systems and can be used to install windows on extremely old PCs and laptops
	- GPT requires UEFI. GPT is not bootable on BIOS-only systems without compatibility layers. Therefore, we use GPT with more recent PCs and laptops. 

5. Chose target system type (5) in the image above:
	- For Legacy/BIOS or Extremely old PCs and laptops: Under “Partition scheme,” select “[MBR](https://hollandsweb.com/tag/mbr-disk/)” and under “Target system,” select “BIOS or UEFI”.
	- For UEFI or newer PCs and laptops: Under “Partition scheme,” select “[GPT](https://hollandsweb.com/tag/gpt-disk/)” and under “Target system,” select “UEFI (non-CSM).”


6. _Note_: The selection of UEFI or Legacy depends on the type of system you plan to install Windows 10 on. If your computer supports UEFI, it’s recommended to choose the UEFI option.


7. Select the Windows 10 ISO: 
	- Click on the small disk icon next to the “Boot selection” section and browse to the location where you have the Windows 10 ISO file, which for us, can be found as detailed in [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/WINDOWS ISO & SOFTWARE\|WINDOWS ISO & SOFTWARE]]. Select the ISO file and click “Open.”


8. Configure Rufus settings:
	- File system: Select “[**NTFS**](https://hollandsweb.com/tag/ntfs/)” (**recommended**) or “FAT32” as the file system for the USB drive.
	- Volume label: You can provide a custom name for the USB drive if you want.
	- Check the “Quick format” and “Create extended label and icon files” options.
	- Leave all other settings as default unless you have specific requirements.


9. Start the Windows 10 USB creation process (8) in the image above:


10. **Rufus** will display a warning message that all data on the USB will be destroyed. Ensure you have backed up any important data from the USB drive, as this process will format it.


11. Click “**OK**” to proceed, and Rufus will start creating the **Windows 10 USB**. It may take several minutes to complete the process, depending on your system’s speed and the size of the ISO file.


12. Once Rufus completes the process, it will display a “**READY**” status. You can now close Rufus and safely remove the **USB flash drive**.


## Windows 10 installation flash drives

We followed the procedure detailed in [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/Windows OS installation#Creating Windows 10 USB using Rufus\|Windows OS installation#Creating Windows 10 USB using Rufus]] to make the four bootable flash drives shown in the image below

![WindowsInstallation.jpg](/img/user/Obsidian%20For%20Eric%20to%20organize%20his%20mind/ASSETS%20&%20DEVICES/Device%20Maintenance/WindowsInstallation.jpg)

These installation drives have the following differences:

1. _**Pink:**_ This flashdrive has Windows 10 Lean installed (Win_10_Pro_Build_18363.1909.476.iso from [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/WINDOWS ISO & SOFTWARE\|WINDOWS ISO & SOFTWARE]]). 
	- Windows 10 lean is suitable for low spec or very old computers as it does not need a lot of resources to run. The price to pay is having to find drivers. 
	- ***We archived this version of windows***, as it became difficult for end-users to use, since it lacked a lot of the needed windows features such as the ability to connect and share files through Bluetooth. It needs time investment to iron out everything missing, and install accordingly.  



2. _**Blue & Purple:**_ These flashdrives have Windows 10 LTSC UEFI version (en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso from [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/WINDOWS ISO & SOFTWARE\|WINDOWS ISO & SOFTWARE]]). 
	- This uses more resources than Windows 10 Lean, but less than the default windows 10 that comes with the PC or Laptop. It is suitable for medium-capacity computers. Practically, it can be used interchangeably with Windows 10 Lean, but Windows 10 Lean feels more snappier when using compared to LTSC windows 10.



3. _**Red:**_ This flashdrive has Windows 10 LTSC Legacy installation specifically meant to be used with older PCs (Please see [[Obsidian For Eric to organize his mind/ASSETS & DEVICES/Device Maintenance/Windows OS installation#Creating Windows 10 USB using Rufus\|Windows OS installation#Creating Windows 10 USB using Rufus]] above for details). 
	- It is used to install windows in old desktop computers that do not support UEFI mode.
	

</div></div>
 


  







3. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/windows-10-software-installation/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Windows 10 Software Installation
To the right, the flashdrive has all the iso and software that can be used to create Bootable flashdrives

2. _Software Installation._ Which can be found on the [Win10_lean](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/Win10_lean) or [Win10_LTSC](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/Win10_LTSC) branches of our github account. These flash drives are to be used with their respective flavors of windows installation. They contain scripts which creates user accounts, removes excess programmes and installs required programmes.
    
![SoftwareInstallation.jpg](/img/user/Obsidian%20For%20Eric%20to%20organize%20his%20mind/ASSETS%20&%20DEVICES/Device%20Maintenance/SoftwareInstallation.jpg)
  
==Proper Documentation Needed==


There is a [script](https://drive.google.com/drive/folders/1iBlNXMg1huBp4YyCMhtNqsTUaIEf1xi3?usp=share_link) that can be run to set up all needed software and login info for computers and laptops.

ON SANDISK USB(s) and [GOOGLE DRIVE](https://drive.google.com/drive/folders/1iBlNXMg1huBp4YyCMhtNqsTUaIEf1xi3?usp=share_link)

O – Windows 10 OS installation

S – is the offline setup for computers and laptops


</div></div>

