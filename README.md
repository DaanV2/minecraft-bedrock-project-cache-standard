# Minecraft Bedrock Project Standard

The goal of this standard is to unify multiple program, analyzers, generators or
intellisense for example. This is accomplished through a universal data caching
format. A secondary goal is also to provided sample files for unit testing

**Content**

- [Minecraft Bedrock Project Standard](#minecraft-bedrock-project-standard)
	- [Data Caching](#data-caching)

## Data Caching

Any program or tool may during its operation and traversing of the files gather
data, for better performance it sometimes better to save a summarized version of
this data to disk. So when the program starts up it already has data it can
provided to the data will it might preform a rescan and save that data for a
latter use.

This standard provided a format of what that data at the bare minimum must
contain, additional data is allowed, but can be overwritten by any other tool.
Any tool or program may create an unique subfolder with additional data for its
own record keeping.

All data will be stored in a universal folder called `.minecraft-bedrock` there
files can be found for each type of data by minecraft it self:

- [blocks.json](data%20caching/tags/version%201.0.0.md)
- [bp_animations.json](data%20caching/bp_animations/version%201.0.0.md)
- [bp_animation_controllers.json](data%20caching/bp_animation_controllers/version%201.0.0.md)
- [entities.json](data%20caching/entities/version%201.0.0.md)
- [families.json](data%20caching/families/version%201.0.0.md)
- [items.json](data%20caching/items/version%201.0.0.md)
- [names.json](data%20caching/names/version%201.0.0.md)
- [objectives.json](data%20caching/objectives/version%201.0.0.md)
- [particles.json](data%20caching/particles/version%201.0.0.md)
- [render_controller.json](data%20caching/render_controllers/version%201.0.0.md)
- [rp_animation.json](data%20caching/rp_animations/version%201.0.0.md)
- [rp_animation_controller.json](data%20caching/rp_animation_controllers/version%201.0.0.md)
- [sounds.json](data%20caching/sounds/version%201.0.0.md)
- [tags.json](data%20caching/tags/version%201.0.0.md)

A wider specification can be found in
[data caching](data%20caching/data%20caching.md)
