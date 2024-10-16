This is the standard visual style that ships with the OSM2World 3D renderer. 

To use this style file, place it (and the textures folder) in the OSM2World directory
and set the "--config standard.properties" option on the command line when starting OSM2World.
For more options and documentation, see the OpenStreetMap wiki:
http://wiki.osm.org/OSM2World/Configuration_file

Many of the textures were contributed by members of the OpenStreetMap community and released into the Public Domain. Visit http://wiki.openstreetmap.org/wiki/Texture_Library to find out about the contributors and discover more texture images.

The configuration file and all additional textures have likewise been released into the Public Domain (see http://creativecommons.org/publicdomain/zero/1.0/).

## Conventions for assets

- Textures should preferably use power-of-two dimensions.
- When using CLAMP mode for textures with a transparent border which do not cover the entire geometry, add 25% transparent padding (12.5% on each side, relative to the original image size) and set padding to 0.1 in the .properties file.

- Models face towards positive z direction in glTF (i.e. towards the front).
- Models can use FF00FF as a placeholder color to be replaced with a per-instance color by OSM2World.
