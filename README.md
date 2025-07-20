# VirtualBoyRC
Build Virtual Boy Rom cartridge by yourself!

# INTRO
There's lot of cheap alternative repo cartridge at other consoles, But not Virtual boy!

**I'm not arguing who sells repo cartridge of Virtual boy, Just giving another choice.**

Due to small fan number of Virtual boy, there's no reprodutions at china.
So you need to prepair some parts.

# Files
+ VirtualBoy_RomCart_c.gerber : Virtual Boy Cartridge Board File
+ VIrtualBoy_RomCart_c.stl : Cartridge Shell for 3D print
+ VIrtualBoy_RomCart_c.dxr : Cartridge Shell for laser cut out (acryllic 2mm)

# BOM List
|Desc|Ref|
|:--:|:--:|
|2mm 2x30p connector||
|M27C160||
|FW16W08||
|0.1uF 0805||

# Build Tips
The Virtual Boy connector has 4x64x5.3mm size. But most of connector out of world have 4.5x60.5x4.3mm.

So you need to grid 4.5mm to 4mm, but the depth is 1mm shorter than Virtual boy original Connector.

I've grid some of connector, and best resault was 4.2mm of height.

# Known error
I've test cartridge by BoundHigh. Which works Great! But other rom doesn't works.

(Jack Bros, HyperFight)

I think the reason was at slicing, and fitting to 2mb rom. 
But My rom writer stops to working so I can't test anymore.
