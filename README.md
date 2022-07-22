# Minecraft Parkour - Map Analitic Tools
This project creates a framework for parkour map analysis inside minecraft server.

Projects resides on couple of domains:

# Base
Map definition (mdefinition) - to start analysis we need some data. This module simplifies minecraft map into blocks the player can stand on, start positions and end positions, also blocks that interrupt player while playing. It's a building block to other analysis


# Ideal time 
The idea of this function is to calculate ideal time of the parkour.

Map simplifier - we simplify the map, using only blocks we will use while making the best time.
Block step-on setter - we set the blocks we will be jump on.
Path creator - after setting blocks we want to create path on, using that and map we create path.
Path time approximizer - using path, we calculate time beetween start and stop of the pass.

# Map structure analysis
Calculation of how many jumps map has, how many paths you can take going through etc.
