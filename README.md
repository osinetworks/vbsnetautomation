# vbsnetautomation
Network Automation  based on VBS and WMI.
This is very old code. Tool used in low bandwith (128K, 256K) infrastrutucre.
**Features:**
* supports telnet
* Find devices model and type (router or switch)
* Support firmware upgrade.
    * Copy fireware from HQ to branch office If it does not exist.
    * Copy required tftp server, tftpd32.exe. If it is running in remote server kills process, run sent tftp32.exe in right path.
    * check hash after firware loaded.
    * reload device at noon If device upgrade completed before noon (12:30 pm), reload at night If device upgrade completed after noon.
    * check device if it is successfully opened.
    * Write fails and success to report text. 
* Get inventory in comma seperated text.
* Backup Backup
* Configure devices

Supports:
Cisco Catalsyt 2960 IOS 12.x.x
Cisco Router 1760, 1841

Note:
*.exe and *.dll files must be copied to c:\windows\system32
