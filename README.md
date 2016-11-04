# geoalgo_lab1
Computational Geometry, D7013E, Lab 1


Known bugs:
The calculation of the lower hull may overwrite the line drawn for the last two points by the upper hull, as it is not part of the lower hull. This is purely cosmetical however, the previous result is not discarded in the data model.

Lower hull sometimes digs a very deep hole for itself into the hull. Not convex at all. Unknown reason. When this happens an obviously false result is obtained.