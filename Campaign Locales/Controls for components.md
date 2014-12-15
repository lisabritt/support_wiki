| CONTROLS FOR MULTIPLE COMPONENTS | LOCALES | OUTCOMES | EXAMPLE USES | CAMPAIGNS |
|:-------------|:------|:----------|:----------|------------|
|Formatting |render_as:'radiobutton'|Answer options display as radio buttons||Contact Preferences: Plan International; Custom 4:  WWF Austria |
|Formatting |render_as:'checkbox'|Answer options display as check boxes||Custom 2: UNICEF Together, Custom 1: Unicef Together; Custom 4: Save the Children (Urban Leaf)|
|Formatting |render_as:'dropdown'|Answer options display in a drop box||Child Profile Number: World Vision UK; Custom 4: Save the Children USA|
|Formatting |render_as:'freetext'|Answer options displays as a box for the user to enter text in.||Custom 5:  Unicef Germany, Custom 1: Greenpeace Denmark (DL Marketing)|
|Formatting |render_as:'datetime'|Displays a date drop box in the format of the Date of Birth question||Custom 4: WWF Together|
|Formatting |label:'big'|The text is displayed across the whole screen and not in the format / alignment of the questions. This is useful for long lines of text.||Checkpoint: World Vision Aust; Custom 1: UNICEF|
|Formatting |render_as:'freetext',format:'^[0-9]{7}$'|Render as freetext, accept digits between 0-9 with a 7 character limit i.e. a 7 digit passport number|World Vision Australia Custom 5 for passport number||
|Formatting |{component_name}_restricts:'personalidentificationnumber',interestedin_trigger:'Resident'|Restrict components based on the response to a question in another component|interestedin_restricts:'childprofilenumber|childname',interestedin_trigger:'Yes'|Neet Feet World Vision Support|
|Formatting |display:'block'|….. To be confirmed …..|||
||||||
|required:false|Question is NOT mandatory||||Mandatory/Optional rules|required:false|Question is NOT mandatory||||
|required:true|Question IS mandatory|||||required:true|Question IS mandatory||||
|required_if_{componentname}:'x'|Question is mandatory only if a certain response is given to another question i.e. required_if_interestedin:'Non-resident'|required_if_interestedin:'No',restricts:'childregion|childgender|custom_1'|World Vision (Neet Feet)|||required_if_{componentname}:'x'|Question is mandatory only if a certain response is given to another question i.e. required_if_interestedin:'Non-resident'|required_if_interestedin:'No',restricts:'childregion|childgender|custom_1'|World Vision (Neet Feet)||
|required_by_regular_giving:'child_sponsorship'|….. To be confirmed …..||World Vision Australia|||required_by_regular_giving:'child_sponsorship'|….. To be confirmed …..||World Vision Australia||













































































