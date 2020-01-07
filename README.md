# Purpose

- Present an opinionated take on a water-cooled, medium/high-end gaming PC.
- Solicit feedback from nerd friends on this opinionated take.
- Act as a detailed parts list for McGarvey's new gaming PC build.
- Avoid some of the obvious mistakes Chinigo made during his recent gaming PC build.
- Act as checklist for the tools Chinigo will need to loan to McGarvey.
- Act as checklist for steps to actually build the thing.

# Parts

## Components

| **Component**       | **Model**     | **Image**                                                                                                                                                            | **Notes**                                                                                                                                                                                                                                                      |
|---------------------|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Case                | *TBD*         |                                                                                                                                                                      | Bigger is better, really. More space for ambient air cooling, easier to work in, prettier when it's not cluttered. Look for a case w/a dedicated fill & drain port, or plan on drilling them into the case w/a hole saw.                                       |
| Power Supply        | *TBD*         |                                                                                                                                                                      | Spring for a "fully modular" PSU, which will let you remove power cables you don't need. In practice, most are unusued. Choose capacity by adding TDP of CPU, GPU, pump, fans, and adding a healthy amount of headroom. Overcapacity is better than under!     |
| Motherboard         | *TBD*         |                                                                                                                                                                      | Verify compatibility w/CPU socket and RAM spec. Make sure fan headers support PWM (many have a dual PWM/DC mode you can toggle from BIOS).                                                                                                                     |
| CPU                 | *TBD*         |                                                                                                                                                                      |                                                                                                                                                                                                                                                                |
| GPU                 | *TBD*         |                                                                                                                                                                      |                                                                                                                                                                                                                                                                |
| RAM                 | *TBD*         |                                                                                                                                                                      | Buy in pairs, stick with the same model for everything.                                                                                                                                                                                                        |
| Fast storage        | *TBD*         |                                                                                                                                                                      | Motherboard-socketed NVMe storage is fastest thing on market. Put games on this storage device to minimize loadtimes, and put OS/etc on "slower" SSD or mass storage.                                                                                          |
| Mass storage        | *TBD*         |                                                                                                                                                                      | Or also an NVMe-only build is practical! You might skip SSDs/HDDs altogether, and not have to run *any* SATA power + data cables for a super clean build.                                                                                                      |
| Case fans           | *TBD*         |                                                                                                                                                                      | Bigger radius = more airflow at given RPM (and thus sound level). You want a buncha big, slow fans. Get PWM-controlled instead of DC-controlled.                                                                                                               |
| Radiator fans       | *TBD*         |                                                                                                                                                                      | If you have a choice, go with "high static pressure" instead of "high airflow." But otherwise same advice stands as for case fan: big + slow.                                                                                                                  |
| Fan controller      | *TBD*         | [![Fan controller](images/fan_controller.jpg)](https://www.newegg.com/p/376-001Y-00003?Description=fan%20controller&cm_re=fan_controller-_-9SIACJF6HF8769-_-Product) | You'll probably end up having more fans than motherboard fan headers. A controller lets you signal multiple fans from same header. Gotta be PWM instead of DC as well.                                                                                         |
| Reservoir           | *TBD*         |                                                                                                                                                                      | Needs to be compatible with pump. Typically, reservoir drains directly into pump, and often you can buy the two as a package.                                                                                                                                  |
| Pump                | *TBD*         |                                                                                                                                                                      |                                                                                                                                                                                                                                                                |
| Radiator            | *TBD*         |                                                                                                                                                                      | Bigger = more cooling capacity. Fans mount directly to radiator to force air through fins; tight fin spacing means high static pressure gradient, which can influence fan choice.                                                                              |
| CPU water block     | *TBD*         |                                                                                                                                                                      | Replaces stock air cooler mounted on top of CPU. Presses metal plate tightly against CPU's IHS, flushes coolant across other side of that plate. Presents compression fittings.                                                                                |
| GPU water block     | *TBD*         |                                                                                                                                                                      | Replaces housing of GPU, presses a metal plate tightly against hot GPU components, flushes coolant across other side of that plate. Presents compression fittings.                                                                                             |


## Fittings + Plumbing

All fittings need to match your tubing diameter (the component-side is a standard size, don't worry about it).

| **Fitting**            | **Model**     | **Image**                                                                                                                                                                                                                                                                                                                                                                         | **Notes**                                                                                                                                                             |
|------------------------|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Flex tubing            | *TBD*         | [![Flex tubing](images/flex_tubing.jpg)](https://www.primochill.com/collections/retail-tubing-1-2-x-3-4/products/primoflex-advanced-lrt-flexible-tubing-1-2in-id-x-3-4in-od-retail-bundle-10ft-pack-crystal-clear)                                                                                                                                                                | Get bigger tubing: larger ID = higher fluid volume = lower temps, thicker tube wall = less likely to kink. I'd go with 1/2" ID x 3/4" OD.                             |
| Compression fittings   | *TBD*         | [![Straight fitting](images/straight_fitting.png)](https://www.primochill.com/collections/flex-sx-1-2-x-3-4/products/primochill-1-2in-x-3-4in-flexsx-series-compression-fitting-silver-nickel) [![Angled fitting](images/angled_fitting.jpg)](https://www.primochill.com/collections/rotary/products/bykski-g-14-male-to-female-45-degree-rotary-elbow-fitting-silver-b-rd45-x)   | Available in straight, 45°, and 90° angles. The rotary angled ones are nice because you can adjust tube orientation by spinning fitting. Mix and match to fit case.   |
| T joint                | *TBD*         | [![T joint](images/t_joint.jpg)](https://www.ekwb.com/shop/ek-af-t-splitter-3f-g1-4-black-nickel)                                                                                                                                                                                                                                                                                 | Needed to plumb in spigot, if pump doesn't have dedicated outlet.                                                                                                     |
| Spigot                 | *TBD*         | [![Spigot](images/spigot.png)](https://www.primochill.com/products/primochill-female-to-female-g-1-4-drain-ball-valve-silver?_pos=2&_sid=4259efa71&_ss=r)                                                                                                                                                                                                                         | Open to drain loop.                                                                                                                                                   |
| Fill port              | *TBD*         | [![Fill port](images/fill_port.jpg)](https://www.primochill.com/products/primochill-fillport-pass-thru-fitting-silver-nickel?_pos=5&_sid=a7c82d743&_ss=r)                                                                                                                                                                                                                         | Same as drain port.                                                                                                                                                   |
| Drain port             | *TBD*         | [![Drain port](images/fill_port.jpg)](https://www.primochill.com/products/primochill-fillport-pass-thru-fitting-silver-nickel?_pos=5&_sid=a7c82d743&_ss=r)                                                                                                                                                                                                                        | Same as fill port.                                                                                                                                                    |
| Fill/drain port cap    | *TBD*         | [![Fill/drain port cap](images/fill_port_cap.png)](https://www.primochill.com/products/primochill-g-1-4-knurled-brass-plug-silver?_pos=8&_sid=d6b51cda0&_ss=r)                                                                                                                                                                                                                    | For when you're not filling or draining loop. Some fill ports come with cap included.                                                                                 |


## Tools

| **Tool**              | **Purpose**                             | **Image**                                                                                                                                                                                           | **Chinigo has?**   | **Notes**                                                                                                                                            |
|-----------------------|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Screwdrivers          | General purpose                         |                                                                                                                                                                                                     | Y                  | Most screws are Phillips head, but you'll run into the occasional flathead. Magnetized tips are clutch to get screws into and out of tight corners.  |
| Hex sockets           | Motherboard standoffs, etc.             |                                                                                                                                                                                                     | Y                  |                                                                                                                                                      |
| Allen wrenches        | GPU screws, misc case screws            |                                                                                                                                                                                                     | Y                  |                                                                                                                                                      |
| Needle nosed pliers   | Pulling wires, etc.                     |                                                                                                                                                                                                     | Y                  |                                                                                                                                                      |
| Paste spreader        | Applying thermal paste to CPU and GPU   | [![Paste spreader](images/paste_spreader.jpg)](https://www.newegg.com/p/2S7-00MH-0EMK7?Description=paste%20spreader&cm_re=paste_spreader-_-2S7-00MH-0EMK7-_-Product)                                | Y                  |                                                                                                                                                      |
| Plumber's pliers      | Gripping compression fittings           | [![Plumber's pliars](images/plumbers_pliers.jpg)](https://www.harborfreight.com/plumbing/plumbing-tools/plumber-s-pliers/8-in-high-performance-groove-joint-pliers-64465.html)                      | Y                  |                                                                                                                                                      |
| Tube cutter           | Cutting tubes                           | [![Tube cutter](images/tube_cutter.jpg)](https://smile.amazon.com/gp/product/B07CTHZL1J/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                                                            | Y                  |                                                                                                                                                      |
| Flush cut snips       | Cutting zip ties                        | [![Flush cut snips](images/flush_cut_snips.jpg)](https://smile.amazon.com/Kaisi-Diagonal-Cutting-Precision-Electronics/dp/B076BP21CC/ref=sr_1_4?keywords=flush+cut+snip&qid=1578426197&s=hi&sr=1-4) | N                  |                                                                                                                                                      |


## Hardware

| **Hardware**           | **Purpose**                                                            | **Image**                                                                                                                                     | **Chinigo has?**   | **Notes**                                                                                                                                            |
|------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Motherboard standoff   | Supporting NVMe drive                                                  | ![Motherboard standoffs](images/motherboard_standoffs.jpg)                                                                                    | Y                  | Likely comes w/the drive.                                                                                                                            |
| Zip ties               | Cable routing                                                          |                                                                                                                                               | Y                  | Get more than you need, you'll end up throwing a bunch away. I like using twist ties to stage everything, and then lock it all down with zip ties.   |
| Various screws         | You'll inevitably find you need some screw you don't have              |                                                                                                                                               | Y                  | I've got a little kit now, I'll bring it over.                                                                                                       |
| CPU cooler mount       | Squeezes CPU water block against CPU                                   |                                                                                                                                               | N                  | Will likely come with water block.                                                                                                                   |
| CPU air cooler         | Used to test CPU before water cooling loop is complete                 |                                                                                                                                               | N                  | CPU will likely come with stock cooler. (Tho, e.g. my 3950x did not.)                                                                                |
| PWM cable extensions   | So you don't have to compromise fan cable routing due to short cables. | [![PWM cable extensions](images/pwm_cable_extensions.jpg)](https://www.amazon.com/extension-cable-Black-Sleeving-FC44PWM-12BKS/dp/B0055OLY88) | N                  |                                                                                                                                                      |


## Supplies
| **Supply**                              | **Purpose**                                                               | **Chinigo has?** | **Notes**                                                                                                                                                                      |
|-----------------------------------------|---------------------------------------------------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Thermal paste                           | Ensure good thermal transfer between CPU/GPU's IHS and cooler/water block | Y                | Hopefully you're not slopping enough of it on to short a component, but get a nonconductive one anyhow just to be safe. Spreading the paste is a bit of an art.                |
| Q tips                                  | Cleaning thermal paste off chip                                           | Y                | You'll need to strip the thermal paste off at least once – when you temporarily mount the CPU's air cooler, before you've tested your GPU water cooling. Also if you screw up. |
| Paper towels                            | Cleaning thermal paste                                                    | N                | Get your own damned paper towels.                                                                                                                                              |
| Gauze                                   | Cleaning thermal paste                                                    | N                | Good for a final pass because, unlike paper towels, gauze doesn't leave any lint behind.                                                                                       |
| Rubbing alcohol                         | Cleaning thermal paste                                                    | Y                | Ok, now this I have way too much of. I accidentally bought four cases of rubbing alcohol off Amazon instead of four bottles.                                                   |
| 1 gal distilled water                   | Flush loop                                                                | N                |                                                                                                                                                                                |
| Dilute acetic acid (white vinegar)      | Flush loop                                                                | N                | For a copper radiator. [Other metals may require different solvents](https://www.ekwb.com/blog/how-to-clean-water-blocks/).                                                    |
| Dilute sodium bicarbonate (baking soda) | Neutralize acetic acid                                                    | N                | Don't want that vinegar hanging around to corrode after your rinse.                                                                                                            |
| 1 gal premixed coolant                  | Coolant                                                                   | N                | Don't mix and match: different brands may have incompatible chemistries.                                                                                                       |
| *OR* mix your own!                      | Coolant                                                                   | N                | Distilled water + biocide + anti-corrosive.                                                                                                                                    |


# Steps

## 1. Dry fit
1. Mount all the components in case to get a sense of possible layouts, fan placements, clearances, tube routing, cable routing, etc.

## 2. Core components test
1. Mount motherboard in case.
1. Mount CPU.
1. Mount air cooler.
1. Seat one stick RAM.
1. Hook up PSU temporarily.
1. Boot test (success = BIOS screen).

## 3. Additional components test
1. Seat NVMe.
1. Seat GPU.
1. Seat all RAM.
1. Mount SSD.
1. Run cables.
1. Hook up PSU temporarily.
1. Boot test with video hooked up to GPU. (Success = BIOS aware of drives and video comes out of GPU.)

## 4. Mount GPU water block
1. Remove factory housing, disconnect fan.
1. Clean off factory thermal paste.
1. Cut & place thermal pads.
1. Spread thermal paste.
1. Mount water block.
1. Connect compression fittings.
1. Seat GPU.

## 5. Mount CPU water block
1. Remove air cooler.
1. Clean off old thermal paste.
1. Spread thermal paste.
1. Connect compression fittings.
1. Mount water block.

## 6. Flush radiator
1. Outside of case (or temporarily mounted, whatever's easier), run tubing between radiator and pump/reservoir. Plumb in a T joint, a spigot, and a drain tube.
1. Mount motherboard, CPU w/air cooler, 1 stick RAM.
1. Connect power supply to motherboard, and pump to CPUFAN1.
1. Fill reservoir with dilute acetic acid (5% - 10%). Warm is good, but not necessary: time can substitute for temperature. Def don't want boiling!
1. Boot to BIOS, run pump for an hour or so.
1. Open spigot, drain most fluid with pump (but never run pump dry!!), refill w/dilute bicarbonate solution.
1. Flush loop once with dilute bicarbonate solution to neutralize. (Never run pump dry!!)
1. Flush loop with distilled water until clear (say, 3x). (Never run pump dry!!)
1. Drain loop most of the way with pump. Drain loop completely by tilting and shaking. (Never run pump dry!!)
1. Disconnect everything.

## 7. Cooling system
![Example coolant loop](images/coolant_loop.jpg)

1. Remove all components except CPU & 1 stick RAM.
1. Mount reservoir & pump.
1. Screw fill port and drain port into case.
1. Mount radiator fans to radiator.
1. Mount additional case fans.
1. Mount radiator to case.
1. Cut & run flex tubing between components. Hand tighten compression fittings only, but tighten them good!
1. Plumb spigot to dedicated pump drain outlet (if pump has one), or add a T joint in the outlet line (if not).
1. Plumb spigot outlet to drain port.
1. Plumb fill port to top of reservoir.
1. Fill reservoir via fill port.
1. Boot to BIOS. Be ready to add coolant as pump runs: the coolant level will drop as the fluid in the reservoir gets sucked into the loop. (Never run pump dry!!)
1. Run pump for a while to confirm no leaks. Note level of coolant in reservoir w/masking tape, drop tissue or construction paper across bottom of case so you'll see any drips. Confirm everything's dry and coolant level hasn't moved after an hour or so.

## 8. Full system test
1. Seat all components again.
1. Run cables. Don't lock them down yet.
1. Connect video output to onboard, disconnect GPU power (you don't want to run the GPU until you can monitor its temp, in case you fucked up GPU water block).
1. Boot to BIOS.
1. Configure fan curves from BIOS.
1. Confirm BIOS aware of all components.
1. Keep an eye on CPU temps while you're poking around. They should be nominal, this is as low a load as system will ever encounter.

## 9. Install Windows
1. Install Windows.
1. Install latest Radeon drivers.
1. Install FPSMonitor, copy Chinigo's config.
1. Install Passmark or something to generate a buncha CPU and GPU load

## 10. GPU test
1. Connect GPU power, connect video out to GPU.
1. Boot to Windows.
1. Monitor GPU & CPU temps as you run the full Passmark suite. Slam it with load to establish temps under max thermal load.

## 11. Final touches
1. Lock down wiring.

## 12. Overclock GPU
1. I got a 4% overall boost to clock speed without too much effort. Surprisingly straightforward.
1. Confirm temps are acceptable w/increased thermal load due to overclocking.

## 13. Overclock CPU
1. GPU is likely the bottleneck for most graphically-intensive games, but why not OC the CPU too? You've got oodles of cooling capacity to spare.
