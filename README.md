# 2-Factor-Auth-Lock
A lock that uses multi pin per stack system to prevent picking, this works by surrounding one specific pin per pin stack with others of varying sizes. When someone tries to pick the lock, it will be "picked" (to the first stage), then the key and rotator will stop moving because those specific pins need to be at a specific height (in the secondary rotator, they must be 4mm tall pins). This creates variance and adds a guessing factor, turning a normal key lock into a picking method that works similar to guessing every possible combo on a keypad, removing intuition and requiring the lock picker to take a long trial and error method. More pins can be added per stack and more stacks can be added in order to make the lock harder to pick, to a point where it might as well be broken. This should be considered more difficult than guessing a keypad as the "pressing a button" requires you to set each pin at a different height. As picking is possible it is not intuitive and hopefully require pure luck. If you find a fault in this design (other than the mechanism keeping the shackle locked, there are already methods to prevent blunt force on the lock from opening it which can be implemented here) if you have issues or think you picked it please reach out at my website: https://liamnmbr1.github.io/

## Bill of Materials
| Part Name | # of Pieces | Purpose |
| :--- | :--- | :--- |
| Casing | x1 | this is the main casing of the lock everything fits into/attaches to |
| primary_rotator | x1 | this is the back of the primary rotator(its main component), the cylinder that holds pins and fits into the secondary rotator |
| primary_piece_rotator | x4 | these attach to each other and the primary_rotator creating a chain, each one has a slot to hold a pin |
| secondary_rotator | x1 | the outer shell of the primary rotator, it has a hole for a paperclip to be inserted and connect a rubber band from it to the Casing, this is needed to reset it to its main vertical state |
| plug_secondary_rotator | x1 | this is the pin that fits into the shackle end of the casing, it is used to hold the secondary rotator vertical and allow it to rotate when the primary rotator is turned ~78 degrees |
| Cap_shackle | x1 | the end cap of the casing on the shackle end, this holds the locking components and needs to be added to seal components like the plug_secondary_rotator and slider_shackle |
| slider_shackle | x1 | this is the component that prevents the shackle from opening(locks the lock), it fits into a slot in the cap_shackle |
| Shackle | x1 | the shackle fits into the casing and the cap_shackle as the part of the lock that secures whatever item you want |
| Shackle_pins | x1 | two pins in one file to keep the shackle in the lock, they are extra long so you can remove the shackle and take apart the lock after assembly |
| Keyhole_cap | x1 | the cap for the casing on the keyhole side, I recommend adding this last as you can still adjust pin settings and rotators before adding it |
| Key to unlock | x1 | a key I designed to work, as I used 2mm tall pins, it won't work for most pin combinations you try, but is a good reference |
| Spring_cap | x1 | covers the pinholes at the top of the casing, but the pins won't fall out without it because there is a bottleneck in the casing to prevent pins from being pushed too high and bypassing the secondary_rotator |
| Pin_4mm | x5 | pins that fit into the secondary rotator to create a correct passcode |
| Pin_6mm | any | pins used to create incorrect combos in pin heights but have the primary rotator turn |

## Recommendations for replicating
  If you plan to print this I recommend you create pins of different heights (8mm or 5mm) and create your own key with those heights, when i originally made this I used 2mm pins but they kept slipping out of the track of the primary rotator. It should be easy to modify the key's solidworks file for any pin heights you want with one measurement change per pin stack you want to change.
  You will also need a cut paperclip(or something similar) and a strong small rubber band to add into the secondary rotator, connecting it to the shaft sticking out of the casing, this ensures the secondary rotator returns to a vertical position after it is turned to unlock the lock.
  I also had no springs so there are lots of tubes sticking out of the lock so you can insert a paperclip or stick to add tension(this should make any attempted picking easier, although you shouldn't be able to pick it anyways unless you know the proper pin heights, but good luck)
  When inserting pins into pin stacks I recommend adding them into the primary rotator and casing (none in secondary rotator) so you can insert the rotators into each other, then into the casing(have the casing pin hole side down so nothing falls), this ensures everything stays together. Also make sure the opening of the primary rotator is facing the pin holes in the secondary rotator, it can be inserted upside down but has to be removed and fixed.
