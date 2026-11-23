
# Generic 10-Inch 1U Rack Tray Template

A customizable 3D-printable tray template for 10-inch homelab racks.

This project provides a starting point for designing custom rack trays to fit your own hardware. Download the CAD files, modify the geometry to accommodate your device, and 3D print your own custom rack mount.

Whether you're mounting a mini PC, single-board computer, networking equipment, or other custom hardware, this template makes it easy to create a solution that fits your setup.

## Included Files

| File | Description |
|---|---|
| [Fusion 360 File (.f3d)](<Fusion 360 File - Generic 10inch 1U Template.f3d>) | Native Fusion 360 project for editing. |
| [STEP File (.step)](<Generic 10inch 1U STEP File.step>) | Universal CAD model compatible with multiple CAD applications. |

## Requirements

You will need:

- A CAD application capable of importing STEP files or opening Fusion 360 projects.
- A 3D printer.
- PETG filament (recommended).

Compatible CAD applications include:

- Autodesk Fusion 360
- FreeCAD
- SolidCraft
- Other CAD applications supporting STEP files.

## Getting Started

### 1. Download and Import

Download either of the provided CAD files.

- Open the `.f3d` file directly in Fusion 360.
- Import the `.step` file into your preferred CAD application.

### 2. Customize the Front Face

Create a sketch on the front face of the tray.

Modify the sketch to match the dimensions of your device. Add the necessary openings, mounting points, or other geometry required to accommodate your hardware.

### 3. Design the Supporting Geometry

On the back of the tray, create a sketch for the supporting geometry.

Design the supports to hold your device securely. Account for its dimensions, mounting requirements, and any necessary cable clearances.

### 4. Extrude the Supporting Geometry

Extrude your supporting sketch to the required depth of your device.

Make sure to leave sufficient clearance for connectors, cables, ventilation, and other components.

### 5. Add Fillets

Add 1–5 mm fillets to supporting areas and structural transitions.

Fillets help distribute stress and reduce sharp corners, improving the durability of your printed tray.

### 6. Export and Print

Once your design is complete, export the finished model as an STL file.

Import the STL into your preferred slicer and prepare it for printing.

## Recommended 3D Printing Settings

The following settings are recommended as a starting point:

| Setting | Recommendation |
|---|---|
| Material | PETG |
| Print Orientation | Rack face down |
| Infill | 30% |
| Supports | As needed |

**Material:** PETG is recommended for its strength, durability, and heat resistance.

**Print Orientation:** Print with the rack face against the build plate.

**Supports:** Add supports wherever your customized geometry requires them.

These settings are recommendations and may need adjustment depending on your printer, filament, and final design.

## Design Considerations

Before printing, consider the following:

- **Clearance:** Leave enough room for your device and connected cables.
- **Ventilation:** Avoid obstructing cooling fans or ventilation openings.
- **Strength:** Use sufficient wall thickness and fillets around supporting geometry.
- **Weight:** Consider the weight of your hardware when designing the supports.
- **Fitment:** Double-check your dimensions before printing.

## Contributing

Have an improvement or created an interesting custom design?

Feel free to fork this repository, modify the template, and share your variations with the homelab community.

If you create something using this template, I'd love to see it!

---

**Built for the homelab community. Happy building!**
