# Starhush constellation star data

`starhush_constellation_stars.json` lists, for each of the 88 IAU constellations, the stars used to draw its lines in the Starhush app:
right ascension and declination (degrees), visual magnitude, distance in light-years, B–V color index and proper name.

Sources
- Constellation lines and star positions: d3-celestial by Olaf Frohn (BSD license), https://github.com/ofrohn/d3-celestial
- Distances, color indices and names: HYG Database v4.1 by David Nash, https://www.astronexus.com/hyg (CC BY-SA 4.0)

Changes: stars were matched by position and magnitude; distances converted from parsecs to light-years. Ten stars with no reliable match use the median distance of their constellation.

License: this adapted data file is released under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), https://creativecommons.org/licenses/by-sa/4.0/
