# NVIDIA_P106
NVIDIA P106 GPUs


----------------------------------------
Thanks for help！
DWITG
3440
萌新小姐姐的施工队
zpl8150
刘sir
----------------------------------------


Modify the'nv_dispi.inf'
Open it with Notepad++
Delete the following
Line 383
Line 512
Line 647
Line 18226
Save it
Open'nvaci.inf'
Add the following code below line 499
%NVIDIA_DEV.1C07%           = Section066, PCI\VEN_10DE&DEV_1C07 
Add the following code below line 786
%NVIDIA_DEV.1C07%           = Section066, PCI\VEN_10DE&DEV_1C07  
Add the following code below line 1073
%NVIDIA_DEV.1C07%           = Section065, PCI\VEN_10DE&DEV_1C07  
Add the following code below line 12496
NVIDIA_DEV.1C07 = "NVIDIA P106-100"
Save it
Replace C:\XXX\416.34-desktop-win10-64bit-international-whql\Display.Driver (change'C'to the disk character you unzipped)with 'nv_dispi.inf' 'nvaci.inf'
