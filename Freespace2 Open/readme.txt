Config-pack for using Freespace2 (retail and FSO) with the Steel Battalion-Controller and Shoot-Speech-recognition
(C) StingerAJ

Introduction:

Hello,

this config-pack will enable you to play FreeSpace2_Open using the "Steel Battalion"-controller.
For this you need to install the vtchid-driver v0.2.1 from the website http://www.tamanegi.org/prog/vtchid/.
Also included is a pilot-profile with preconfigured controls for the sticks, pedals and buttons.
The Comm-Buttons, the Comm Dial, the toggleswitches and the Sight-Change-stick are programmed in
the vtchid-profile freespace2.sdp.
Optional: also included is an enhanced profile for Speech-Recognition-Tool Shoot 1.6.4.
See http://clans.gameclubcentral.com/shoot/ for further details on how to install and use this.

Installation:

To install this config-pack, do the following:
- Install vtchid 0.2.1 Binary from http://www.tamanegi.org/prog/vtchid/
- Copy the directory data, contained in the fs2-pilot-profile, to the Freespace2-directory
- Optional: If desired, install Shoot 1.6.4 from http://clans.gameclubcentral.com/shoot/downloads.php
  and load the included shoot-profile.
  
Usage:

- Connect the controller to your PC using a "SmartJoy X2 USB"-cable or a selfbuilt-one.
- Install now the vtchid-drivers if you not already did it.
- Load freespace2.sdp into VTCHID (control panel->game controllers->VT controller->load),
  then press Apply, then OK.
- Optional: If desired, start up Shoot 1.6.4 and load the shoot-profile Freespace-the-great-war.xml.
  You can activate the speech-recognition in-game with the Sight-Change-button (press the stick).
  It's a "Hold-to-Speech"-button-config. You can trigger multiple commands while pressing the button. 
- Create a new pilot by cloning the pilot "VTCHIDPILOT" and select it for play.
- Make yourself familiar with the controller-assignments with the "Search"-function in the Control-Config.

Special notes for the Comm-Section of the controller:
- For wing-selection switch the toggle "OXYGEN SUPPLY SYSTEM" to LOWER position,
  UPPER position is reserved for future use (fine-grained per-ship comm-channels).
- Use the Comm Dial to select the targets of your order:
  - Comm Dial set to WEST (Channel 1): All Fighters
  - Comm Dial set to NORTHWEST (Ch 2): First Wing
  - Comm Dial set to NORTH     (Ch 3): Second Wing
  - Comm Dial set to NORTHEAST (Ch 4): Third Wing
  - Comm Dial set to EAST      (Ch 5): Fourth Wing
- The red Comm-Buttons send the order to the selected wing depending on the setting
  of the Comm Dial:
  Comm Dial is on W/NW/N/NE:
  - Comm-Button 1: Attack Target
  - Comm-Button 2: Disable Target
  - Comm-Button 3: Disarm Target
  - Comm-Button 4: Attack Subsystem
  - Comm-Button 5: Protect Target
  Comm Dial is next to W/NW/N/NE (clockwise):
  - Comm-Button 1: Ignore Target
  - Comm-Button 2: Form on my wing
  - Comm-Button 3: Cover me
  - Comm-Button 4: Engage enemy
  - Comm-Button 5: Depart
- Orders "Resupply" and "Reinforcements" are currently not assigned to the Comm-Buttons
  ("Resupply" can be activated with the speech-recognition from the Shoot-profile)
  
Shoot-profile Freespace-the-great-war.xml handles the following functions
(most important listed here, for details check the profile-file):
- Comm-orders for all fighters ("Attack target!") or individual wings ("First wing attack target!", "Second wing cover me!")
- Order Supply-ship to Resupply&Repair ("Resupply!")
- Targeting ("Target turret!")
- Power-distribution ("Full power to engines/shields/weapons!"), ("Normal energy!")
- Shield-distribution ("forward/left/right/rear shield!"), ("equalize!")


For discussion about this visit the following HLP-Forum-Thread:
http://www.hard-light.net/forums/index.php/topic,64917.0.html
