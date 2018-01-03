# Mind Orb Mechanical Design Files
Tinkercad revision: 2018-01-02T13:31

## 3D Printing Setup
- LulzBot TAZ 6 -> https://www.lulzbot.com/store/printers/lulzbot-taz-6
- CAM -> Cura LulzBot Edition -> https://www.lulzbot.com/cura
    + Material -> `PLA (Verbatim`
    + Profile -> `High speed (0.38mm)`
    + Infill
        * Base -> 30%
        * Ring -> 20%
        * Wedges -> 20%
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
    + (Cura was doing weird things with saving -> missing for this iteration)
- GCODE (for TAZ 6)
    + `base_1x` -> 1 lower bracket
    + `ring_1x` -> 1 middle bracket
    + `wedge_4x` -> 4 top 
