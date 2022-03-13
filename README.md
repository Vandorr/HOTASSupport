# HOTAS Support for Railway games
Unofficially HOTAS Support especially for Train Life: Railway Simulator game :)

[![N|Solid](https://github.com/Vandorr/HOTASSupport/blob/main/images/join-us-on-discord.png)](https://discord.gg/VvsMfJWjyp)

This third-party executable program helps you to use your HOTAS with Railroads Online! game.\
It only works in driving mode because it relies on the UI being there (it emulates a mouse click+move events)!

Use of the program is completely free. 

1️⃣  Download and save program to your hard drive (Find program release on the right side under Releases) 

2️⃣  Download and save premade profile if you want (Find profile release on the right side under Releases) 

3️⃣  Execute Program

4️⃣  If you downloaded Profile, click File -> Profile -> Import Profile. Select downloaded profile file from your computer. 
       If you want to create a new profile click File -> Profile -> New Profile (jump to step 6)
       Before you start configuration load or create new profile!

5️⃣  Click File -> Profile -> "Your Game profile name"

6️⃣  Select Hardware (first controller selected by default)

7️⃣  Start Game. If running, select game window (find name: "Arr")

8️⃣  Configure HOTAS Axis behaviors:
- you have to setup two rows. One for Throttle and one for Break

**FOR THROTTLE:**
- click on + icon on the navigator panel for the first new row
- setup Axis and "Steps count" field to 10 (This controls how many step between min and max value). Press ✅ on the navigator panel
- click on Calibration button on the row (2 step for calibration)
  - STEP 1: move your your HOTAS for throttle zero position (HOTAS half/neutral position). Hit Joytick 1 button. It will save the Hotas value. Hit S (or your throttle- key) in the "Min value" field
  - STEP 2: move your your HOTAS for throttle max position (HOTAS highest position). Hit Joytick 1 button. It will save the Hotas value. Hit W (or your throttle+ key) in the "Max value" field

**FOR BRAKE:**
- click on + icon on the navigator panel for the second row
- setup Axis and "Steps count" field to 10 (This controls how many step between min and max value). Press ✅ on the navigator panel
- click on Calibration button on the row (2 step for calibration)
  - STEP 1: move your your HOTAS for brake zero position (HOTAS half/neutral position). Hit Joytick 1 button. It will save the Hotas value. Hit D (or your brake- key) in the "Min value" field
  - STEP 2: move your your HOTAS for brake max position (HOTAS lowest position). Hit Joytick 1 button. It will save the Hotas value. Hit E (or your brake+ key) in the "Max value" field
 
## Antivirus warning
The program needs to monitoring your Joystick/HOTAS positions and send mouse click or keystrokes for a game window. This is not something regular programs do, so your antivirus program can detect and gives you a false positive result!

**Requirements if you want to build from the source code:**
- Delphi 10.3
- DevExpress components (TcxGrid, input fields)
- Winsoft's DirectX Joystick Component


## SCREENSHOT

![image](https://user-images.githubusercontent.com/990379/158072940-b34a78c1-a890-4564-b95c-056d971c1362.png)

## SUPPORT/DONATION

Use of the program is completely free. 
If you would like to support the development, you can do it here:\
[![N|Solid](https://github.com/Vandorr/HOTASSupport/blob/main/images/donate-through-paypal.png)](https://shorturl.at/bryT6 )

**Thank you, I appreciate it!**
