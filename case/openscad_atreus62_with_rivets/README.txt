Modified atreus(62) case to use threaded rivet nut inserts on the
bottom of the case for a neater look. Following parameters must
be adjusted depending on size of screws and laser cutter kerf:

 - screw_hole_radius
 - rivets_hole_radius
 - switch_plate_hole_radius
 - switch_hole_size

I added an additional variable for switch plate screw hole radius
as, in my case, the company cutting the plate (laserboost) didn't
want a kerf set, while the company cutting the acrylic layer
wanted a kerf of 0.2. Please adjust as needed.

dxf file ready for laserboost in directory
atreus62_laserboost_steel_plate.

svg file ready for vectorealism in directory
atreus62_vectorealism_acrylic_case. 
