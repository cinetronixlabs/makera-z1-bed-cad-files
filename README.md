# Makera Z1 / Z1 Pro Bed CAD Files and Workholding Reference (STEP / DXF)

This repository contains reference CAD files for the Makera Z1 / Z1 Pro bed / worktable.

These files are intended to help users design custom fixtures, spoilboards, workholding accessories, and other add-ons for the Makera Z1 and Z1 Pro.

Distribution of these reference CAD files has been approved by Makera.

## Included Files

### STEP

- `STEP/Makera_Z1_Bed_v1_1.step`  
  3D reference model of the Makera Z1 / Z1 Pro bed / worktable.  
  Includes Blue Tape Method workholding fixtures in the same STEP file.

### DXF

- `DXF/Makera_Z1_Aluminum_Base_v1_1.dxf`  
  2D reference layout of the aluminum base

- `DXF/Makera_Z1_Aluminum_Base_Hole_Pattern_v1_1.dxf`  
  2D reference layout of the aluminum base, showing only the M5 threaded holes and dowel pin holes

- `DXF/Makera_Z1_MDF_Bed_v1_1.dxf`  
  2D reference layout of the MDF bed

## Included STEP Components

The STEP file includes the following components:

- Aluminum Base
- Aluminum Base (M5 and Dowel Pin Holes Only)
- MDF Bed
- Blue Tape Fixture (100x150x10mm, Makera Store Stock)
- Blue Tape Fixture (100x173.5x8mm, Optimized Stock)
- L-Bracket (Thick)
- L-Bracket (Thin)

## Intended Use

These files can be useful for:

- Designing custom spoilboards
- Creating fixture plates
- Planning workholding setups
- Aligning fixtures with the Makera Z1 / Z1 Pro bed
- Creating accessories that reference the bed hole pattern or usable work area
- Creating Blue Tape Method workholding setups using painter’s tape and CA glue

## Important Notes

These files are provided as reference CAD files.

The hole positions have been checked against my Makera Z1 unit and Makera’s official [`Z1-MDF-v2.1.STEP`](https://github.com/MakeraInc/CarveraProfiles/tree/main/Machine_Design_Files) file.

For the Blue Tape Fixture, use M5x14 mm screws or the M5x20 mm screws included with the Makera Z1. Do not use screws longer than M5x20 mm, as they may contact the bottom of the machine enclosure.

For locating the Blue Tape Fixture, use the dowel pins included with the Makera Low-Profile Vise or 4th Axis Module.

Before machining final parts, please verify any critical dimensions on your own machine.

These files are not official Makera CAD files.

## Compatibility

Compatible with:

- Makera Z1
- Makera Z1 Pro

## Revision History

### v1.1

- Corrected one M5 threaded hole position located to the left of the tool setter.
- Verified the hole positions against my Makera Z1 unit and Makera’s official `Z1-MDF-v2.1.STEP` file.
- Added Blue Tape Method workholding fixtures to the STEP file.
- Added an aluminum base hole-pattern-only DXF file showing only the M5 threaded holes and dowel pin holes.

### v1.0

- Initial release. Removed from the repository to avoid confusion due to one incorrect M5 threaded hole position.

## License

These files are shared under the CC BY 4.0 license.

You are free to use, modify, and share them, including for your own projects, as long as proper credit is given.

Credit: [cinetronix](https://www.youtube.com/@cinetronix_labs)

## Disclaimer

These files are provided as-is, without any warranty.

Use them at your own risk. I am not responsible for any damage, machining errors, fitment issues, or other problems resulting from the use of these files.

Makera is a trademark of Makera. This repository is not an official Makera repository.
