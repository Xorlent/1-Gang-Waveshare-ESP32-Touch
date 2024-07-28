# 1-Gang-Waveshare-ESP32-Touch
Single Gang Waveshare ESP32 Touch 4.3" Mount
![Waveshare 4.3" Mount Rendering](https://github.com/Xorlent/1-Gang-Waveshare-ESP32-Touch/blob/main/Images/Waveshare-Mount.jpg)

## Purpose
- This mount allows for a [Waveshare ESP32-S3-Touch-LCD-4.3](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-4.3) to be installed in a single gang wall box.
> [!WARNING]
> This mount and associated components are not certified or designed for installation in a box with AC mains (utility) power.

## Bill of Materials
- A 3.3V DC power source (I recommend a 3.3V 1A Isolated Step-down DC Module)
- PH 2.0 female connector to provide 3.3V to the Waveshare device via the battery connection (see NOTE at the bottom of this README)
- [8mm x 3mm neodymium magnets (x4)](https://www.amazon.com/dp/B0CCXH6W5Q)
- 3.3 oz of filament (PETG recommended)
- [Physical switch](https://www.amazon.com/gp/product/B086L2GPGX) (x2 if you intend to program in-place)
- Optional [3.3V relay module](https://www.amazon.com/gp/product/B09SZ71K4L) to control a device with the physical switch (use with loaded back box)
- Optional [I2C SHT41 Temp + Humidity sensor](https://www.amazon.com/dp/B0C61LLH4T)

## Printing
- 0.20mm layer height
- All componets should be printed with tabs facing up
- Build plate supports are needed only to print the back box and top bezel
  - If printing the loaded back box, set the overhang threshold to 50 degrees
- Pause the print when the magnet column walls are finished but before the top chamfer (should be somewhere around layer 40 for the mount and 65 for the bottom bezel)
  - Once paused, install the magnets, ensuring correct polarity so the bottom bezel will fasten properly, then resume the print

## Using the Mount
- The perforated rectangle at the top of the mount facilitates a cutout for programming without disassembly or removing the Waveshare device
  - You must install and wire the hidden switch to the positive terminal of your power supply
  - Use this switch to de-power your device prior to connecting a USB C programming wire
- The BOOT and RESET switches are accessible via holes in the left side of the mount
- Once assembled, to remove the top bezel, slide a utility knife under the top lip of the bezel and carefully pry to push the case shell outwards
- The physical switch should nicely press-fit in place, but if you want more security, use glue or use the 1.5mm holes to add retaining pins
- There are two versions of the Back Box:
  1. Empty provides a single open cavity behind the mount
  2. Loaded creates pockets and snap-fit provisions for a relay module and power supply (use with Back Box - Loaded PCB Standoffs.step)
     - To install the back box power supply PCB standoffs, insert so the chamfers are a 90 degree offset to each other, then turn 90 degrees so chamfers align to lock in place.
  ![Loaded Back Box](https://github.com/Xorlent/1-Gang-Waveshare-ESP32-Touch/blob/main/Images/BackBox-Loaded.jpg)
- There are two versions of the Top Bezel:
  1. Exact - increases the width of the right-hand frame to match the active display area (see image at the top of this README)
  2. Symmetrical - provides for a balanced look, with equal frame widths
  ![Symmetrical Top Bezel](https://github.com/Xorlent/1-Gang-Waveshare-ESP32-Touch/blob/main/Images/TopBezel-Symmetrical.jpg)
> [!NOTE]
> The 3.3v battery header connector polarity is reversed from many PH 2.0 connectors.  The stenciled polarity on the Waveshare PCB is CORRECT.  Use this as your guide.

## Using the Waveshare Device
- See https://github.com/Westcott1/Waveshare-ESP32-S3-Touch-LCD-4.3-and-Arduino  

## Editing the Model
- [Link to OnShape Model](https://cad.onshape.com/documents/3b123274614f3c78b895b05a/w/b3004bfeec5f0d6871b879db/e/d03b68fccefe118e7b07eb04?renderMode=0&uiState=66a6be7423fdcb087bda0a28)
