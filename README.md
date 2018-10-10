# Position Mask
<strong>To create quick mask using the data contained in the render of "World Position" or "Ref Position".</strong>

This node has several advantages compared to other same kind of tools.

The center of the mask is not set by a “color picker” but with a 2D Position knob which executes callbacks. So it is possible to precisely place the mask regardless of the channel viewed. With the “Overlay” mode, the tool is visually even more convenient.
Visualization in 3D space is also a real advantage in a certain situation, as well as the integration of the “Unpremult” and “Premult” which makes it possible to obtain clean edges.
The tool is fast and easy to use, but still has to have the position pass 😉

<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/ex1.gif" alt="" />
<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/ex4.gif" alt="" />
<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/ex3.gif" alt="" />

<strong>Tool details:</strong>

<strong>P Channel:</strong> To select the Position Pass channel.
  
<strong>Shape:</strong> To Choose between "sphere" or "cube" the shape that you need.

<strong>Center:</strong> To adjust the center of the shape.

<strong>Scale:</strong> To adjust the scale as you want (global and feather).

<strong>Overlay:</strong> To show the mask on overlay (looking the rgb) and to change the color (none, red, green, blue or black).

<strong>3D Options:</strong>

- To transform the shape (volume) in 3D.
- To visualize in 3D the input image and the volume that makes the mask. This uses a "position to point" node and it gives the possibility to adjust the "Point Detail" and the "Point Size".

<strong>(Un)Premult:</strong> To keep nice shapes on edges.

<strong>Mix:</strong> To make the mask more or less transparent.


For the creation of this tool, I was strongly inspired by the article written by <a style="font-weight: inherit; font-style: inherit; color: #ff8f00;" title="Nukepedia Tutorial" href="http://www.nukepedia.com/written-tutorials/expressions-101" target="_blank" rel="noopener">Matt Estela and Pedro Andrade</a> and similar tools, such as those from <a style="font-weight: inherit; font-style: inherit; color: #ff8f00;" title="Nukepedia Tool" href="http://www.nukepedia.com/toolsets/3d/wptk" target="_blank" rel="noopener">Ivan Kokov</a>.
