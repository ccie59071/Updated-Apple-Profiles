# Updated-Apple-Profiles

NOTE: Please test these profiles before putting them on a production ISE environment. These profiles are not officially endorsed or provided by Cisco in any way. 

These profiles should change the structure, fidelity, and granulary of Apple devices profiled by ISE. In order to use these profiles efficiently, please disable the following built-in Cisco-provided profile policies in ISE: 
<br> Apple-iPad
Apple-iPhone
Apple-Ipod
Apple-Macbook
Apple-Watch
OS_X_Yosemite-Workstation
OS_X_Tiger-Workstation
OS_X_SnowLeopard-Workstation
OS_X_Sierra-Workstation
OS_X_MountainLion-Workstation
OS_X_Mojave-Workstation
OS_X_Mavericks-Workstation
OS_X_Lion-Workstation
OS_X_Leopard-Workstation
OS_X_High_Sierra-Workstation
OS_X_El_Capitan-Workstation
OS_X-Workstation


After those profiles are disabled, import Apple-Import-1. This will update the existing Apple-Device profile policy to include many other attributes to help identify an Apple device even when a 3rd party dongle is used. 

Then you will upload the second Apple-Import-2 xml file. This will add many new Apple device profiles that will hopefully provide additional granular information on the types of Apple devices connecting to your network. 

The following is a representation of the built-in Apple device profile structure and how the profiles are nested by default: https://github.com/network-node/Updated-Apple-Profiles/blob/master/Old-Apple-Profile-Structure.jpg

After uploading these profiles, the Apple profile structure will be organized as so: https://github.com/network-node/Updated-Apple-Profiles/blob/master/New-Apple-Profile-Structure.jpg
