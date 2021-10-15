# wfc-minecraft-plugin
Minecraft plugin for 3D Wave Function Collapse.

<iframe width="560" height="315" src="https://www.youtube.com/embed/O7m775lzlkA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# How to install
Build this plugin and put to bukkit plugins directory.
Build [fast-wfc-3d-stdio](https://github.com/Lunuy/fast-wfc-3d-stdio) and copy wfc_stdio.exe to "(bukkit directory)/exe/wfc_stdio.exe".

# Usage
## Select area
You can set area using stone axe like worldedit's wood axe.
Unlike worldedit plugin, area will doesn't contain x, y, z coordinate that you right/left clicked block's coordinate.

## Commands
### /input
Set selected area to input area.
### /gen N periodic_input_x periodic_input_y periodic_input_z periodic_output_x periodic_output_y periodic_output_z
Generate blocks to selected area using WFC based on input area. (Selected area will be cleared)
### /kgen N periodic_input_x periodic_input_y periodic_input_z periodic_output_x periodic_output_y periodic_output_z
Keep-gen. Generate blocks, but keeping already placed blocks.
### /genstop
Stop generating blocks.
### /cl
Clear selected area.
