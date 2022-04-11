## &lt;Display_Direction&gt; 
----
''REQUIRED''

This class defines the correct orientation for displaying the array axes associated with a single image plane (that is, the ''Line'' and ''Sample'' axes).

### &lt;comment&gt; 



''OPTIONAL''

Another opportunity for free-format comments.

### &lt;horizontal_display_axis&gt; 



''REQUIRED''

This attribute identifies which axis of the array is considered the horizontal (or "sample") axis by referencing the ''&lt;axis_name&gt;'' value.  The value ''must'' match the name exactly (i.e., case counts).

### &lt;horizontal_display_direction&gt; 



''REQUIRED''

This attribute indicates the direction in which pixels should be drawn sequentially along the horizontal axis of the display device.  It must have one of these two values (case and embedded blanks are significant):

* '''Left to Right'''
* '''Right to Left'''

### &lt;vertical_display_axis&gt; 



''REQUIRED''

This attribute identifies which axis of the array is considered the vertical (or "line") axis by reference the ''&lt;axis_name&gt;'' value.  The value ''must'' match the name exactly (i.e., case counts).

### &lt;vertical_display_direction&gt; 



''REQUIRED''

This attribute indicates the direction in which lines of pixels should be stacked sequentially along the vertical direction of the display device.  It must have one of these two values (case and embedded blanks are significant):

* '''Top to Bottom'''
* '''Bottom to Top'''
