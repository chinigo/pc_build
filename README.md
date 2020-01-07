# Tools
Screwdrivers
Hex sockets
Paste spreader
Needle nosed pliers
Plumber's wrench
Tube cutter

# Hardware
Motherboard standoffs
Zip ties
Power supply PCM jumper
T joint compression fitting
Spigot w/compression fitting
2x fill port (one for fill, one for drain)

# Supplies
Thermal paste
CPU cooler mount
Air cooler (CPU likely ships with stock cooler)
1 gal distilled water to flush loop
1 gal coolant, or addl 1 gal distilled water + biocide + anti-corrosive
White vinegar (I think, for a copper radiator)

# Steps

## Dry fit
Mount all the components in case to get a sense of possible layouts, fan placements, clearances, tube routing, cable routing, etc.

## Core components test
Mount motherboard in case
Mount CPU
Mount air cooler
Seat one stick RAM
Hook up PSU temporarily
Boot test (success = BIOS screen)

## Additional components test
Seat NVMe
Seat GPU
Seat all RAM
Mount SSD
Run cables
Hook up PSU temporarily
Boot test with video hooked up to GPU (success = BIOS aware of drives)

## Mount GPU water block
Remove factory case, disconnect fan
Cut & place thermal pads
Spread thermal paste
Mount water block
Connect compression fittings
Seat GPU

## Mount CPU water block
Remove air cooler
Spread thermal paste
Connect compression fittings
Mount water block

## Flush radiator
Outside of case (or temporarily mounted, whatever's easier), run tubing between radiator and pump/reservoir. Plumb in a T joint, a spigot, and a drain tube.
Mount motherboard, CPU w/air cooler, 1 stick RAM.
Connect power supply to motherboard, and pump to CPUFAN1.
Fill reservoir with cleaning fluid. (Dilute acetic acid maybe, depending on radiator metal.)
Boot to BIOS, run pump for an hour or so.
Flush loop with distilled water until clear. Open spigot, drain most fluid with pump (but never run pump dry!!), refill w/distilled water, rinse, repeat.
Drain loop most of the way with pump. Drain loop completely by tilting and shaking. (Never run pump dry!!)
Disconnect everything.

## Cooling system
Remove all components except CPU & 1 stick RAM
Mount reservoir & pump
Screw fill port and drain port into case
Mount radiator fans to radiator
Mount additional case fans
Mount radiator to case
Cut & run flex tubing between components. Hand tighten compression fittings only, but tighten them good!
Plumb spigot to drain port (if pump has one), or add a T joint in the outlet line (if not).
Plumb spigot outlet to drain port.
Plumb fill port to top of reservoir.
Fill reservoir via fill port.
Boot to BIOS, run pump for leak test.

## Full system test
Seat all components again.
Run cables. Don't lock them down yet.
Connect video output to onboard, disconnect GPU power (you don't want to run it until you can monitor its temp in case you fucked up GPU water block).
Boot to BIOS.
Configure fan curves from BIOS.
Confirm BIOS aware of all components.
Keep an eye on CPU temps while you're poking around. They should be nominal, this is as low a load as system will ever encounter.

## Install Windows
Install Windows.
Install latest Radeon drivers.
Install FPSMonitor, copy Chinigo's config.
Install passmark or something to generate a buncha CPU and GPU load

## GPU test
Connect GPU power, connect video out to GPU.
Boot to Windows.
Monitor GPU & CPU temps as you run the full Passmark suite. Slam it with load to establish temps under max thermal load.

## Overclock GPU
I got a 4% overall boost to clock speed without too much effort. Surprisingly straightforward.
Confirm temps are acceptable w/increased thermal load due to overclocking.
