# 1-Gang-Waveshare-ESP32-Touch
Single Gang Waveshare ESP32 Touch 4.3" Mount
![Waveshare 4.3" Mount Model](https://github.com/Xorlent/1-Gang-Waveshare-ESP32-Touch/blob/main/Images/Waveshare43-Model.jpg)

## Purpose
- This mount allows for a [Waveshare ESP32-S3-Touch-LCD-4.3](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-4.3) to be installed in a single gang electrical box.
> [!WARNING]
> This mount and associated components are not certified or designed for installation in a box with AC mains (utility) power.

## Bill of Materials
- A 3.3V DC power source
- PH 2.0 female connector to provide 3.3V to the Waveshare device via the battery connection
- [8mm x 3mm neodymium magnets (x4)](https://www.amazon.com/dp/B0CCXH6W5Q)
- 3oz filament (PETG recommended)
- [Physical switch](https://www.amazon.com/gp/product/B086L2GPGX)
- Optional [3.3V relay module](https://www.amazon.com/gp/product/B09SZ71K4L) to control a device with the physical switch (use with loaded back box)
- Optional [SHT41 Temp + Humidity sensor](https://www.amazon.com/dp/B0C61LLH4T)

## Printing
- 0.20mm layer height
- All componets should be printed with tabs facing up
- Supports are needed only to print the back box
- Pause the print when the magnet column walls are finished but before the top chamfer (should be around layer 39)
  - Once paused, install the magnets, ensuring correct polarity so the bottom bezel will fasten properly, then resume the print

## Using the Mount
- The perforated rectangle at the top of the mount facilitates a cutout for programming without removing the device from the mount
- Once assembled, to remove the top bezel, slide a utility knife under the top lip of the bezel and carefully pry to push the case shell outwards
- The physical switch should nicely press-fit in place, but if you want more security, use glue or use the 1.5mm holes to add retaining pins
- There are two versions of the Back Box:
  1. Empty provides a single open cavity behind the mount
  2. Loaded creates pockets and snap-fit provisions for a relay module and power supply (use with the PCB standoffs)
- There are two versions of the Top Bezel:
  1. Symmetrical provides for a balanced look, with equal frame widths
  2. Exact increases the width of the right-hand frame to match the active display area
- To install the PCB standoffs, insert the standoff at a 90 degree offset to the back box chamfered recess.  Once inserted, turn 90 degrees so chamfers align to lock in place.

## Using the Waveshare Device
- See https://github.com/Westcott1/Waveshare-ESP32-S3-Touch-LCD-4.3-and-Arduino
