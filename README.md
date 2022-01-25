# ***Panda41***

A modified version of the Reviung41 PCB by gtips, designed to fit in a stacked acrylic case made by opsecPANDA in collaboration with dazon. 

![Panda41 family photo](/Panda41-pics/Panda41_round-up.jpg)

\![Panda41 family photo](https://i.imgur.com/QJjG1G4.jpg)

https://imgur.com/a/qKzNon4

## **PCB**

Modified by dazon and Rossman360, the PCB has the following differences from the original Reviung41:

- Controller footprint rotated and moved underneath a switch
- Top edge of PCB is now flat across
- MX switch footprint
- Diode footprint is THT+SMD combo
- RGB strip header added (SMD LED footprints were not removed)

## **Case**

Case files were designed to each be 3mm acrylic. The files names refer to a number in the beginning to label their order in the stack, and the “--x1” to denote how many of that specific file type you need to have. I.e. “4-mid layer–x2.dxf” means you need to cut or 3D print or otherwise create 2 layers of this one. 

- 1-top top–x1.dxf
- 2-top lower--x1.dxf
- 3-switch plate–x1.dxf
- 4-mid layer with risers–x1.dxf
- 4-mid layer–x2.dxf
- 5-bottom plate–x1.dxf

If you want to mimic my original “top color & bottom color” mix&match, you want to have layers 1 and 2 be Color A and, the remainders be Color B. If you want to do an “RGB layer” you should actually have both “4-mid layer–x2.dxf” layers be something like white, off-white, opal, glass or just clear. 

## **Hardware**

The case is designed to use the following hardware:

- 16 m2 case screws - 8mm length
- 8 m2 case spacers - 10mm length
- 3 m2 riser nuts
- 3 m2 riser screws - 12mm length
- 41 diodes - 1N4148, through hole (TR) or SMD
- 1 tactile reset switch - PTS635SH43LFS


## **Firmware/keymap:**

When flashing for this board, you want to treat it as a Reviung41. You can create a keymap with the online QMK Configurator under the Reviung41 selection. If you want to use VIA, flash it with the “reviung41_via.hex”.  You can use a nice!nano and flash with a reviung41 shield. 
