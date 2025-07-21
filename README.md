# Celebrating 30 Years of the Virtual Boy
In celebration of the Virtual Boy’s 30th anniversary, here’s a DIY cartridge project for fans and builders alike.

# VBRC
Build Virtual Boy Rom Cartridge by yourself!

<p align="center">
  <img src="https://github.com/Dayongdo/VirtualBoyRC/blob/main/IMG/01.png" width="50%">
  <img src="https://github.com/Dayongdo/VirtualBoyRC/blob/main/IMG/03.JPG" width="30%">
</p>

# Introduction
There are plenty of cheap alternative repro cartridge for other consoles, But not for Virtual boy!

So, here's cheap DIY solution.

**I'm not arguing with those who sell repro cartridges for the Virtual Boy — I'm just offering another choice.**

Due to small VIrtual Boy fanbase, there are no reprodution parts made in China.
So you'll need to prepare some parts yourself.

# Files
|File|Desc|
|:--:|:--:|
|VBRC_C.zip|Virtual Boy Cartridge Board File|
|VBRC.stl|Cartridge Shell for 3D print|
|VBRC.dwg|Cartridge Shell for laser cut out (2mm acrylic)|

# BOM List
|Comp|Desc|
|:--:|:--:|
|2mm 2x30p connector|For cart-to-console connection|
|M27C160|16Mbit EPROM|
|FW16W08|Alt for SRAM|
|0.1uF 0805||

# Build Tips
The original Virtual Boy cartridge connector size is 4.0 × 64.0 × 5.3 mm.

Most aftermarket connectors are 4.5 × 60.5 × 4.3 mm, so:

    Sand down the 4.5mm width to 4.0mm.

    Be aware the depth will still be ~1mm shorter than the original.

Based on my tests, 4.2mm height gave the best result.

Since the PCB matches the original Virtual Boy cartridge size, it’s not suited for standalone use.
Please use the provided case files.
⚙️ Recommended: M3 5mm flat-head screws for assembly.

If you insert the cartridge without a shell, it will look like this when connected to the Virtual Boy:

<p align="center"> <img src="https://github.com/Dayongdo/VirtualBoyRC/blob/main/IMG/04.JPG" width="60%"> </p>


# ⚠️Known Issues
<p align="center">
  <img src="https://github.com/Dayongdo/VirtualBoyRC/blob/main/IMG/05.jpg" width="40%">
  <img src="https://github.com/Dayongdo/VirtualBoyRC/blob/main/IMG/06.jpg" width="42%">
</p>

**Successfully tested with Bound High — it works great!**

However, some ROMs (e.g. Jack Bros., Hyper Fighting) did not work.

Likely causes:

+ ROM slicing errors
+ ROM size mismatch (e.g., not fitting in 2MB space)

My ROM writer stopped working, so I couldn't test further for while.


# Future Development
This project was developed quickly to celebrate the 30th anniversary of the Virtual Boy,
so the current version only supports EPROM-based ROM writing.

The final goal is to create a single-board version with the following improvements:

+ Support for USB-based flash ROM writing
+ Fully enclosed and stable cartridge design

Thanks!
