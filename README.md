# MSFREEDOM
Collection of guides to get Windows for free

## Disclaimer
This document is for educational and testing purposes only. I recommend you buy Windows and other Microsoft products genuinely and legally.


## Guides:
Get a clean Enterprise LTSC ISO (version .316) (using SVF repository):

**Skip steps 2, 5 and 6 if you want to use en_US as your language.**

Steps ([source](https://forums.mydigitallife.net/threads/info-discussion-downloads-windows-10-1809-final-b-17763-xxx-pc-rs5.77945/page-312#post-1601664)):

1. Download the Consumer ISO.rar from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/)
3. Download the Consumer EN to XX .svf file in the language of your choosing from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/). 
2. Download the Consumer to LTSC .svf file in the language of your choice (e.g [en_us]) from the [SVF repo](https://cloud.mail.ru/public/2fYm/2bzdHD4X2/)
3. [Download](https://www.softpedia.com/get/System/Back-Up-and-Recovery/SVF-eXtractor.shtml) svfx.exe
4. Extract the ISO from the RAR
5. Make a new folder and put the extracted ISO, your EN to XX .svf file and svfx.exe in it
6. Run svfx.exe inside that folder and an ISO of your desired language will be created
7. Make a new folder and put the new ISO, the Consumer to LTSC .svf file and svfx.exe in it
8. Run svfx.exe inside that folder and the LTSC ISO will be created
9. Done

Upgrade from Windows 10 Home to Pro (N) for Workstations:

If you are already on Windows 10 Pro and not Home, you can skip steps 1-4.

Steps:

0. This guide uses the Semi-Annual Channel KMS Client generic keys. For other keys, refer to Generic_Keys.txt at the root of this repository.
1. Admin command prompt:
   slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
   
   For Windows N edition:
   slmgr /ipk MH37W-N47XK-V7XM9-C7227-GCQG9

2. Reboot
3. Run Windows Update
4. Reboot

5. Admin command prompt:
   slmgr /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J
   
   For Windows N edition: 
   slmgr /ipk 9FNHH-K3HBT-3W4TD-6383H-6XYWF

6. Reboot
7. Run Windows Update
8. Reboot
9. Activate Windows normally, with a method of your choosing
10. Done

Additional links:

[MDL thread for Enterprise LTSC](https://forums.mydigitallife.net/threads/discussion-windows-10-enterprise-n-ltsc-2019.76325/)

[Techbench dump](https://tb.32767.ga/) (download clean Windows ISOs)

[KMSpico torrent](magnet:?xt=urn:btih:E954AB6B5A93071E8F1A41C509E77F35A50B1B11&dn=KMSpico_v10.2.0&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.publicbt.com%3a80%2fannounce&tr=udp%3a%2f%2finferno.demonoid.ooo%3a3392%2fannounce&tr=http%3a%2f%2fmgtracker.org%3a2710%2fannounce&tr=udp%3a%2f%2f9.rarbg.com%3a2710%2fannounce&tr=udp%3a%2f%2fglotorrents.pw%3a6969%2fannounce&tr=udp%3a%2f%2ftracker.blackunicorn.xyz%3a6969%2fannounce&tr=udp%3a%2f%2ftracker.ccc.de%3a80%2fannounce)

List of generic keys for Windows:
[WindowsClub list](https://www.thewindowsclub.com/generic-windows-10-product-keys-to-install-windows-10-enterprise)

[Offical Microsoft list](https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys)

[TenForums list](https://www.tenforums.com/tutorials/95922-generic-product-keys-install-windows-10-editions.html) (very complete)
