# Upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 + TFT35-E3-v3

Use the Pre-Compiled firmware in the main branch to upgrade the Ender 2 Pro To A BTT-SKR-Mini-E3-v2 + TFT35-E3-v3 Touch Screen Display / Classic Marlin Dislay.

Or download a copy of Marlin-bugfix-2.1.x from the main Marlin firmware branch: https://github.com/MarlinFirmware/Marlin

and copy over the Configuration.h, Configuration_adv.h, Version.h from here: 

https://github.com/The-300lb-Gorilla/Ender-2-Pro-BTT/tree/main/Code%20Files%20for%20BTT%20SKR%20Mini%20E3%20v2%20Reconfiguration

and make the change listed below in the Platforio.ini file.

Make this change to Platformio.ini: default_envs = STM32F103RC_btt (Do NOT change anything else)

This upgrade requires a BTT SKR Mini E3 v2 Main Board and TFT35 E3 v3 bundle. Available on Amazon.com

This upgrade also requires NEW Motor Cables. 6 pin to 4 pin, Ender 3 motor cables. Available on Amazon.com

This upgrade also requires a longer 10 pin to 10 pin LCD ribbon cable. Available on Amazon.com

You will need to 3D Print a control box for the TFT35 Touch Screen. There is a Zip file that contains these files.
