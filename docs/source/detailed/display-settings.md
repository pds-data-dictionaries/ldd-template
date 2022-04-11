The display dictionary is a ''discipline dictionary'', which means that its classes will appear in the ''&lt;Discipline_Area&gt;'' at the bottom of the ''&lt;Observation_Area&gt;'' in observational product labels (and in the ''&lt;Context_Area&gt;'', if appropriate, in non-observational products).  The classes in this dictionary define the appropriate way to draw or otherwise display array-type data objects in order to be able to correctly interpret geometric or other quantities referenced to, e.g., an image elsewhere in the label.

''Last Update: 2020-07-31, for version 1B00 of this dictionary.''

# &lt;Display_Settings&gt; 

''REQUIRED''

This is the main wrapper class for the Display Dictionary.  It must be used whenever you want or need to include display information in any label that includes one or more array-type objects, in which case it is repeated for each object that needs display information.
