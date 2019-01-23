# Raster 2 Laser GCode generator for Inkscape

Modified version of the 305Engineering extension adding several options:

Speed OFF - set moving speed independently of engave speed
Dwell - add in dwell command before laser changes - fixes errors causing engrave inversion, use -1 value to disable
Initial Z position - for setting the bed height before starting (only useful for 3D laser conversions)
Reset Position - whether to output a G92 command that resets position to 0,0 but causes Z axis reset as well


