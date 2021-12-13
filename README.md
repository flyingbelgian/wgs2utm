# wgs2utm
Batch convert WGS dd°mm'ss" coordinates to UTM


The user selects a csv file using GUI.
The file must have a set format, which is why a sample source file is included in the download.

The coordinates in the csv are then batch converted to UTM and a new csv is created that has the original coordinates as well as the utm coordinates.

This script would not have been possible (or at least a lot harder) without the excellent work by twpayne on his utm.py script (https://gist.github.com/twpayne/4409500) and the pyproj team.
