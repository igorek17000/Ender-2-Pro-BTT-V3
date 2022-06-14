# Upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 + TFT35-E3-v3

Use the Pre-Compiled firmware in the main branch to upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 + TFT35-E3-v3 Touch Screen Display / Classic Marlin Dislay.

Or download a copy of Marlin-bugfix-2.1.x from the main Marlin firmware branch: https://github.com/MarlinFirmware/Marlin

and copy over the Configuration.h, Configuration_adv.h, Version.h from here: 

https://github.com/The-300lb-Gorilla/Ender-2-Pro-BTT/tree/main/Code%20Files%20for%20BTT%20SKR%20Mini%20E3%20v2%20Reconfiguration

and make the change listed below in the Platforio.ini file.

Make this change to Line 16 in the Platformio.ini: default_envs = STM32F103RC_btt (Do NOT change anything else)

The click the check mark at the bottom to compile. If you have any issues. Let me know here. 

I have been testing this version of the firmware for over a month now with no issues so far.

Remember, you will need to purchase the three items listed below to do this upgrade. 

You cannot use the stock Main Board and Stock Motor Cables with this firmware.

I have provided links to each item required. (I DO NOT GET PAID FOR ANY LINK I PROVIDE)

This upgrade requires a BTT SKR Mini E3 v2 Main Board and TFT35 E3 v3 bundle. Available on Amazon.com

https://www.amazon.com/dp/B089DBS62S?ref=ppx_yo2ov_dt_b_product_details&th=1

This upgrade also requires NEW Motor Cables. 6 pin to 4 pin, Ender 3 motor cables. Available on Amazon.com

https://www.amazon.com/dp/B07SX11SKB?psc=1&ref=ppx_yo2ov_dt_b_product_details

This upgrade also requires a longer 10 pin to 10 pin LCD ribbon cable. Available on Amazon.com

https://www.amazon.com/dp/B07SR3S2W3?psc=1&ref=ppx_yo2ov_dt_b_product_details

You will need to 3D Print a control box for the TFT35 Touch Screen. There is a folder that contains these files on the main page.

https://github.com/The-300lb-Gorilla/Ender-2-Pro-BTT
