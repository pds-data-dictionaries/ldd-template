## &lt;Movie_Display_Settings&gt; 
----
''OPTIONAL''

Use this class to define a time axis and parameters for displaying the associated array object as a movie.

### &lt;time_display_axis&gt; 



''REQUIRED''

The value of this attribute must correspond to the ''&lt;axis-name&gt;'' value of one of the axes of the relevant array-type object.  This is the axis that well be
considered the "time" axis.  Logically, it must ''not'' be the same value as either ''&lt;horizontal_display_axis&gt;'' or ''&lt;vertical_display_axis&gt;'' of the ''&lt;Display_Direction&gt;'' class, but this is not validate - so type carefully.

### &lt;comment&gt; 



''OPTIONAL''

Free-format text for additional notes to the user.

### &lt;frame_rate&gt; 



''OPTIONAL''

This attribute indicates how many images (i.e, "frames") should be displayed each second.  You must specify a unit of "frames/s".  For example:

:::<code>&lt;frame_rate unit="frames/s"&gt;12&lt;/frame_rate&gt;</code>

The minimum valid value for this attribute is 1.0.

### &lt;loop_flag&gt; 



''OPTIONAL''

This attribute will contain the value ''true'' if the movie should be looped, or ''false'' if not.

### &lt;loop_count&gt; 



''OPTIONAL''

This attribute contains the number of times the movie should be looped before being stopped. It may have a minimum value of one (1).

### &lt;loop_delay&gt; 



''OPTIONAL''

This attribute give the amount of time to pause between playback loops. You must include a time unit with the value, e.g.:

:::<code>&lt;loop_delay unit="ms"&gt;500&lt;/loop_delay&gt;</code>

This may have a minimum value of zero (0).

### &lt;loop_back_and_forth_flag&gt; 



''OPTIONAL''

This attribute will contain the value ''true'' if the movie should be played alternately forward and in reverse while looping; or ''false'' if it should only be played in the forward direction when looping.  '''''Note''''' that this attribute only makes logical sense in the presence of other looping attributes, but as of this writing this is neither required nor validated.
