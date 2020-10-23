# MSFREEDOM
Collection of guides to get Windows for free

## Disclaimer
This document is for educational and testing purposes only. I recommend you buy Windows and other Microsoft products genuinely and legally.


### Guides:
Get a clean Enterprise LTSC ISO v316 (using SVF repo):

Steps:

0. Here is the SVF repo for reference: https://bit.ly/3kiyCLD 
1. Download the consumer ISO: https://bit.ly/35quKBZ
2. Download the LTSC .svf: https://bit.ly/37A56h0
3. Download svfx.exe: https://bit.ly/3jnffQj
4. Extract the ISO from the RAR
5. Make a new folder and put the extracted ISO, the .svf file and svfx.exe in it
6. Run svfx.exe and the LTSC ISO will be created


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

6. reboot
7. run Windows Update
8. reboot
9. run KMSpico

Additional stuff:

MDL thread for Enterprise LTSC: https://forums.mydigitallife.net/threads/discussion-windows-10-enterprise-n-ltsc-2019.76325/

Techbench dump (download clean Windows ISOs): https://tb.32767.ga/

KMSpico torrent: http://mgnet.me/eoTE4E0

List of generic keys for Windows:
WindowsClub list: https://www.thewindowsclub.com/generic-windows-10-product-keys-to-install-windows-10-enterprise

Offical Microsoft list: https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys

TenForums list (very complete): https://www.tenforums.com/tutorials/95922-generic-product-keys-install-windows-10-editions.html
