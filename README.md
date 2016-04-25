#Project Description
 Deployment Automation of Windows Server 2016 labs on WS2016/Windows10 Hyper-V

Simply deploy your lab just with these scripts and ISO file.

 This solution is used in Microsoft Premier Workshop for Software Defined Storage.

#Usage (more info in wiki)

 [Download](https://github.com/Microsoft/ws2016lab/blob/master/scripts.zip?raw=true) scripts
 
 Unzip in some folder
 
 Right-click and run with PowerShell. (1_Prereq.ps1 -> 2_CreateParentDisks.ps1 -> 3_Deploy.ps1 -> Cleanup.ps1 (if needed) -> modify variables.ps1 -> 3_Deploy.ps1 again)

 You will be prompted for Windows Server 2016 ISO (TP5 and newer only) when running 2_CreateParentDisks.ps1. 

 You can create [multiple scenarios](https://github.com/Microsoft/ws2016lab/wiki/variables.ps1-examples) if you modify variables.ps1 - **Simple**, **S2D** works on Windows 10
 **Replica**, **Shared** requires Failover Clustering (svhdx filter driver)
