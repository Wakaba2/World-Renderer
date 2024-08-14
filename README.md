# World Renderer  
This plugin allows you to render objects on the sky and world  
  
![gif](https://i.imgur.com/H9lEztq.png)  
  
# Templates  
There are many procedure templates in the directory "templates."  
You can download and use them just like the built-in templates.  
  
# Changelog  
v1.8.3  
You need to set an overlay target in order to render overlays  
Changed the rendering system for shape overlays  
Added the procedure "Set sky light color"  
Added the procedure "Set block light color"  
Removed the procedure "Multiply sky light color"  
Removed the procedure "Multiply block light color"  
Removed the procedure "Set light pixel"  
Some fixes and improvements  
Fixed some bugs  
  
v1.8.2  
The event trigger "Graphics - Render models" was renamed "Graphics - Render world"  
The procedure list "Model" was renamed "World"  
Added a procedure to render a line, which can be used for the event trigger "Graphics - Render world"  
Some fixes and improvements  
Fixed some bugs  
  
v1.8.1  
In order to disable vanilla clouds, sky, weather and weather effects, you will need to return logic "true" on each of event triggers  
Some fixes and improvements  
  
v1.8.0  
Added support for NeoForge 1.20.6  
Added support for custom light colors  
Added some procedures to get data for rendering  
Removed event trigger "Graphics - render texts"  
Texts can be rendered on event trigger "Graphics - render models"  
Some fixes and improvements  
Fixed some bugs  
  
v1.7.1  
Some fixes and improvements  
Fixed some bugs  
  
v1.7.0  
Added procedures and an event trigger to render overlays  
Event trigger "Graphics - Render shapes" can render overlays  
Added procedure templates for overlays  
Some fixes and improvements  
Fixed some bugs  
  
v1.6.5  
Some fixes and improvements  
  
v1.6.4  
Some fixes and improvements  
  
v1.6.3  
Some fixes and improvements  
Fixed some bugs  
  
v1.6.2  
Added a procedure to set a color mask  
Some fixes and improvements  
  
v1.6.1  
Fixed some bugs  
  
v1.6.0  
Added procedures and an event trigger to render texts  
Added a procedure to iterate block entities  
Added a procedure to get an entity the player is looking at  
Added a variable "shape" to get shapes from other procedure elements  
Added a procedure template "Graphics - Shape - Render a block"  
Removed a procedure template "Graphics - Shape - Render a head"  
Some fixes and improvements  
  
v1.5.5  
Added a procedure to iterate weather positions  
Improved a procedure template "Graphics - Weather - Render weather"  
Fixed some bugs  
  
v1.5.4  
Added a procedure template "Graphics - Shape - Render a cone"  
Added a procedure template "Graphics - Shape - Render a cylinder"  
Added a procedure template "Graphics - Shape - Render a head"  
Added a procedure template "Graphics - Shape - Render a sphere"  
Added a procedure template "Graphics - Shape - Render a torus"  
Added a procedure template "Graphics - Shape - Render an octahedron"  
Improved procedure lists  
Some fixes and improvements  
  
v1.5.3  
Added a procedure to check whether the game is paused  
Added a procedure to set a shape offset  
Some fixes and improvements  
Fixed some bugs  
  
v1.5.2  
Fixed some bugs  
  
v1.5.1  
Added a procedure to set up dimensions with constant lights  
Added a procedure to get a render distance  
Added a procedure to set depth masking  
Added a procedure to set a render target for shapes  
Added a procedure to set a coordinate system for shapes  
Added a support for MCreator 2024.1 - Forge 1.19.2  
Some fixes and improvements  
  
v1.5.0  
Added an event trigger "Render shapes" to render shapes like triangles and quads etc.  
Added an event trigger "Render models" to render blocks, items, and entities  
Added a procedure for block rendering   
Added a procedure for item rendering  
Improved procedure lists  
Added a support for MCreator 2023.4 - Forge 1.19.2  
Added supports for MCreator 2024.1 - Forge 1.19.4 / 1.20.1 / NeoForge 1.20.4  
Stopped supports for Forge 1.14.4 / 1.15.2 / 1.16.5 / 1.17.1 / 1.18.2  
Fixed some bugs  
  
v1.4.6  
Fixed some bugs  
  
v1.4.5  
Added an event trigger "Set effects", which can disable clouds, sky, rain/snow, etc. Also, procedure templates is available  
Added a procedure "Set cloud height"  
Added a procedure "Set ground effects"  
Added a procedure "Set sky type"  
Added a procedure "Set forced bright lights"  
Added a procedure "Set constant ambient lights"  
Fixed some bugs  
  
v1.4.4  
Fixed some bugs  
  
v1.4.3  
Fixed some bugs  
  
v1.4.2  
Added a procedure "Render particle", which it can use on an event trigger "Render world"  
  
v1.4.1  
Fixed stitching of sky box. See the guide for details
  
v1.4.0  
Added a procedure "Use stencil"  
Fixed some bugs  
  
v1.3.4  
Fixed some bugs  
  
v1.3.3  
Added a blend mode "CLOUDS"  
Added a procedure "Set color mask"  
Fixed some bugs  
  
v1.3.2  
Fixed some bugs  
  
v1.3.1  
Fixed some bugs  
  
v1.3.0  
Added a trigger and procedure to render clouds  
Added a trigger and procedure to render rain and snow  
Added a trigger and procedure to add effects for rain and snow  
Added a procedure "Set cloud scale"  
Added a procedure "Get cloud color"  
Fixed some bugs  
  
v1.2.1  
Fixed some bugs  
  
v1.2.0  
Update procedure lists  
The sky is always cleared in custom dimension  
Camera position has been removed from dependencies. Alternatively, it is possible to get camera position using new procedures  
Added a procedure to identify camera type  
Added a procedure to get set texture width  
Added a procedure to get set texture height  
Added a procedure to get world height on client side  
Added procedures to render objects using buffers  
Fixed some bugs  
  
v1.1.1  
Fixed some bugs (Forge 1.18.2 / 1.19.2 / 1.19.4 / 1.20.1)  
  
v1.1.0  
Added a support for NeoForge 1.20.1 (MCreator 2023.3 - 1.18.2 / 1.19.2 / 1.19.4 / 1.20.1 / NeoForge 1.20.1)  
Forge 1.17.1 Merged with Forge 1.15.2 / 1.16.5 (MCreator 2022.3)  
Added a procedure "Render overworld"  
Improved advenced rendering  
Fixed some bugs  
  
v1.0.2  
Added a support for Forge 1.20.1 (MCreator 2023.2 - 1.18.2 / 1.19.2 / 1.19.4 / 1.20.1)  
Added a support for Forge 1.15.2 (MCreator 2022.3 - 1.15.2 / 1.16.5)  
Fixed some bugs  
  
v1.0.1  
Added support for appropriate MCreator versions  
  
v1.0.0  
Added a procedure "Render sky box"  
Fixed some bugs  
  
# Information:
This plugin supports Forge 1.19.2 / 1.19.4 / 1.20.1 / NeoForge 1.20.4 / 1.20.6  
License: MITLicense  
