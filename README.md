# life-simulation
Predator-Prey relationships

Download all files into one file.

Run BalancedEcosystemGUI

Press "Start". Select "Default" and press "G0!" if it is the first time.
It will open 2 windows: one for variable control and one for the actual simulation.

Press "Start" to run the simulation.

Selecting "Food" (green), "Prey" (blue), or "Predator" (red) and then click-dragging across the grid will allow you to spawn the selected object in the selected area.
Right click and drag will clear the selected area.
Density can be toggled in the "Density (%)" dropdown menu
Selecting "Pointer On" will allow you to click and drag, with objects only being added or removed at the cursor tip.

Simulation speed can be toggled at the top left.
Start/stop/incremement actions are located at the top right.
Preloaded ecosystems can be selected from the dropdown menu directly below the start/stop/increment. Select the ecosystem and press load.

Variable explanation


Food Spawn Rate: each square has n% chance of spawning food
Food Expiration Rate: after n generations, the food square has a 50% chance of disappearing

*prey and predators have hunger counters. Moving decreases the counter and eating increases the counter*

Food Energy: amount the prey's hunger counter increases from prey eating 1 food square

Prey Hunger: value of the hunger counter that prey start off with

Food Required for Prey Reproduction: Prey must have n hunger or greater to create a new prey animal

Prey Reproduction Period: wait time for prey before they can reproduce again


Prey Energy: amount the predator's hunger counter increases from predator eating 1 prey square

Predator Hunger: value of the hunger counter that predators start off with

Food Required for Predator Reproduction: predators must have n hunger or greater to create a new predator animal

Predator Reproduction Period: wait time for predators before they can reproduce again
