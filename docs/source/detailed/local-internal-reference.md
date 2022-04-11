## &lt;pds:Local_Internal_Reference&gt; 
----
''REQUIRED''

This class is used to identify the specific array-type object to which these display settings apply.

Note that the class name ''Local_Internal_Reference'' and the attributes within it all come from the PDS core namespace. Depending on how you set up prefixes in your label, that may mean that there will be no prefix on the class name and its attributes, or you will use the "pds:" prefix, to indicate the change in namespace. See the [Local Dictionaries](https://sbnwiki.astro.umd.edu/wiki/Using_Local_Dictionaries) page on this wiki for gory details on that.  For the purposes of this description, we'll indicate the attributes in the PDS core namespace by adding an explicit "pds:" namespace abbreviation prefix to them.

### &lt;pds:comment&gt; 



''OPTIONAL''

This is a free-text field for any clarifying comments you might wish to include.

### &lt;pds:local_identifier_reference&gt; 



''REQUIRED''

This attribute identifies the array object to which the display settings apply, by citing the ''local_identifier'' value from the associated array object. All array-type objects have an optional ''&lt;local_identifier&gt;'' attribute, which, when present, must have a value that is unique within the label.  You must assign ''local_identifier'' values to your arrays when you are providing display information. 

### &lt;pds:local_reference_type&gt; 


 
''REQUIRED''

This must have the value ''display_settings_to_array''.