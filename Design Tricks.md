## Things to Consider while desinging

#### for POWER
- Low inductive ground -> LARGE GND plane
- Switching node has to be small area
- Ind/Diode/CAP/GaN should be placed as close as possibe (in the Figure 1.a.)

- DC+ output has to be large plane for Decoupling and Heatsink
- Cout should be Fast Film Cap

#### for Gate Drive (Figure 1.b.)
- L must be kept as low as possible
- COM of IC is connected source with WIDE trace
- OUT of IC is connected gate with SHORT WIDE trace
- Decouple with film cap (VCC-COM)
- LARGE GND plane for control circuits to have shortest routes of GND

#### Probe Considerations
- Ground wire is long. Acts like antenna, pick-up noise. Use short wire.
place directly to the device leads.
- Use truly floating oscilloscope.
If gnd is not designed to truly float with min cap but simply disconnected from earth gnd: parasitic cap occurs.
