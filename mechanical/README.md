# Mind Orb Mechanical Design Files
Tinkercad revision: 2018.01.02T21.07

## 3D Printing Setup
- LulzBot TAZ 6 -> https://www.lulzbot.com/store/printers/lulzbot-taz-6
- CAM -> Cura LulzBot Edition -> https://www.lulzbot.com/cura
    + Material -> `PLA (Verbatim)`
    + Profile -> `High speed (0.38mm)`
    + Infill (all) -> 30%
- Hatchbox 3.00mm PLA (black) -> https://www.amazon.com/gp/product/B00MEZE7XU/
- Bed Coating
    + Mix 1:3 parts Elmer's white glue : water
    + Lightly coat bed in thin layer using foam brush
- Assembly
    + Join 1x base / 1x ring / 4x wedge with acrylic cement -> https://www.amazon.com/gp/product/B003HNFLMY/

## Files
- Solid Models (exported from Tinkercad)
    + `base.stl` -> Lowermost bracket -> holds 
    + `ring.stl` -> Middle bracket -> holds equatorial LED ring
    + `wedge.stl` -> Top bracket (single) -> hold up-and-out LEDs
- Cura Project Files
    + `all-parts_1x.curaproject.3mf` -> All parts needed to make a single inner bracket assembly in one print job
- GCODE (for TAZ 6)
    + `all-parts_1x.gcode` -> All parts needed to make a single inner bracket assembly in one print job
