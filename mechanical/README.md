# Mind Orb Mechanical Design Files
Tinkercad revision: 2018.01.03T15:44

## 3D Printing Setup
- LulzBot TAZ 6 -> https://www.lulzbot.com/store/printers/lulzbot-taz-6
- CAM -> Cura LulzBot Edition -> https://www.lulzbot.com/cura
    + Material -> `PLA (Verbatim)`
    + Profile -> `High speed (0.38mm)`
    + Infill -> 30%
- Hatchbox 3.00mm PLA (black) -> https://www.amazon.com/gp/product/B00MEZE7XU/
- Bed Coating
    + Mix 1:3 parts Elmer's white glue : water
    + Coat bed in generous, but even layer using foam brush
- Assembly
    + Join 1x base / 1x ring / 4x wedge with acrylic cement -> https://www.amazon.com/gp/product/B003HNFLMY/
    + TODO -> update steps

## Files
- Solid Models (exported from Tinkercad)
    + `base.stl` -> Lowermost bracket -> holds 
    + `ring.stl` -> Middle bracket -> holds equatorial LED ring
    + `wedge.stl` -> Top bracket (single) -> hold up-and-out LEDs
    + `footings.stl` -> All 4 lower footings -> attach to orb housing and magnets to hold inner bracket
    + `bracket-footings-all-parts_1x.stl` -> All 10 parts in a single file oriented for printing in high-density batches
- Cura Project Files
    + `bracket-all-parts_1x.curaproject.3mf` -> All parts needed to make a single inner bracket assembly in one print job (no footings / infill 30%)
    + `footings-all_1x.curaproject.3mf` -> All 4 footings (1 orb) in a single print job (infill 20%)
    + `bracket-footings-all-parts_2x.curaproject.3mf` -> 2 full orbs worth of parts for batch printing (infill 30%)
- GCODE (for TAZ 6)
    + `bracket-all-parts_1x.gcode` -> All parts needed to make a single inner bracket assembly in one print job (no footings / infill 30%)
    + `footings-all_1x.gcode` -> All 4 footings (1 orb) in a single print job (infill 20%)
    + `bracket-footings-all-parts_2x.gcode` -> 2 full orbs worth of parts for batch printing (infill 30%)
