# mycusini-reveng
Collection of Files &amp; Ressources for advanced uses of the MyCusini 3D Food Printer

The firmware is based on repetier and can be found here https://github.com/print2taste/miniprinter-firmware

Unfornuately the folder structure from repetier is not preseved and the code seems to be formatted differently 
making it harder to find the differences to mainline repetier.

It looks like it is based on repetiert 1.0.0 and most changes to the mainline firmware are marked with
`//marcel XXXX`
(See https://github.com/print2taste/miniprinter-firmware/search?q=marcel)

There is also a summary of changes in the [`mycusini-firmware.ino`](https://github.com/print2taste/miniprinter-firmware/blob/master/mycusini-firmware.ino#L28) file. Here (translated to english):

> Manual Changes:
>  Marcel Endstop
>  = Addition of an Extruder Max-Endstops
>  Marcel Temp
>  = Condition for Test for the temperature probe
>  Marcel LCD
>  = Addition of the LCD
>  Marcel Kartuschenwechsel
>  = menu option for the cartridge change and extruder position as a opening condition
>  Marcel Menu
>  = change and add menu options

## USB Port

The USB Port exposes a standard serial port, which also reports temperatures and accepts GCODE, so OctoPrint etc. seem to work just fine with it.

## PrusaSlicer Config

See the files `3dbenchy.3mf` and `config.ini`

## Printing Custom Choclate Filament

See filament-mold folder


I am not affiliated with MyCusini or print2taste in any way.