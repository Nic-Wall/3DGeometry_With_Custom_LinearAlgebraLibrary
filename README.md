# 3DGeometry_With_Custom_LinearAlgebraLibrary
A general application of my custom made Linear Algebra Library. This project uses OpenGL to display a 3D rotating cube calculated with functions from my Linear Algebra Library.
3DGeometry: Executable: Opens a new window that displays a rotating cube. The cube should rotate in a random direction until it's either rotated 90 degrees or bumped the edge of the window. If it's bumped the edge of the window it'll will inverse it's rotation and continue in that direction until it either hits another wall or finishes the 90 degrees (90 - degrees of rotation before hitting the wall). If it completes it's 90 degree rotation it randomly selects a new direction to rotate in.
CMakeLists.txt: Just a cmake file directing the compiler to my custom made matrix library

Please note: The CMAKE was written with the intention of being compiled on OSX Mac computers.
