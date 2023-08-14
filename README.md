# Flatbox-rev-5-RGB Dang Remix
![1](https://github.com/dangk1/Flatbox-rev-5-RGB/assets/57189623/eeb3adbc-68bf-43e7-81c9-a4440a0ae829)
![2](https://github.com/dangk1/Flatbox-rev-5-RGB/assets/57189623/89824cba-6d75-44dd-99fa-9608372f00d1)

This is a remix of a remix version of the Flatbox Rev 5 RGB by TheTrain and jfedor from the Openstick Community repository 

Link to repo: https://github.com/OpenStickCommunity/Hardware/tree/main/Flatbox%20Rev%205%20RGB

This remix version adds an extra button to the layout for easy acces with right the thumb primarily made for SF6 (drive impact/parry). I also lowered the placement of P4+K4 buttons because it suits my finger placement more. (I like noir but that would end up a bit too low on the Flatbox)

For compatibilty with the original firmware I did not mess with the routing of the pins so updating the Flatbox rev 5 RGB firmware from the GP2040-CE website will cause no functionality problems. 
However because of the extra button there are 2 more leds that need to be added to the data chain in the configuration. 
I will provide a screenshot with the correct settings in the web configuration to make it functional.
The extra right thumb button is routed to R3 and the tactile switch which had R3 previously (outer right tactile switch) is now routed to Pin 1 on the RP2040 zero. 
Pin 1 is unused and not activated in the firmware of the Flatbox rev 5 RGB. U can assign anything u want manually in the web configuration of GP2040-CE. (Turbo?).

For the case I used the acrylic Flatbox from Ultra Arcade repository and modified the top 2 panels to fit the button layout. I think this case only fits Punk workshop/Sino button caps so I used those.

Link to repo : [
](https://github.com/Ultra-Arcade/open-ua-cnc/tree/main/Case%20Designs/Open%20Ultra%20Arcade%20CNC%20-%20Flatbox)https://github.com/Ultra-Arcade/open-ua-cnc/tree/main/Case%20Designs/Open%20Ultra%20Arcade%20CNC%20-%20Flatbox
