# Intro
HexCooler is a laptop cooling stand project designed with a hexagonal pattern.

# BOM
> [!note]
> The BOM is work in progress. It is possible that some materials are missing right now.

> [!imporant]
> I assume you have basic knowledge about 3D printing as well as access to a 3D printer.
> Also, I assume you have basic knowledge about soldering and you have access to a soldering setup.

> [!tip]
> I don't give you links as I assume you can find the best offer yourself :smile:

> [!tip]
> I did most purchases in PLN, so USD prices are approximate.

| Item             | Quantity | Price [PLN] | Price [USD] | Notes |
|------------------|----------|-------------|-------------|----------------|
| Filaments (PLA)  | 2 * 1 kg (one black and one red - pick whatever colors you want) | 85 | 24 |  |
| Be Quiet! Pure Wings 3 140mm 3-Pin black | 1 | 50 | 14 |  |
| Hex Cooler V1 PCB on [JLCPCB](https://jlcpcb.com/) (see [project file](./hexcooler_v1.epro)) | 2 assembled + 3 printed boards | 73.20 | 20 | This is what I paid for USD in my bank. In reality, it was a bit cheaper on JLCPCB (as some of those USD left on my currency account) |
| **Total** | 208.20 | 58 |  |

> [!note]
> I also used some universal pins to connect my fan to the PCB. You can alternatively use goldpins or (not recommended) cut the plug and solder the fan wires directly to the PCB.

> [!note]
> As this is V1 I ordered only 2 assembled boards from JLCPCB. If you are going to build multiple coolers, it is theoretically possible to cut costs by ordering more assembled boards.
> Also, if you have advanced soldering skills, you can order unassembled boards + components (much cheaper) and solder them yourself.
> Also I didn't print all the filament I bought - you can save some money there.

# How to build

1. Order all the parts from the BOM. Note that delivery time especially for PCBs may be long.
2. Install FreeCAD
3. Download this repository
4. Open `hexcooler.fcstd` in FreeCAD
5. Click on `VarSet` and adjust whatever parameters you want (e.g. fan holder size, hex dimensions, e.t.c.)
6. Export each individual part
   (PROTIP: If your printer is too small to print the whole part at once, you can set NX/NY to e.g. half, and print twice,
   but be careful to verify before printing - some frame parts are 1 tile wider so printing them twice will not work with
   printing the grid twice - you know what I mean, just count tiles and you'll see what I mean :smile:).
   One more protip: I recommend printing a small prototype first (e.g. with nx=1, ny=1) and check if junctions fit well (they should not be too loose or too ight - check JunctionTolerance var).
7. Print all the parts
8. Assemble the parts together (you can use some glue if you need but I didn't use any and it works for me)
9. Its done! GG!

# Status
WIP :smile:

**04.11.2025** The first project iteration has just been printed. It has some minor issues (e.g. one missing junction) which however has already been fixed.
I also experienced a skill issue (while exporting the bottom part I didn't export mirrors)
**18.01.2026** The project has been printed almost entirely and is under use. It is missing some minor parts (e.g. the stand - comming soon) but geneerally looks good and is usable.

