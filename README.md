# Image Packer
Takes a Wavefront OBJ with textures and attempts to squash them into a single texture file.

## Why?
I put this together for the purpose of packing complex models with multiple textures (such as ripped game models) into a single `.obj` and texture file for use as custom models in [Tabletop Simulator](http://berserk-games.com/tabletop-simulator/). Initially, I had to do this by hand -- first, combining the textures in GIMP and then going through in Blender moving and scaling UV's to fit. This process felt awfully repetitive, as well as awfully automatable, cue this script.

## Dependencies
Written in [*Python 3*](https://www.python.org/downloads/), and using the great [*Pillow*](https://python-pillow.github.io/) image processing/manipulation library. 
