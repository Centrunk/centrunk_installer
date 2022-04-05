# centrunk_installer
The installer script for Hotspots for the Centrunk Trunking Radio System

# How to Use
* Clone the repository and switch into it.
* Make the installer executable by running the following command:
`$ sudo chmod +x centrunk_installer`
* Run the following command to start the install process:
`$ sudo ./centrunk_installer
--voice|--control|--voc 
    --id <EQUIP_ID> 
    --ip <IP_ADDRESS> 
    --rcon <RCON_PORT>
    --uart <PATH_TO_MODEM>
    --channel <UHF|VHF|800|700|900>
    --rfss <RFSS_ID>
    --site <SITE_ID>  
    --sys <SYS_ID>
    --net <NET_ID>
    --nac <NAC_CODE>
    --atg <SUPER_GROUP>
    [--flash]
    --zt <ZEROTIER_ID>
    --chid <CHANNEL_NUMBER>
    --vcn <VOICE_CHANNEL_NUMBER>
    --help
   `
