# Updated-Apple-Profiles

NOTE: Please test these profiles before putting them on a production ISE environment. These profiles are not officially endorsed or provided by Cisco in any way. 
<br> 
<br> 
These profiles should change the structure, fidelity, and granulary of Apple devices profiled by ISE. In order to use these profiles efficiently, please disable the following built-in Cisco-provided profile policies in ISE: 
<br> Apple-iPad
<br> Apple-iPhone
<br> Apple-Ipod
<br> Apple-Macbook
<br> Apple-Watch
<br> OS_X_Yosemite-Workstation
<br> OS_X_Tiger-Workstation
<br> OS_X_SnowLeopard-Workstation
<br> OS_X_Sierra-Workstation
<br> OS_X_MountainLion-Workstation
<br>  OS_X_Mojave-Workstation
<br> OS_X_Mavericks-Workstation
<br> OS_X_Lion-Workstation
<br> OS_X_Leopard-Workstation
<br> OS_X_High_Sierra-Workstation
<br> OS_X_El_Capitan-Workstation
<br> OS_X-Workstation
<br> 
<br> 
After those profiles are disabled, import Apple-Import-1. This will update the existing Apple-Device profile policy to include many other attributes to help identify an Apple device even when a 3rd party dongle is used. 
<br> 
<br> 
<br> 
Then you will upload the second Apple-Import-2 xml file. This will add many new Apple device profiles that will hopefully provide additional granular information on the types of Apple devices connecting to your network. 
<br> 
<br> 
<br> 
The following is a representation of the built-in Apple device profile structure and how the profiles are nested by default: https://github.com/network-node/Updated-Apple-Profiles/blob/master/Old-Apple-Profile-Structure.jpg
<br> 
<br> 
<br> 
After uploading these profiles, the Apple profile structure will be organized as so: https://github.com/network-node/Updated-Apple-Profiles/blob/master/New-Apple-Profile-Structure.jpg
<br> 
