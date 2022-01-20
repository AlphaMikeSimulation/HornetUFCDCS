# HornetUFCDCSAppServer
Hornet UFC DCS Companion Windows App

# INSTRUCTIONS:
Video Tutotial:
https://youtu.be/hjC-EsR9tEU

1- Get The App:

Android https://play.google.com/store/apps/details?id=com.embarcadero.HornetUFCDCS

iOS https://apps.apple.com/us/app/hornet-ufc-dcs/id1604694496#?platform=ipad

2-  Download the lastest release of HornetUFCDCSAppServer from the GitHub Repository https://github.com/AlphaMikeSimulation/HornetUFCDCS/releases

3- Unzip The Content somewhere in your hard drive( Desktop Or C Drive For Example)

4- Copy the DCS-BIOS Folder yo your Scripts folder ( C:\Users\USERNAME\Saved Games\DCS.openbeta\Scripts)

5- Edit your export.lua file and add this to the end of the file:    dofile(lfs.writedir()..[[Scripts\DCS-BIOS\BIOS.lua]])

6- Open the HornetUFCDCSAppServer.exe and go to settings and inpiut the IP Address of the Tablet or Phone that you are using for the HORNET UFC DCS App

7- Click in Shutdown Server and Start the server again for the new IP to take effect

8- Open HORNET UFC DCS In your phone or tablet and go to settings, input the IP of the computer that you are using for running DCS World

9- Open DCS World and wait for HornetUFCDCSAppServer status to change status from DCS Not Running To Waiting for DCS...

10- Open any Mission and wait for the HornetUFCDCSAppServer status to change to Connected

11- Now you can control the UFC from your phone or tablet, ENJOY!

# Common Errors

*Error Socket 53 " Connection Reset by Peer"

Solution: Close your app completely and open it again, make sure the IP field in the app settings is filled out correctly and with the correct IP of the computer running DCS

*I can send commands to DCS but the app is no receiving information

Solution: Check the IP in the Settings of the HORNETUFCDCSAPP.exe running in your PC, also make sure your DCS-BIOS is installed correctly and the export.lua is correct

# Credits

Flightpanel DCS-BIOS fork https://github.com/DCSFlightpanels/dcs-bios

jboecker / python-dcs-bios-example https://github.com/jboecker/python-dcs-bios-example
 
emcek / dcspy https://github.com/emcek/dcspy
