# Custom Pickguard for Sire T3 Telecaster

![Finished Pickguard on Sire T3](path/to/your/image.jpg)
*A placeholder for an image of your finished pickguard on the guitar.*

## Overview

This repository contains the design files for a custom, direct-fit replacement pickguard for the **Sire T3 Telecaster-style guitar**.

As many owners have discovered, the stock pickguard on the Sire T3 does not adhere to standard Fender Telecaster specifications. This means that common off-the-shelf replacement pickguards will not align correctly with the screw holes, neck pocket, and control plate.

This project was created to provide a verified, ready-to-use template for anyone looking to create their own pickguard for their Sire T3, whether through 3D printing, CNC machining, or manual cutting.

## Files Included

The files are organized into folders based on their purpose:

* **/CAD/**
    * `Sire T3 Pickguard.step`: A universal solid model for easy modification in most CAD software (e.g., SolidWorks, Inventor, FreeCAD).
    * `Sire T3 Pickguard.f3d`: The original, parametric Autodesk Fusion 360 file. This is the best file to use for modifications if you have Fusion 360.

* **/CNC/**
    * `Sire T3 Pickguard.dxf`: A 2D vector file suitable for CNC routers, laser cutters, or for printing as a paper template to check the fit.

* **/STL/**
    * `Sire T3 Pickguard.stl`: A high-resolution mesh file, ready to be sliced for 3D printing.

* **/Reference/**
    * `Sire T3 Pickguard Scan.jpg`: The original high-resolution photo/scan of the stock pickguard that was used to trace and model this design.

## Instructions for Use

### 1. Verification (Recommended)

Before committing to a final piece, it is **highly recommended** to verify the fit.
1.  Print the `.dxf` file at a 1:1 scale on paper.
2.  Cut it out and lay it on your guitar to check the alignment of all screw holes, the neck pocket, and the pickup cutout.

### 2. 3D Printing

* **Material:** PLA, PETG, or ABS will work well. PETG is a good choice for durability.
* **Layer Height:** 0.2mm is recommended for a good balance of speed and quality.
* **Infill:** 20-40% is sufficient.
* **Bed Size:** Ensure your printer's build plate is large enough to accommodate the pickguard (approx. 220mm x 220mm). I was able to just fit it within my FlashForge AD5MP.

### 3. CNC Machining / Laser Cutting

The `.dxf` file is ready to be used with a CNC router or laser cutter.
* **Material:** Standard 3-ply or single-ply plastic pickguard blanks are ideal.
* **Tooling:** Use a fine-bit router for clean edges. If laser cutting, you may need to do a finishing pass to clean up the edges.
* **Countersinking:** Remember to countersink the screw holes after cutting for a flush fit with standard pickguard screws.

## Notes & Disclaimer

* This design was modeled from my own Sire T3 which I purchased in 2025. While it should fit all T3 models, minor variations may exist. Always test the fit first.
* Depending on the precision of your machine, some minor sanding or filing of the edges may be required for a perfect fit.
* This project is provided as-is. Use at your own risk.
---

Happy modding!
