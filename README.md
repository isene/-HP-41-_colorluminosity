# hp-41_colorluminosity
Calculate the luminosity of an RGB color

Calculate the total luminosity of an RGB color in the format "FFFFFF" (hex triplet"). This may be useful when creating themes or matching colors with similar luminosity across different color hues.

This repository includes two tools - one HP-41 program and a Ruby script. For the HP-41 program (CLUMIN), put the color in Alpha (such as "A854F3") and do XEQ"CLUMIN" and you will get the percent luminosity in Alpha and the score (out of max 765) in REG 00. For the Ruby script, simply type "colorluminosity A854F3" to get the score and percentage luminosity for that color.

## License
This software is released into the Public Domain.
