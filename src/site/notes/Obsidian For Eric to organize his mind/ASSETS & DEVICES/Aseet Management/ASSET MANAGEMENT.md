---
{"dg-publish":true,"permalink":"/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/asset-management/"}
---


## ASSET TAGS
In order to keep track of various assets available, there is need to develop a tagging system that would differentiate the different asssets that are of the same type. This makes it also easier to give information about a specific asset without confusion as to which asset is being referred to.


#### Barcodes
Barcodes for smaller non-RU assets are catalogued in the Google Drive on the [SIH asset tags (barcodes)](https://docs.google.com/spreadsheets/d/15AfW-mC6pktVMW2x2FFRot9Gs58E7M1z/edit#gid=173501204) Google Sheets. Copies are in the cupboard for loans and a copy is in the Office. It is updated as new accessories are added.

On the ‘unused’ tab of the [SIH asset tags (barcodes)](https://docs.google.com/spreadsheets/d/15AfW-mC6pktVMW2x2FFRot9Gs58E7M1z/edit#gid=173501204) Google sheets are all the new asset tags that have not been used. A Google Sheet function is used to automatically generate barcodes from a website called Berrywing.com. The equation is inserted on every row of the ‘Barcode’ column, where C3 is row 3 of ASSET Tag Column with all the asset tags that you want to generate the barcode from. The barcodes are generated using the equation:

=if(isblank(C3), "BLANK",image("http://berrywing.com/barcode/Code128.aspx?bc=" & C3))

![Barcodes.png](/img/user/Obsidian%20For%20Eric%20to%20organize%20his%20mind/ASSETS%20&%20DEVICES/Aseet%20Management/Barcodes.png)

## ASSET REGISTER
Asset registers are methods through which we keep track of our assets. There are divided into two groups, the manual and automated methods.



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/manual-asset-register/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






</div></div>



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/automated-asset-register/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





## [**Asset Tiger**](https://www.myassettag.com/assettiger/dashboard)

[Asset Tiger](https://www.myassettag.com/assettiger/dashboard) is a device management software used to track equipment, availability, maintenance, loans and check outs, bookings and disposal.

==**Describe categories**==

==**Describe leases vs check outs**==

==**Describe budget tracking**==


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/automated-asset-management-tools/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





## [**Zapier.com**](https://zapier.com/)

Zapier is an online automation tool that connects different services online and automating them as needed.   

For our purposes, Zapier is used to generate tasks on [socialinnovationhub.ru@gmail.com](mailto:socialinnovationhub.ru@gmail.com) that relate to assets needing to be renewed as their expiry date comes close. It is also used to transfer attached pdf(s) of various activities to google drive for future reference purposes. These activities are described below in detail.

  
  
![Zapier.png](/img/user/Obsidian%20For%20Eric%20to%20organize%20his%20mind/ASSETS%20&%20DEVICES/Aseet%20Management/Zapier.png)

  
  

1. _Asset Tiger -_ Asset Tiger sends an automated email to [socialinnovaitonhub.ru@gmail.com](mailto:socialinnovaitonhub.ru@gmail.com), [t.matyobeni@ru.ac.za](mailto:t.matyobeni@ru.ac.za) and [kamau757@gmail.com](mailto:kamau757@gmail.com) every week on Friday morning with an attached pdf of the current asset status. Basically, the lab manager. This can be customized in Asset Tiger settings. Zapier is used to transfer this attached pdf from [socialinnovationhub.ru@gmail.com](mailto:socialinnovationhub.ru@gmail.com) to the [Asset Tiger Automated reports](https://drive.google.com/drive/folders/1MdppvlIfEs5UvxRdhBIbeDm4ZNQnIJRy?usp=share_link) folder. This is a security measure in case records have been altered.
    
2. _Asset Tiger -_ Asset Tiger also sends a reminder email when equipment is about to expire. Zapier is used to add these emails onto google tasks on [socialinnovationhub.ru@gmail.com](mailto:socialinnovationhub.ru@gmail.com) account. This is just for convenience of the lab manager but can be turned off by clicking on the green raio button under Equipment Return zap on Zapier.
    
3. _Google Forms_ – When someone is in need of equipment, the fill in the google form on the following link: [https://forms.gle/jpZywszPTMD2XfEE8](https://forms.gle/jpZywszPTMD2XfEE8). This form sends an email with the attached pdf summarising what equipment is needed to [socialinnovationhub.ru@gmail.com](mailto:socialinnovationhub.ru@gmail.com), and to the lab manager’s email address. Zapier saves this attached pdf emailed by Google Forms, particularly, the [Proposal for long term loans form](https://forms.gle/jpZywszPTMD2XfEE8), in the [Proposal for equipment use](https://drive.google.com/drive/folders/11QFnhquAyg9O00DfyeMCIaeYxd_jZR9d?usp=share_link) folder on the shared SIH Drive for our records.

For more details on how to automate your tasks using zapier, please see this tutorial here:
1. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/how-to-connect-gmail-to-google-drive-using-zapier/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






</div></div>

2. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/obsidian-for-eric-to-organize-his-mind/assets-and-devices/aseet-management/how-to-connect-gmail-to-google-tasks-using-zapier/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






</div></div>



</div></div>



</div></div>


## ASSET TRACKING
The following devices are being tracked.

- MacOS Tracking happens using the [Find My](https://www.apple.com/icloud/find-my/) app on MacOS. All MacOS have a DST MAC # admin account. This Admin account must not be shared. This admin account is logged into the apple ID using [sihdevices@gmail.com](mailto:sihdevices@gmail.com), password in Bitwarden. It is this apple ID You can also access the web portal to track MacOS using this link: [https://www.icloud.com/find](https://www.icloud.com/find). It is very accurate in tracking.
    
- Android devices can be tracked using the following link: [https://www.google.com/android/find](https://www.google.com/android/find). They all use [sihvisitors@gmail.com](mailto:sihvisitors@gmail.com) as their default account. You will need to be are logged in using [sihvisitors@gmail.com](mailto:sihvisitors@gmail.com) in order to track them. Password in Bitwarden. As this is a public gmail account, they will be moved to a separate gmail account, different from [sihdevices@gmail.com](mailto:sihdevices@gmail.com). It is used to track the 10” tablets but not very accurate.
    
    - Samsung Tablets can be tracked using the link: [https://findmymobile.samsung.com](https://findmymobile.samsung.com/). They are using [sihdevices@gmail.com](mailto:sihdevices@gmail.com) samsung account; login in Bitwarden.
        
- Windows Laptops can be tracked using the following link: [https://account.microsoft.com/devices](https://account.microsoft.com/devices). They are logged in using [sihdevices@gmail.com](mailto:sihdevices@gmail.com) Microsoft account on the RUCE Admin account. Login details can be found in the main Bitwarden account. This Admin account must not be shared. It is not very accurate in tracking.

#### SECURITY FLAWS IN ASSET TRACKING
==Explain security flaws==

