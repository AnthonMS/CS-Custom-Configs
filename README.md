<h1> CS2 Config </h1>

To autorun it when cs2 is started through steam, go to steam, right click CS2, click properties and add `+exec autoexec.cfg` to LAUNCH OPTIONS.
To run it manually when changes are made, open console and run command `exec autoexec`

Default Keybinds and [Settings](#settings) are added to this so I can easily switch between accounts and run this config to get the same settings.


My keybinds are made for Scandinavian 60% Keyboard layout. 

| Key	(Scand. Keyboard)	| Function															|
| ------------------------- | ----------------------------------------------------------------- |
| **Movement Keys**         |                                                                   |
| **W**                     | Forward                                                           |
| **A**                     | Strafe Left                                                       |
| **S**                     | Backwards                                                         |
| **D**                     | Strafe Right                                                      |
| **MWHEELDOWN**            | Jump                                                              |
| **SHIFT**                 | Walk                                                              |
| **CTRL**                  | Crouch                                                            |
| **Weapon Keys**           | ----------------------------------------------------------------- |
| **1**                     | Slot1                                                             |
| **2**                     | Slot2                                                             |
| **3**                     | Slot3                                                             |
| **4**                     | Slot4                                                             |
| **5**                     | Slot5                                                             |
| **6**                     | Slot6                                                             |
| **7**                     | Slot7                                                             |
| **8**                     | Slot8                                                             |
| **9**                     | Slot9                                                             |
| **0**                     | Slot10                                                            |
| **E**                     | Use                                                               |
| **MOUSE1**                | Attack1                                                           |
| **MOUSE2**                | Attack2                                                           |
| **R**                     | Reload                                                            |
| **Q**                     | Last Equipped                                                     |
| **G**                     | Drop                                                              |
| **F**                     | Inspect Weapon                                                    |
| **B**                     | Buymenu                                                           |
| **H**                     | Slot12 / Healthshot                                               |
| **T**                     | Spraymenu                                                         |
| **UI Keys**               | ----------------------------------------------------------------- |
| **TAB**                   | Scoreboard                                                        |
| **M**                     | Team Menu                                                         |
| **-** / **+**             | Toggle Console                                                    |
| **Comm. Keys**            | ----------------------------------------------------------------- |
| **MOUSE3**                | Ping (Mousewheel Click)                                           |
| **Y**                     | Message All                                                       |
| **U**                     | Message Team                                                      |
| **Chat Wheel Keys**       | ----------------------------------------------------------------- |
| **Z**                     | Radialmenu                                                        |
| **X**                     | Radialmenu2                                                       |
| **C**                     | Radialmenu3                                                       |

| Key	(Scand. Keyboard)	| Function															|
| ------------------------- | ----------------------------------------------------------------- |
| **Buy Binds** 		    | 																	|
| **,**                     | Buy Vest                                                          |
| **.**                     | Buy Vest & Helmet                                                 |
| **RALT**                  | Buy Diffuser                                                      |
| **[** / **Å**             | Buy Dual Berettas                                                 |
| **'** / **Ø**             | Buy p250                                                          |
| **/** / **-**             | Buy Tec9 / CZ / FiveSeven                                         |
| **RCTRL**                 | Buy Deagle                                                        |
| **=** / **´**             | Buy Nova                                                          |
| **]** / **¨**             | Buy XM1014                                                        |
| **\** / **'**             | Buy MAC10 / MP9                                                   |
| **RSHIFT**                | Buy P90                                                           |
| **LEFTARROW**             | Buy PP-Bizon                                                      |
| **BACKSPACE**             | Buy Galil / Famas                                                 |
| **ENTER**                 | Buy AK47 / M4A4                                                   |
| **UPARROW**               | Buy Scout                                                         |
| **DOWNARROW**             | Buy AWP                                                           |
| **INS**                   | Buy Flashbang                                                     |
| **DEL**                   | Buy Smoke Grenade                                                 |
| **PGUP**                  | Buy HE Grenade                                                    |
| **PGDN**                  | Buy Molotov / Incendiary                                          |
| **RIGHTARROW**            | Buy Decoy Grenade                                                 |

When holding Mouse5 (Forward mouse button), it will switch to secondary keybinds and when let go it will switch back to primary.

| Key	(Scand. Keyboard)	| Function															|
| ------------------------- | ----------------------------------------------------------------- |
| **Primary Binds** 		| 																	|
| **1**                     | Slot1     /   Primary                                             |
| **2**                     | Slot2     /   Secondary                                           |
| **3**                     | Slot3     /   Knife/Zeus                                          |
| **4**                     | Slot4     /   Cycle Grenades                                      |
| **G**                     | Drop                                                              |
| ------------------------- | ----------------------------------------------------------------- |
| **Secondary Binds** 		| 																	|
| **1**                     | Slot6     /   HE Grenade                                          |
| **2**                     | Slot10    /   Molotov                                             |
| **3**                     | Slot8     /   Smoke                                               |
| **4**                     | Slot7     /   Flashbang                                           |
| **G**                     | Drop C4                                                           |



### Settings:
// Default Settings:
- volume 0.6
- snd_menumusic_volume 0.04
- snd_roundstart_volume 0
- snd_roundaction_volume 0
- snd_roundend_volume 0.16
- snd_mvp_volume 0.2
- snd_tensecondwarning_volume = 0.04
- snd_deathcamera_volume 0.16
- fps_max 400
- fps_max_ui 200
- cl_radar_scale 0.700000
- cl_radar_always_centered 0
- cl_use_opens_buy_menu 0
- developer 1             			// Console now outputs in top left corner as well
- con_enable 1
- cl_color 2
- cl_teamcounter_playercount_instead_of_avatars 1

- cl_interp_ratio 1
- cl_interp 0.015625                  // Set to 0.03125 for less stable connection
- cl_showfps 0                        // Set to 1 to enable it
- r_fullscreen_gamma 2.200000

// Crosshair
- cl_crosshair_drawoutline 0
- cl_crosshair_recoil 0
- cl_crosshair_outlinethickness 1.035
- cl_crosshair_friendly_warning 1
- cl_crosshair_t false
- cl_crosshairalpha 255
- cl_crosshaircolor 5
- cl_crosshaircolor_b 0
- cl_crosshaircolor_g 0
- cl_crosshaircolor_r 255
- cl_crosshairdot 0
- cl_crosshairgap -3.466554
- cl_crosshairgap_useweaponvalue false
- cl_crosshairsize 1.982854
- cl_crosshairstyle 4
- cl_crosshairthickness 0.585305
- cl_crosshairusealpha 1





Notes:

slot0: ???
slot1: primary weapon
slot2: secondary weapon
slot3: knife
slot4: cycle grenades
slot5: c4/bomb
slot6: hegrenade
slot7: flashbang
slot8: smokegrenade
slot9: decoy
slot10: molotov/incgrenade
slot11: zeus
slot12: healthshot


+turnleft:  Turn Left
+turnright: Turn Right





Special Keys:
Key on keyboard  :   CS Keycode
Ø                :   O_WITH_STROKE
Æ                :   AE
Å                :   A_WITH_RING_ABOVE
´                :   =
+                :   -
¨                :   ]
'                :   \
RSHIFT           :   RSHIFT
RCTRL            :   RCTRL
RALT             :   RALT
-                :   /
.                :   .