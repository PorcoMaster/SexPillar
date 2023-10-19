# SexPillar
SexPillar is an advanced, fully parametric endstop, drawing inspiration from Unklicky, Sexbolt, and Unklicky_z. Crafted with meticulous attention to detail in Fusion, the design file encompasses a wide range of possibilities and is annotated with comments to ensure ease of use. Tailored specifically for printers with a metallic plate, it incorporates a robust magnet at its base. This magnetic feature not only ensures stability but also facilitates precise adjustments along the X and Y axes. Moreover, its adaptability shines, as it can accommodate any magnet, screw, wire, and heat insert. Primarily, SexPillar is optimized for use with an auto_Z macro, streamlining the calculation of nozzle offsets and babysteps.
# Disclaimer

This bill of materials is based on what I had readily available. While the associated .f3d file is fully parametric, I do not recommend purchasing the items listed verbatim. Instead, evaluate what you have on hand and adjust accordingly. Larger tower(Tube Height) and window dimensions (HWC) may offer greater ease during assembly. In essence, with the right specifications, you could construct the 'sexpillar' using just one screw, one sexbolt, two magnets, and two wires. I incorporated numerous heat inserts in my design due to my personal preference and because I had an abundance of them.

PS: if you do change Tube Height, remember to also adjust PinHoleHeight

# General Bill of Materials (BOM)

List of Hardware

- 20x5mm Magnet - 1 Units

- 6x2mm Magnet - 2 Units

- Heatinsert M3x4mm - 1 Unit

- HeatInsert M3 5mm - 1 Unit

- M3 Screw 16mm - 1 Unit

- M3 Screw 6mm - 1 Unit

- M4 SexBolt - 1 Unit / bigger than 8mm without lid, bigger than 12 mm with lid


Optional with putting LID, LID is completely Cosmestic

- M2 Screw 6mm - 2 Units

- M2 Heatinsert 3mm - 2 Units


[Heatinsert](https://www.amazon.com/Swpeet-Embedment-Hydraulic-Injection-Assortment/dp/B08YYGRCBG/ref=sr_1_3?crid=N201IKVAH3JM&keywords=swpeet+300pcs+5+values+m2+m3+m4+m5+m6+female+tampered&qid=1697503901&sprefix=swpeet+300pc%2Caps%2C106&sr=8-3) i used was from this kit, if you are using a different one please go into file and change sizes


# Parameters

- **BMD (Big Magnet Diameter):** 
  - 20 mm
  - Refers to the diameter of the larger magnet used in the design.
  
- **BMH (Big Magnet Height):** 
  - 5 mm
  - Specifies the height of the larger magnet.
  
- **SMD (Small Magnet Diameter):** 
  - 6 mm
  - Diameter of a smaller magnet
  
- **SMH (Small Magnet height):** 
  - 4 mm
  - The height of the smaller magnet.
  
- **HD (Heat Insert Diameter):** 
  - 4.3 mm
  - Diameter of the Bigger heat insert
  
- **HH (Heat Insert Height):** 
  - 8 mm
  - The vertical size of the Bigger heat insert.
  
- **TPH (Tolerance of Printer in holes):** 
  - 0.6 mm
  - The Printer typical Tolerance
  
- **NozzleSize:** 
  - 0.4 mm
  - The diameter of the 3D printer nozzle
  
- **Wall:** 
  - 4.8 mm (12 * NozzleSize)
  - Thickness of the wall, calculated based on the nozzle size.
  
- **DMG (Distance from magnet to ground):** 
  - 0.6 mm
  - This gap ensures the magnet doesn't touch the base or ground. so it doens't scratch, too big and you will not have a good grip
    too small and you will scratch your table.
  
- **LayerHeight:** 
  - 0.2 mm
  - Each 3D print layer's height, determining the print's resolution.
  
- **WSM (Wall separating magnet):** 
  - 0.6 mm (3 * LayerHeight)
  - The thickness of the wall that separates individual magnets. too small, weak wall, too big you have a problem with magnetic not having enough force to push.
  
- **DP (Diameter Pin):** 
  - 8.4 mm
  - Refers to the diameter of a pin used in the assembly.
  
- **PHe (Pin Height):** 
  - 25 mm
  - The vertical dimension or height of the pin.
  
- **FP1 (Flatten Pin adjustment):** 
  - 1 mm
  - Amount to reduce the pin's side.
  
- **FP2 (Opposite side adjustment):** 
  - 1 mm
  - A similar adjustment as FP1 but applied to the opposite side.
  
- **SCD (Screw Contact Diameter):** 
  - 3 mm
  - Diameter where the screw makes contact
  - 
- **TSW (Tolerance Screw Window):** 
  - 0.6 mm
  - The allowable deviation in the screw placement window to ensure a proper fit.
  
- **HWC (Height Window contact with added half circle):** 
  - 3.6 mm (SCD + 0.6 mm)
  - Refers to the height of the contact window that includes an extra half-circle design.
  
- **TSexyBolt (Thread Sexy Bolt):** 
  - 5.5 mm
  - The length of the threaded section of "sexy bolt". You need to edit this directly on the design timeline.
  
- **HTsexyBolt (Height Thread SexyBolt):** 
  - 4 mm
  - Specifies the height of the threaded of the "sexy bolt".
  
- **TubeHeight:** 
  - 35 mm (PHe + 10 mm)
  - The vertical dimension of the Tube.
  
- **SHD (Small Heat Insert Diameter):** 
  - 2.7 mm
  - Diameter of a smaller variant of the heat insert.
  
- **SHH (Small Heat Insert Height):** 
  - 3.5 mm
  - Vertical size of the smaller heat insert.
  
- **SSD (Small Screw Diameter):** 
  - 2 mm
  - Diameter of the smaller screws used in the design.
  
- **PINholeHeight:** 
  - 16.4 mm
  - Represents the depth of a hole specifically made to accommodate a pin.


- [Teste](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/Video%20Teste.mp4) 

- [Moving](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/Video%20moving.mp4)

![SexPillar](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/SexPillar.png)
![Appresentation](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/SexPillar.gif)

![Tutorial](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/SexPillar_v2%20(2).gif)
![Real](https://github.com/PorcoMaster/SexPillar/blob/main/Images%20And%20Videos/Picture.jpeg)




Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
