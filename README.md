# PLEASE READ THE ENTIRE README.MD BEFORE PROCEEDING TO ANY DOWNLOADS
# Upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 + TFT35-E3-v3
# Download Marlin-bugfix-2.1.x(Preconfigured).zip Separately From The Marlin Source Code File Folder, This version of the Marlin source code has already been set up for the BTT SKR Mini E3 + TFT35 to use on an Ender 2 Pro
Step 1: Click on Marlin Source Code Zip Folder

Step 2: Click on Marlin-bugfix-2.1.x.zip file

Step 3: Click on Download or View Raw and the Zip file will download.

Step 4: Once the file has downloaded, move it to the directory you want to keep it in
and extract the file.

Step 5: Using VS-Code, make any additional changes if you so desire, then compile by clicking the check mark at the bottom left.
# Upgrading the TFT35 Touch Screen Firmware

Step 1: Click on the TFT35 Touch Screen Update folder.

Step 2: Click on the TFT35 E3v3 Firmware Update.zip file.

Step 3: Click on Download or View Raw and the Zip file will download.

Step 4: Once the file has downloaded, move it to the directory you want to keep it in
and extract the file.

Step 5: Open the TFT35 E3v3 Firmware Update Folder and copy and paste all of the files in that folder to a BLANK SD CARD.

Step 6: Insert SD Card into the full Size SD Card Slot on the TFT35 Touch Screen unit, and power on the Ender 2 Pro. The TFT35 firmware will then update.

# Additional Options and Information

Use the Pre-Compiled firmware in the main branch to upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 and 

TFT35-E3-v3 Touch Screen Display / Classic Marlin Dislay. You will need to purchase items listed at the bottom in order to do this upgrade.

Or download a copy of Marlin-bugfix-2.1.x from the main Marlin firmware branch: https://github.com/MarlinFirmware/Marlin

and copy over the Configuration.h, Configuration_adv.h, Version.h from here: 
https://github.com/The-300lb-Gorilla/Ender-2-Pro-BTT

and make the change listed below in the Platforio.ini file.

Make this change to Line 16 in the Platformio.ini: default_envs = STM32F103RC_btt (Do NOT change anything else)

The click the check mark at the bottom to compile. If you have any issues. Let me know here. 

I have been testing this version of the firmware for over a month now with no issues so far. 94 prints, no failures.

# You will need to purchase the three items listed below to do this upgrade. (I DO NOT GET PAID FOR ANY LINK I PROVIDE)

You cannot use the stock Main Board and Stock Motor Cables with this firmware.

I have provided links to each item required. 

This upgrade requires a BTT SKR Mini E3 v2 Main Board and TFT35 E3 v3 bundle. Available on Amazon.com

https://www.amazon.com/dp/B089DBS62S?ref=ppx_yo2ov_dt_b_product_details&th=1

This upgrade also requires NEW Motor Cables. 6 pin to 4 pin, Ender 3 motor cables. Available on Amazon.com

https://www.amazon.com/dp/B07SX11SKB?psc=1&ref=ppx_yo2ov_dt_b_product_details

This upgrade also requires a longer 10 pin to 10 pin LCD ribbon cable. Available on Amazon.com

https://www.amazon.com/dp/B07SR3S2W3?psc=1&ref=ppx_yo2ov_dt_b_product_details

# STL Model Files & 3D Printing GCODE Files for the STL Models

You will need to 3D Print a control box for the TFT35 Touch Screen. There is a folder that contains these files on the main page.

https://github.com/The-300lb-Gorilla/Ender-2-Pro-BTT
