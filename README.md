# MSFREEDOM
Collection of guides to get Windows for free

## Disclaimer
This document is for educational and testing purposes only. I recommend you buy Windows and other Microsoft products genuinely, legally and legitimately.

## Guides

### Windows 10 (Basic Install)

For Step 1: To download the latest version of Windows 10 from TechBench, click on Windows 10 > Windows 10 and scroll to the bottom of the page. The latest version (20H2 at the time of writing) should be near the bottom of the page.

Steps: 

1. Go to [TechBench](https://tb.32767.ga/) and download whatever build of Windows 10 you desire
2. Write the ISO to a disk using a tool like [Rufus](https://rufus.ie/) and boot into it
3. Install Windows as normal
4. Download [KMSpico](https://forums.mydigitallife.net/threads/kmspico-official-thread.65739/), a very popular activation tool for Windows
5. Temporarily disable your AV and/or whitelist KMSpico (see its README for a list of files to whitelist); KMSpico and other activation tools are detected as false positives and do not contain any malicious code
6. Run KMSELDI.exe and click the massive red button

### Windows 10 Enterprise LTSC

**Skip steps 2, 6 and 7 if you want to use `en_US` as your language.**

Follow these steps ([source](https://forums.mydigitallife.net/threads/info-discussion-downloads-windows-10-1809-final-b-17763-xxx-pc-rs5.77945/page-312#post-1601664)) to create a clean ISO of Enterprise LTSC:

1. Download the Consumer ISO.rar from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/)
2. Download the Consumer EN to XX .svf file in the language of your choosing from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/). 
3. Download the Consumer to LTSC .svf file in the language of your choice (e.g. `en_us`) from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/)
4. Download [SVF eXtractor](https://www.softpedia.com/get/System/Back-Up-and-Recovery/SVF-eXtractor.shtml)
5. Extract the ISO from the RAR
6. Make a new folder and put the extracted ISO, your EN to XX .svf file and svfx.exe in it
7. Run svfx.exe inside that folder and an ISO of your desired language will be created
8. Make a new folder and put the new ISO, the Consumer to LTSC .svf file and svfx.exe in it
9. Run svfx.exe inside that folder and the LTSC ISO will be created

### Additional links

[Enterprise LTSC MDL thread](https://forums.mydigitallife.net/threads/discussion-windows-10-enterprise-n-ltsc-2019.76325/)

[Windows Server MDL thread](https://forums.mydigitallife.net/threads/the-windows-server-repository.49120/)

[Techbench dump](https://tb.32767.ga/) (download clean Windows ISOs)

[KMS_VL_ALL MDL thread](https://forums.mydigitallife.net/threads/kms_vl_all-smart-activation-script.79535/)

[KMSpico MDL thread](https://forums.mydigitallife.net/threads/kmspico-official-thread.65739/)

[Additional Enterprise LTSC downloads](https://forums.mydigitallife.net/threads/info-discussion-downloads-windows-10-1809-final-b-17763-xxx-pc-rs5.77945/page-51#post-1467631)

[(Google Drive) en_US LTSC x64 ISO, can be used with SVFs](https://drive.google.com/file/d/1_hpyK3usbR2oRsjNZ6NoPNqSGAPpSxgd/view)

#### List of generic keys for Windows

[WindowsClub list](https://www.thewindowsclub.com/generic-windows-10-product-keys-to-install-windows-10-enterprise)

[Offical Microsoft list](https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys)

[TenForums list](https://www.tenforums.com/tutorials/95922-generic-product-keys-install-windows-10-editions.html) (very complete)

### Not working

#### These are methods I made that turned out not to work, but I'm keeping them here so I can update and possibly add them back in the future.

#### Upgrade from Windows 10 Home to Pro using Windows Settings

Steps:

1. Open Windows Settings --> Update & Security --> Activation
2. Click on 'Change Product Key'
3. Enter VK7JG-NPHTM-C97JM-9MPGT-3V66T
4. The updater will upgrade Windows for you and automatically reboot
5. Activate Windows normally, with a method of your choosing 

#### Upgrade from Windows 10 Home to Pro using `slmgr`

Steps: 

1. Open Command Prompt as administrator and run:
   `slmgr /ipk VK7JG-NPHTM-C97JM-9MPGT-3V66T`
2. Reboot, run Windows Update, and reboot again
3. Activate Windows normally, with a method of your choosing 

#### Upgrade from Windows 10 Home to Pro for Workstations using Windows Settings

If you are already on Windows 10 Pro and not Home, you can skip steps 1 and 2.

Steps:

0. Ensure Windows is activated
1. Open Windows Settings --> Update & Security --> Activation
2. Click on 'Change Product Key'
3. Enter DXG7C-N36C4-C4HTG-X4T3X-2YV77
4. Reboot, run Windows Update, and reboot again
5. Activate Windows normally, with a method of your choosing 

### Credits

Microsoft, for Windows

Heldigard, for KMSpico

GezoeSloog and Enthousiast, for the Windows 10 LTSC SVF repos

GezoeSloog for SVF eXtractor and loads of other things

LostED for tons of SVF-related stuff

TechBench for providing a clean way to download legitimate ISOs

abbodi1406 for KMS_VL_ALL

WinDev for providing an easy way to download Windows Server, plus other things

Everyone at MyDigitalLife and anyone I possibly forgot


