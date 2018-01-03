# Mind Orb Mechanical Design Files
Tinkercad revision: 2018.01.03T15:44

## 3D Printing Setup
- LulzBot TAZ 6 -> https://www.lulzbot.com/store/printers/lulzbot-taz-6
- CAM -> Cura LulzBot Edition -> https://www.lulzbot.com/cura
    + Material -> `PLA (Verbatim)`
    + Profile -> `High speed (0.38mm)`
    + Infill
        * All 3 bracket parts -> 30%
        * All 4 footings -> 20%
- Hatchbox 3.00mm PLA (black) -> https://www.amazon.com/gp/product/B00MEZE7XU/
- Bed Coating
    + Mix 1:3 parts Elmer's white glue : water
    + Lightly coat bed in thin layer using foam brush
- Assembly
    + Join 1x base / 1x ring / 4x wedge with acrylic cement -> https://www.amazon.com/gp/product/B003HNFLMY/
    + TODO -> update steps

## Files
- Solid Models (exported from Tinkercad)
    + `base.stl` -> Lowermost bracket -> holds 
    + `ring.stl` -> Middle bracket -> holds equatorial LED ring
    + `wedge.stl` -> Top bracket (single) -> hold up-and-out LEDs
    + `footings.stl` -> All 4 lower footings -> attach to orb housing and magnets to hold inner bracket
- Cura Project Files
    + `bracket-all-parts_1x.curaproject.3mf` -> All parts needed to make a single inner bracket assembly in one print job (no footings)
    + `footings-all_1x.curaproject.3mf` -> All 4 footings (1 orb) in a single print job
- GCODE (for TAZ 6)
    + `bracket-all-parts_1x.gcode` -> All parts needed to make a single inner bracket assembly in one print job (no footings)
    + + `footings-all_1x.gcode` -> All 4 footings (1 orb) in a single print job
