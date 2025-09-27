Maplestory Spell Trace Expected Cost Calculator

This is a simple, single-file web application designed to help Maplestory players calculate the expected Spell Trace and Meso cost required to successfully fully enhance an item from scratch.
🛠️ Calculation Logic

The calculator determines the Expected Cost Per Successful Slot (E_slot) using the following formula:
Eslot​=(Success Chance (P)Spell Traces per Attempt​)+((Success Chance (P)1​)−1)×Clean Cost

This formula accounts for both the traces spent on successful attempts and the average number of traces spent cleaning failures. The total expected cost is then simply:
Total Cost=Eslot​×Total Slots

The Meso cost is calculated by multiplying the total traces by the user-inputted Meso cost per trace.
