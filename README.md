# KochVase

A vase design and 3d print

This is a design project in Autodesk Inventor.

The Koch shape was first drafted in one plane. Then it was copied off to seperate planes with different scaling. A loft was created from these 2D sketches. After that the sketches were rotated to a certain degree to create the twisting motion. This twist was done after the lofting process to maintain the vertice connections properly arranged. Otherwise, Inventor will always choose the path with least distance when lofting.

For 3D printing the solid was exported in STL form. Slicing for 3D printing was done using Simplify 3D. However, top slid layer and internal fill was kept at 0 to create the vase. This option was chosen over single perimeter shell printing is to have a stronger body. The printing was done in PLA and took about 2 hours at 200 micron layer height.
