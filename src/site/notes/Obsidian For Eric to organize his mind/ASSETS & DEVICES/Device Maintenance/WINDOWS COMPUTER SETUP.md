---
{"dg-publish":true,"permalink":"/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/windows-computer-setup/"}
---

# WINDOWS COMPUTER SETUP

Windows computer setup will be broken down into two parts:

1. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/device-maintenance/the-difference-between-windows-iso-types/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# THE DIFFERENCE BETWEEN WINDOWS ISO TYPES


We keep all our iso(s) downloaded and stored locally on a flashdrive as shown below. This enables us to work both offline, within the community, in situations where there is no internet access, as well as work faster in that we wont have to wait for an iso file to download before setting up a bootable flashdrive. 

<iframe src="https://drive.google.com/file/d/1zhzBUqErzzv-wlB8AUT5NgbKDJbUQzMq/view" width="800" height="600" title="Embedded Google Doc"></iframe>


The flashdrive shown above has the following list of windows iso files:
1. 


This file is meant to document the differences between the different iso files in this flashdrive.

1. en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso is our version 2 windows installation iso. It is a Long Term Servicing Channel, a version of Windows 10 that is designed for use cases where stability and compatibility are more important than access to new features. LTSC releases of Windows 10 are intended for devices that are used in critical systems, such as medical equipment or air traffic control systems or industrial controllers. The primary reason why we use this in the hub is to reduce the number of windows feature updates, and get a more cleaner version of windows with minimum bloatware.
    
2. Win_10_Pro_Build_18363.1909.476.iso is our windows lean version 3 windows installation. Windows 10 Lean is a smaller edition of Windows 10 for devices with 16GB of storage or less1. It is also known as Windows 10 CloudE or Windows 10 S. It has a smaller footprint and less features than the regular Windows 10, such as no Registry Editor, no Microsoft Management Console, no wallpapers, no drivers for CD/DVD drives, and so on. It is designed to run faster and more efficiently on low-end devices. We use this as our version 3 windows installation because it does not have bloatware at all and can run effeciently on low specs devices. However, we will have to hunt down for drivers for this version of windows.
    

### Miscalleneous

[](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/OS_ISO#-miscalleneous)

As of the time i wrote this documentation, the remaining versions of windows were lagely untested. Please feel free to play around with them as per requirements. However, Windows 10 Lite Edition 19H2 x64.iso seemed to run slow for some strange reason after installation - It slowed down the computer using this version of windows and i needed more time to investigate. tiny10 21H2 x64 2209.iso is still untested.

Version 1 of windows refers to the version that came pre-installed with the computer.

</div></div>



1. _Windows OS installation_ Which can be found on the [OS_ISO](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/OS_ISO) branch of our github documentation

<iframe src="https://drive.google.com/file/d/1Fw-_nMnFrNlqqTzO25SSzY3WYpZ1tUOs/view?usp=drive_link" width="800" height="600" title="Embedded Google Doc"></iframe>


The 4 Bootable flashdrives to the right are Windows 10 installation drives with the following differences:

_**Pink:**_ This flashdrive has Windows 10 Lean installed. Windows 10 lean is suitable for low spec or very old computers as it does not need a lot of resources to run. The price to pay is having to find drivers.

_**Blue & Purple:**_ These flashdrives have Windows 10 LTSC UEFI version. This uses more resources than Windows 10 Lean, but less than the manufacturer installed windows 10. It is suitable for medium-capacity computers. Practically, it can be used interchangeably with Windows 10 Lean, but Windows 10 Lean feels more snappier when using compared to LTSC windows 10.

_**Red:**_ This flashdrive has Windows 10 LTSC Legacy installation. It is used to install windows in old desktop computers that do not support UEFI mode.

  








To the right, the flashdrive has all the iso and software that can be used to create Bootable flashdrives

2. _Software Installation._ Which can be found on the [Win10_lean](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/Win10_lean) or [Win10_LTSC](https://github.com/RUCE-Social-Innovation-Hub/RUCE-SIH-Offline-Software-Installation/tree/Win10_LTSC) branches of our github account. These flash drives are to be used with their respective flavors of windows installation. They contain scripts which creates user accounts, removes excess programmes and installs required programmes.
    

  
<iframe src="https://drive.google.com/file/d/1W2dVoIodYEaLk-7nMzShf9aczKd1JAot/view?usp=drive_link" width="800" height="600" title="Embedded Google Doc"></iframe>
<iframe src="https://drive.google.com/file/d/1W2dVoIodYEaLk-7nMzShf9aczKd1JAot/view" width="800" height="600" title="Embedded Google Doc"></iframe>



There is a [script](https://drive.google.com/drive/folders/1iBlNXMg1huBp4YyCMhtNqsTUaIEf1xi3?usp=share_link) that can be run to set up all needed software and login info for computers and laptops.

ON SANDISK USB(s) and [GOOGLE DRIVE](https://drive.google.com/drive/folders/1iBlNXMg1huBp4YyCMhtNqsTUaIEf1xi3?usp=share_link)

O – Windows 10 OS installation

S – is the offline setup for computers and laptops
