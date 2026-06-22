# Using a Prusa XL bed tile instead of the custom made aluminum plate.
Does not give any more print area despite being larger. Is still 70x70mm

## BOM
- Prusa XL Bedtile https://www.prusa3d.com/product/heatbed-tile/
- magnetic spring steel plate 90mmx90mm (self source or cut from a larger one). DXF in mod folder
- molex clickmate 4 harness (3 options for sourcing) 
https://www.prusa3d.com/product/modular-bed-cable/
https://www.mouser.com/ProductDetail/538-15135-0403
https://www.digikey.com/en/products/detail/molex/0151350403/6833474
- M3x25mm grub screws https://www.amazon.com/dp/B0DDHN1C8C
- M3x4x5 brass heat sets (if using modified knobs) https://www.amazon.com/dp/B0D7M3LJDL
- bed springs. used 0.5x5.5x11x10x5 springs from [this set](https://www.amazon.com/dp/B0DRVND2LM)


## Files to print
- fan duct x2 (must use ones in the mod folder)
- knob bed x4 (can use stock ones if desired)
- bed frame (two versions given, one with built in supports, one without)

## Basic instructions
Use of the included shorter fan ducts is required, as the standard ducts will hit the larger bed plate.
Grub screws install into the bed tile from underneath and stay permanently, snug them in. This allows adjustability using the knobs. The modified knobs are not necessary, but they move the threads to the top of the knob using a headset, which makes it easier to thread in. Wire up the bed plate referencing the below image. Polarity is not important on heater or thermistor. Unsure of length of the Prusa harness, but the 300mm ones from digikey or mouser are perfect length to reach the SKR pico.
Sensor value in klipper will be “EPCOS 100K B57560G104F” or “Generic 3950” both are nearly identical

![description](https://github.com/dahliamoth/Fraxinus-00tw/blob/main/Mods/00tw%20Prusa%20XL%20bed%20tile/bed%20underside.jpg)
![description](https://github.com/dahliamoth/Fraxinus-00tw/blob/main/Mods/00tw%20Prusa%20XL%20bed%20tile/heatset%20bed%20nuts.jpg)
