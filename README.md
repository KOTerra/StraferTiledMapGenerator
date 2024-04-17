# StraferTiledMapGenerator

A tool helps us automate the generation of objects added to the game world, as well as the matrices associated with pathfinding in map files exported from tiled as json files.

This tool was written and used for Strafer II and its port Strafer Liberator
To generate the pathfinding matrix
To generate Java code with init() functions that can be directly inserted into the WorldSection<11-23> classes
The output is saved in .txt files, and then added to the core project.

The application was written in C++17, and parsing was done with the Tileson library.