## &lt;Color_Display_Settings&gt; 
----
''OPTIONAL''

Use this class if your array object is an RGB color image, or a banded image for which you would like to define a default set of channels to be interpreted as RGB levels.

### &lt;color_display_axis&gt; 



''REQUIRED''

The value of this attribute must correspond to the ''&lt;axis_name&gt;'' value of one of the axes of the relevant array-type object.  This is the axis that well be
considered the "color" or "band" axis.  Logically, it must ''not'' be the same
value as found in either the ''&lt;horizontal_display_axis&gt;'' or ''&lt;vertical_display_axis&gt;'' of the ''&lt;Display_Direction&gt;'' class, but this is not validated - so type carefully.

### &lt;comment&gt; 



''OPTIONAL''

Free-format text for additional notes to users.

### &lt;red_channel_band&gt; 



''REQUIRED''

This attribute is the subscript to be used in the named ''color_display_axis'' 
for the red (R) value.  '''''Note''''' that the first element along this axis is considered to have a subscript of 1 (one).

### &lt;green_channel_band&gt; 



''REQUIRED''

This attribute is the subscript to be used in the named ''color_display_axis'' for the green (G) value.  '''''Note''''' that the first element along this axis is considered to have a subscript of 1 (one).

### &lt;blue_channel_band&gt; 



''REQUIRED''

This attribute is the subscript to be used in the named ''color_display_axis'' for the blue (B) value.  '''''Note''''' that the first element along this axis is considered to have a subscript of 1 (one).