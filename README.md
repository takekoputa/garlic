# garlic

Not so many moons ago, I started working on gem5, a hardware simulation.
Useful simulations usually take hours to moons to finish while there is almost no
indicator of the progress of the simulation.
One way to keep track of the progress is to observe its outputs, which include
the guest stdout and stderr (which are written to `system.pc.com_1.device`).

This application is intended to keep track of when each line of that file is outputted
relative to when the simulation starts.
