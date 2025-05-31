
# Ida - 3-key macropad

![](images/1.jpg)
![](images/2.jpg)
![](images/3.jpg)
![](images/4.jpg)

# Bill of Materials

- **2x** 12x1 pin header
- **1x** Diode (_1N4148 DO-35_)
- **1x** Push button for resetting the board (_4x4x1.5mm_)
- **1x** Pro Micro or something with compatible pinout
- **3x** Keyboard switch
- **1x** 2u stabilizer
- **4x** 8mm rubber feet
- Steady hands

# Getting the parts made

- For the PCB, there is a Kicad project included in the repo in [kicad](kicad/). You can simply upload the gerbers to something like JLCPCB.
- The case is made up of two ([top](top.stl), [bottom](bottom.stl), [threads](drawing.pdf)) parts which are CNC'd out of Aluminium (but you can also 3D print them). I used JLCPCB for this too.

# Build guide

**Step 1**: Solder the reset switch and the diode:

![](images/guide/1.jpg)

**Step 2**: Solder the pin headers:

![](images/guide/2.jpg)

**Step 3**: Place the stabilizers:

![](images/guide/3.jpg)

**Step 4**: Place switches in the enclosure:

![](images/guide/4.jpg)

**Step 5**: Place the PCB inside the enclosure and solder the switches:

![](images/guide/5.jpg)
![](images/guide/6.jpg)
![](images/guide/7.jpg)

**Step 6**: Place and solder the Pro Micro:

![](images/guide/8.jpg)
![](images/guide/9.jpg)

**Step 7**: Screw the bottom part of the case:

![](images/guide/10.jpg)

**Done!**

![](images/1.jpg)

# Schematic

![](/images/schematic.png)

![](/images/pcb.png)