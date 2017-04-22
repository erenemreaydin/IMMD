GaN	FETs	exhibit	in-circuit	switching	speeds	in	excess	of	150V/ns,	compared	to	current	silicon	technology at	
less	than	50V/ns.
However high	di/dt	during	switching accompanies	combined with	parasitic	inductances,	
generates	noise	voltages in	the	circuit. causes-> Continuous Oscillation

####GaN FETs in Parallel Using Drain Ferrite Beads and RC Snubbers for High-power Applications


####Recommended External Circuitry for Transphorm GaN FETs
Adding a drain and a gate ferrite bead is suggested to prevent the oscillation.
Must be mounted very close to the leads.
Parasitic C and L (shown in Figure) acts like a resistor (tank circuit) at a frequency range=[50 200]MHz.
Because parasitic inductance varies according to PCB layout. The FB impedance MUST be at 100 MHz.
FB and Heat Pads specified in the table and the figure.

-Can be expanded w/ further research.

####Drain Voltage and Avalanche Ratings for GaN FETs
GaN FETs do not have a body diode and therefore no physical avalanche mechanism.
Have a dielectric breakdown voltage three times higher than datasheet Vmax.
GaNs are rated for a transient peak Vpeak=1.25*Vcont. And the Vpeak is significantly below voltage levels of failure.

####Characteristics of Transphorm GaN Power FETs


####Printed Circuit Board Layout and Probing for GaN FETs
These can be found from Design Tricks.md

####Designing Hard-switched Bridges with GaN


####PQFN88 Lead-free 2nd Level Soldering Recommendations for Vapor Phase Reflow
