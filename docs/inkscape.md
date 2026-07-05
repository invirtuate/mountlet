# inkscape

## Overview
Inkscape can be used to make and edit parts

## Notes
Its possible to combine multiple parts to form a shape, be cautious when doing this though as the final part must be a single part.

Do not add bends as a shape, just do lines.

Combine shapes to produce a final part:
- Division of two shapes will results in one of the shapes cutting through the other one; you want this
- Combine paths
- Difference: Use difference in inkscape to cut out holes to main piece

Use outline to confirm everything looks good

Bends:
- U-Channel: Must be 2:1, or must be shorter than 3" and can be 1:1
- Flange: A bend cannot be performed if the minimum flange length is not met
- Bend relief: A bend relief prevents bulging/cracking at the bend, refer to `Bend Relief Depth` on the material for exact size. It is measured from the center of the bend line to the bottom of the relief. A bend relief can be a square, circular, triangular, or obround
- Do not allow bend lines to touch this can cause entity errors

Holes/Cutouts:
- Should be at least double the distance from an edge as the thickness of the material
- Cutouts/holes should be at least 6mm (0.236") away from the bend line to avoid distortion
- Hole minimum size is 0.015"

**Cannot combine or do division on multiple shapes at the same time**

## Troubleshooting
`Bend Minimum Flange Contact Error`
- This means the material is not long enough to do the bend. If parts are being joined make sure they're combined first before adding bends.

`Entity ....`
- Ensure all shapes are combined into one and **DO NOT** forget to `Path > Union`
