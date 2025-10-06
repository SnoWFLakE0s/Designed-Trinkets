# Custom Pickguard for Sire T3 Telecaster

<p align="center">
  <img src="https://github.com/user-attachments/assets/07b998d5-5d69-4478-954b-19e7f91d379c" width="400" alt="Finished Pickguard Example 1">
  <img src="https://github.com/user-attachments/assets/ac99cdb4-b497-4160-bd4c-82751c0eeec6" width="400" alt="Finished Pickguard Example 2">
</p>

## Overview

This repository contains the design files for a custom, direct-fit replacement pickguard for the Sire T3 Telecaster.

The stock pickguard on the Sire T3 does not adhere to standard Fender Telecaster specifications. This project was created to provide a verified, ready-to-use template for anyone looking to create their own pickguard for their Sire T3, whether through 3D printing, CNC machining, or manual cutting.

## Files Included

* **/CAD/**
    * `Sire T3 Pickguard.step`: It's a STEP file... import into any sensible CAD suite.
    * `Sire T3 Pickguard.f3d`: The original, parametric Autodesk Fusion file.

* **/CNC/**
    * `Sire T3 Pickguard.dxf`: A 2D vector file suitable for CNC routers, laser cutters, or for printing as a paper template to check the fit.

* **/STL/**
    * `Sire T3 Pickguard.stl`: A high-resolution mesh file, ready to be sliced for 3D printing.

* **/Reference/**
    * `Sire T3 Pickguard Scan.jpg`: The original high-resolution photo/scan of the stock pickguard that was used to spline fit.

## Instructions for Use

### 1. Verification (Recommended)

Before committing to a final piece, it is highly recommended to verify the fit.
1.  Print the `.dxf` file at a 1:1 scale on paper.
2.  Cut it out and lay it on your guitar to check the alignment of all screw holes, the neck pocket, and the pickup cutout.

### 2. 3D Printing

* **Material:** PLA, PETG, or ABS will work well. PETG is a good choice for durability.
* **Layer Height:** 0.2mm is recommended for a good balance of speed and quality.
* **Infill:** 20-40% is sufficient.
* **Bed Size:** Ensure your printer's build plate is large enough to accommodate the pickguard (approx. 220mm x 220mm). I was able to just fit it within my FlashForge AD5MP.

### 3. CNC Routing / Laser Cutting

The `.dxf` file is ready to be used with a CNC router or laser cutter. **File units are in millimeters!**
* **Material:** Standard pickguard blanks are ideal if routing... if lasercutting, you can reasonably use 1/8" or 1/16" acrylic. That's what I used for laser cutting.
* **Countersinking:** Remember to countersink the screw holes for a flush fit with standard pickguard screws.

## Notes & Disclaimer

* This design was modeled from my own Sire T3 which I purchased in 2025. While it should fit all T3 models, minor variations may exist. Always test the fit first.
* Depending on the precision of your machine, some minor sanding or filing of the edges may be required for a perfect fit.
* This project is provided as-is. Use at your own risk.
---

Happy modding!
