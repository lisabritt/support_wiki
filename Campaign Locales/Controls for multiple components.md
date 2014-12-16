|Locales|Outcomes|Example uses|Campaigns||Component|Locales|Outcomes|Example uses|Campaigns|
|:-------------|:------|:----------|:----------|------------|
|country:'x'|….. To be confirmed …..||Account number', 'Account name', 'BSB': Greenpeace Denmark (DL Marketing)||Account Name|country:'x'|….. To be confirmed …..||Account number', 'Account name', 'BSB': Greenpeace Denmark (DL Marketing)||
||||||
|generate_bic_iban:true|….. To be confirmed …..||||Account Number|generate_bic_iban:true|….. To be confirmed …..||||
|country:'x'|….. To be confirmed …..|||||country:'x'|….. To be confirmed …..||||
||||||
|No locales as yet|||||Account Type|No locales as yet|||||
||||||
|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||Address  (and Secondary & Tertiary Addresses)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||
|po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|||po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)||
|international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|||international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)||
|enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|||enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland||
|country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|||country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)||
|house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|||house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)||
|house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||||house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional||||
|postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|||postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)||
|address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|||address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)||
|international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|||international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)||
||||||
|No locales as yet|||||Amount|No locales as yet|||||
||||||
|country:'x'|….. To be confirmed …..|display:'block',country:'DK'|Greenpeace Denmark||BSB|country:'x'|….. To be confirmed …..|display:'block',country:'DK'|Greenpeace Denmark||
||||||
|No locales as yet||display:'block'|||Card Number|No locales as yet||display:'block'|||
||||||
|No locales as yet||label:'big'|||Checkpoint|No locales as yet||label:'big'|||
||||||
|No locales as yet||required:false|||Child Gender|No locales as yet||required:false|||
||||||
|No locales as yet||required:false|||Child Name|No locales as yet||required:false|||
||||||
|No locales as yet|||||Child Name & Gender|No locales as yet|||||
||||||
|validate_child:true|….. To be confirmed …..|render_as:'dropdown',required:false|Children with Cancer UK (P2P)||Child Profile Number|validate_child:true|….. To be confirmed …..|render_as:'dropdown',required:false|Children with Cancer UK (P2P)||
||||||
|No locales as yet||required:false|Children with Cancer UK (P2P)||Child Region|No locales as yet||required:false|Children with Cancer UK (P2P)||
||||||
|validate_child:false|….. To be confirmed …..||World Vision Australia||Child Sponsorship|validate_child:false|….. To be confirmed …..||World Vision Australia||
|validate_child:true|….. To be confirmed …..||World Vision Australia|||validate_child:true|….. To be confirmed …..||World Vision Australia||
|required_by_regular_giving:'child_sponsorship|….. To be confirmed …..||World Vision Australia|||required_by_regular_giving:'child_sponsorship|….. To be confirmed …..||World Vision Australia||
||||||
|No locales as yet|||||Consumer Price Index|No locales as yet|||||
||||||
|validation_workflow:'Phone_home_phone or Phone_mobile_phone',validation_workflow_err_msg:'CONTACT_BLOCK_ONE_PHONE'|If the Preferred Phone is home phone, then home phone is mandatory and mobile is optional. If Preferred Phone is mobile then mobile is mandatory and home phone is optional.||ActionAid (another)||Contact block|validation_workflow:'Phone_home_phone or Phone_mobile_phone',validation_workflow_err_msg:'CONTACT_BLOCK_ONE_PHONE'|If the Preferred Phone is home phone, then home phone is mandatory and mobile is optional. If Preferred Phone is mobile then mobile is mandatory and home phone is optional.||ActionAid (another)||
||||||
|No locales as yet||required:false,label:'big',render_as:'radiobutton'|||Contact Preferences|No locales as yet||required:false,label:'big',render_as:'radiobutton'|||
||||||
|No locales as yet||display:'block'|||Credit card failed validations|No locales as yet||display:'block'|||
||||||
|No locales as yet||display:'block'|||Credit Card Type|No locales as yet||display:'block'|||
||||||
|No locales as yet|||||Currency Type|No locales as yet|||||
||||||
|See: Formatting for components|||||Custom Components 1-5|See: Formatting for components|||||
||||||
|hide_date_and_month:true|Shows only the year of birth in Date of Birth|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support||Date of birth|hide_date_and_month:true|Shows only the year of birth in Date of Birth|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support||
|hide_date:true|Shows only the month and year of birth in Date of Birth|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support|||hide_date:true|Shows only the month and year of birth in Date of Birth|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support||
|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support|||required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support||
||||||
|No locales as yet|||||Debit Communications|No locales as yet|||||
||||||
|No locales as yet|||||Debit Failed Validations|No locales as yet|||||
||||||
|No locales as yet||label:'big'|||Debit Tax|No locales as yet||label:'big'|||
||||||
|No locales as yet||display:'block'|||Direct Debit IBAN|No locales as yet||display:'block'|||
||||||
|No locales as yet||display:'block', required:false|||Direct Debit SWIFT|No locales as yet||display:'block', required:false|||
||||||
|generate_bic_iban:true|Adds the BIC/IBAN components to the form|display:'block',generate_bic_iban:true|Account number: Barnadoes Ireland||Direct debit type|generate_bic_iban:true|Adds the BIC/IBAN components to the form|display:'block',generate_bic_iban:true|Account number: Barnadoes Ireland||
||||||
|No locales as yet||required:false|||Email|No locales as yet||required:false|||
||||||
|minimum_months:x|Logic to control the number of months from the current date that the credit card expiry date must have before it is accepted. The minimum time is the value you replace x with|minimum_months:2' creates logic to only accept credit cards that expire after 2 months from the current date|||Expiry Date|minimum_months:x|Logic to control the number of months from the current date that the credit card expiry date must have before it is accepted. The minimum time is the value you replace x with|minimum_months:2' creates logic to only accept credit cards that expire after 2 months from the current date|||
||||||
|No locales as yet||display:'block'|||Financial Institution|No locales as yet||display:'block'|||
||||||
|No locales as yet|||||First Name|No locales as yet|||||
||||||
|No locales as yet||required:false|||Gender|No locales as yet||required:false|||
||||||
|ntp_option:true|….. To be confirmed …..|required:true,label:'big', ntp_option:true|British Red Cross||Gift Aid|ntp_option:true|….. To be confirmed …..|required:true,label:'big', ntp_option:true|British Red Cross||
||||||
|data_set:'WVA Gifts XMas'|Attaches a Campaign Data Set as the answer option for the Gifts component|Uses the Campaign Data Set 'WVA Gifts XMas' as a drop list|||Gifts|data_set:'WVA Gifts XMas'|Attaches a Campaign Data Set as the answer option for the Gifts component|Uses the Campaign Data Set 'WVA Gifts XMas' as a drop list|||
||||||
|No locales as yet|||||Have Heard Of|No locales as yet|||||
||||||
|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false|||Home Phone|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false|||
||||||
|No locales as yet|||||ID Type Sighted|No locales as yet|||||
||||||
|No locales as yet|||||Income|No locales as yet|||||
||||||
|Interested In|interestedin_restricts:'{component_name}\|{component_name}\|{component_name}\|{component_name},interestedin_trigger:'{answer trigger to restrict the other components}'|Based on the response to the Interested In component, other components are hidden or displayed|interestedin_restricts:'childprofilenumber\|childname\|regulargiving\|transactiontype\|paymentdays\|paymentmonth',interestedin_trigger:'Yes'|World Vision Australia|
||||||
|No locales as yet|||||Interested In Volunteering|No locales as yet|||||
||||||
|No locales as yet|||||Last Name|No locales as yet|||||
||||||
|No locales as yet|||||Location|No locales as yet|||||
||||||
|No locales as yet|||||Location Type|No locales as yet|||||
||||||
|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false|Greenpeace Canada English||Mobile Phone|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false|Greenpeace Canada English||
|prefixes:''|….. To be confirmed …..||Greenpeace Mexico|||prefixes:''|….. To be confirmed …..||Greenpeace Mexico||
||||||
|currency:'x'|When you replace 'x' with the currency symbol for your currency ($, £ etc), it will display that symbol on the signature screen| currency:'$' will display $ on the screen. Other currencies that can be used: 'Php', 'Kr', 'Rp', '€', ''|Monthly Amount: Greenpeace Denmark (ML Marketing), Save the Children Philippines (Equality Marketing)||Monthly Amount|currency:'x'|When you replace 'x' with the currency symbol for your currency ($, £ etc), it will display that symbol on the signature screen| currency:'$' will display $ on the screen. Other currencies that can be used: 'Php', 'Kr', 'Rp', '€', ''|Monthly Amount: Greenpeace Denmark (ML Marketing), Save the Children Philippines (Equality Marketing)||
|free_amount:false|Removes the free text box from the screen along with any associated text |label:'big',free_amount:false|Children with Cancer Support|||free_amount:false|Removes the free text box from the screen along with any associated text |label:'big',free_amount:false|Children with Cancer Support||
||||||
|No locales as yet||display:'block'|||Name on Card|No locales as yet||display:'block'|||
||||||
|use_campaign_csv_values:false|Displays the Payment Days as a drop list from 1st - 28th|use_campaign_csv_values:false,required:false|Payment days - World Vision UK||Payment Days|use_campaign_csv_values:false|Displays the Payment Days as a drop list from 1st - 28th|use_campaign_csv_values:false,required:false|Payment days - World Vision UK||
|ordinalize:false|Displays the Payment Days from the campaign setup as numbers only||UNICEF Austria|||ordinalize:false|Displays the Payment Days from the campaign setup as numbers only||UNICEF Austria||
|ordinalize:true|Displays the Payment Days from the campaign setup as 1st, 2nd, 3rd etc|||||ordinalize:true|Displays the Payment Days from the campaign setup as 1st, 2nd, 3rd etc||||
||||||
|max_days_for_payment: x|When you replace x with the maximum days of payment, it will display that number of days in months i.e. max_days_for_payment: 60 will display the next two months from the current date|max_days_for_payment: 60,required:true|Oxfam IE Support||Payment Month|max_days_for_payment: x|When you replace x with the maximum days of payment, it will display that number of days in months i.e. max_days_for_payment: 60 will display the next two months from the current date|max_days_for_payment: 60,required:true|Oxfam IE Support||
||||||
|options:'x\|y\|z'|Adds x, y, z options as payment types|options:'credit\|debit\|other'|British Heart Foundation (Clear)||Payment type|options:'x\|y\|z'|Adds x, y, z options as payment types|options:'credit\|debit\|other'|British Heart Foundation (Clear)||
|debit_components:'custom_2\|Personalidentificationnumber\|Interestedin'\|….. To be confirmed …..|debit_components:'directdebitiban', display:'block', options:'credit\|debit\|other'|Greenpeace Spain Support|||debit_components:'custom_2\|Personalidentificationnumber\|Interestedin'|….. To be confirmed …..|debit_components:'directdebitiban', display:'block', options:'credit\|debit\|other'|Greenpeace Spain Support||
|other_components:'custom_4\|custom_5'|….. To be confirmed …..||World Vision Australia|||other_components:'custom_4\|custom_5'|….. To be confirmed …..||World Vision Australia||
||||||
|No locales as yet|||||Personal Identification Number|No locales as yet|||||
||||||
|No locales as yet|||||Place of Birth|No locales as yet|||||
||||||
|No locales as yet||required:false|||Preferred Phone|No locales as yet||required:false|||
||||||
|No locales as yet|||||Prefers Email Updates|No locales as yet|||||
||||||
|No locales as yet||required:false|||Profession|No locales as yet||required:false|||
||||||
|No locales as yet||required:true|||Receive Communications|No locales as yet||required:true|||
||||||
|restricts:'\|x\|x\|x'|Restricts the x components that are contained within the ' '|restricts:'PersonalDetails\|secondary_address'|World Vision Australia||Restrict Component Visibility|restricts:'\|x\|x\|x'|Restricts the x components that are contained within the ' '|restricts:'PersonalDetails\|secondary_address'|World Vision Australia||
|required_if_interestedin:'x\|y'|Sets the component as required based on the response to another question|required_if_interestedin:'Go Wild Membership – Donor is not legal guardian of recipient\|Go Wild Membership – Donor is legal guardian of recipient',restricts:'custom_1\|custom_2\|custom_3\|custom_4\|custom_5\|secondary_address'|WWF WORLD CUP (Together)|||required_if_interestedin:'x\|y'|Sets the component as required based on the response to another question|required_if_interestedin:'Go Wild Membership – Donor is not legal guardian of recipient\|Go Wild Membership – Donor is legal guardian of recipient',restricts:'custom_1\|custom_2\|custom_3\|custom_4\|custom_5\|secondary_address'|WWF WORLD CUP (Together)||
||||||
|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||Secondary Address (and Address and Tertiary Address)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||
|po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|||po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)||
|international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|||international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)||
|enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|||enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland||
|country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|||country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)||
|house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|||house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)||
|house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||||house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional||||
|postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|||postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)||
|address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|||address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)||
|international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|||international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)||
||||||
|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:0,required:false|WWF Austria||Secondary Person Details|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:0,required:false|WWF Austria||
||||||
|No locales as yet||required:true|||Share Details|No locales as yet||required:true|||
||||||
|editable:true|Displays a free text box for shopping centre||Wesley ASAP||Shopping Centre|editable:true|Displays a free text box for shopping centre||Wesley ASAP||
||||||
|No locales as yet|||||Terms & Conditions|No locales as yet|||||
||||||
|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||Tertiary Address (and Address and Secondary Address)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)||
|po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|||po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)||
|international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|||international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)||
|enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|||enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland||
|country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|||country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)||
|house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|||house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)||
|house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||||house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional||||
|postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|||postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)||
|address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|||address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)||
|international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|||international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)||
||||||
|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required:false, required_age:0|PDSA sandbox||Tertiary Person Details|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required:false, required_age:0|PDSA sandbox||
||||||
|No locales as yet|||||Tied Funding|No locales as yet|||||
||||||
|No locales as yet||required:false|Oxfam (Dialogue Direct)||Title|No locales as yet||required:false|Oxfam (Dialogue Direct)||
||||||
|No locales as yet||required:true|Save the Children (Urban Leaf)||Transaction Type|No locales as yet||required:true|Save the Children (Urban Leaf)||
||||||
|length:'x'|Enforces a character limit of 'x' characters|required:false|||Work phone|length:'x'|Enforces a character limit of 'x' characters|required:false|||