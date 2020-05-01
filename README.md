# MTK-Smartwatch-custom-firmware-G8-
~~ This is firmware I customized in 2017 that optimizes code and removes the pedometer feature in order to  add custom watch face update via MTK Tool(android app) 
~~ This is an upload of the compiled firmware and upload tools. 

The firmware and the Imei writer for mtk devices.

I've modified the No.1 G8 firmware to support watch faces whilst maintaining the sim function. 

##Ensure Format FAT format and USB Download/Readback are selected under the options menu.##

1. Use the mtk2502FlashTool to apply the firmware by selecting the scatter file in the firmware folder here .This will automaticall load the rest of the required system files.
2. Click the download button.
3 Turn your watch off then connect to pc. This should automatically install the new firmware. 

NOTE: Due to the available memory of the smartwatch, You can only install 1 vxp watchface at a time. This can be done via the mediatek smartwatch app.

You will also note that with a sim card installed, you arent able to make or recieve calls. There is an easy fix for that.. Rewriting the IMEI number. (Please use the IMEI that came with your smartwatch. OR you may use an IMEI from another mtk device which is no longer in use)

1. Open SN-Writer folder and locate 'SN Writer.exe'. 
2. Just follow the screenshots included :) 

Thank you,
Jeffrey Magwaza
