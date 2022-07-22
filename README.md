# Minecraft Parkour - Map Analitic Tools
This project creates a framework for parkour map analysis inside minecraft server.

Projects resides on couple of domains:

# Base

Map definition (mdefinition) - to start analysis we need some data. This module simplifies minecraft map into blocks the player can stand on, start positions and end positions, also blocks that interrupt player while playing. It's a building block to other analysis


# Ideal time 

Map simplifier - we simplify the map, using only blocks we will use while making the best time.

Path time approximizer - using map and path, we calculate time beetween start and stop

