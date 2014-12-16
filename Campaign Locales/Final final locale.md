| COMPONENT | LOCALES | OUTCOMES | EXAMPLE USES | CAMPAIGNS |
|:-------------|:--|:--------------------|:----------|------------|
|Account Name|country:'x'|….. To be confirmed …..||Account number', 'Account name', 'BSB': Greenpeace Denmark (DL Marketing)|
|Account Number|generate_bic_iban:true|….. To be confirmed …..|||
|   |country:'x'|….. To be confirmed …..|||
|Account Type|No locales as yet||||
|Address  (and Secondary & Tertiary Addresses)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)|
|   |po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|
|   |international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|
|   |enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|
|   |country:'{country_abbreviation}',language:'{language_abbreviation}'|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||
|   |postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|
|   |address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|
|   |international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|
|Amount|No locales as yet||||
|BSB|country:'x'|….. To be confirmed …..|display:'block',country:'DK'|Greenpeace Denmark|
|Card Number|No locales as yet||display:'block'||
|Checkpoint|No locales as yet||label:'big'||
|Child Gender|No locales as yet||required:false||
|Child Name|No locales as yet||required:false||
|Child Name & Gender|No locales as yet||||
|Child Profile Number|validate_child:true|….. To be confirmed …..|render_as:'dropdown',required:false|Children with Cancer UK (P2P)|
|Child Region|No locales as yet||required:false|Children with Cancer UK (P2P)|
|Child Sponsorship|validate_child:false|….. To be confirmed …..||World Vision Australia|
|   |validate_child:true|….. To be confirmed …..||World Vision Australia|
||required_by_regular_giving:'child_sponsorship|….. To be confirmed …..||World Vision Australia|
|Consumer Price Index|No locales as yet||||
|Contact block|validation_workflow:'Phone_home_phone or Phone_mobile_phone',validation_workflow_err_msg:'CONTACT_BLOCK_ONE_PHONE'|If the Preferred Phone is home phone, then home phone is mandatory and mobile is optional. If Preferred Phone is mobile then mobile is mandatory and home phone is optional.||ActionAid (another)|
|Contact Preferences|No locales as yet||required:false,label:'big',render_as:'radiobutton'||
|Credit card failed validations|No locales as yet||display:'block'||
|Credit Card Type|No locales as yet||display:'block'||
|Currency Type|No locales as yet||||
|Custom Components 1-5|See: Controls for multiple components.md||||
|Date of birth|hide_date_and_month:true|Shows only the year of birth in Date of Birth|required_age:25, required_age_is_mandatory:true, hide_date_and_month:true|World Vision UK Support|
|   |hide_date:true|Shows only the month and year of birth in Date of Birth||World Vision UK Support|
|   |required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:0|World Vision UK Support|
|Debit Communications|No locales as yet||||
|Debit Failed Validations|No locales as yet||||
|Debit Tax|No locales as yet||label:'big'||
|Direct Debit IBAN|No locales as yet||display:'block'||
|Direct Debit SWIFT|No locales as yet||display:'block', required:false||
|Direct debit type|generate_bic_iban:true|Adds the BIC/IBAN components to the form|display:'block',generate_bic_iban:true|Dogs Trust 2015|
|Email|No locales as yet||required:false||
|Expiry Date|minimum_months:x|Logic to control the number of months from the current date that the credit card expiry date must have before it is accepted. The minimum time is the value you replace x with|minimum_months:2' creates logic to only accept credit cards that expire after 2 months from the current date||
|Financial Institution|No locales as yet||display:'block'||
|First Name|No locales as yet||||
|Gender|No locales as yet||required:false||
|Gift Aid|ntp_option:true|….. To be confirmed …..|required:true,label:'big', ntp_option:true|British Red Cross|
|Gifts|data_set:'{data set name}'|Attaches a Campaign Data Set as the answer option for the Gifts component|data_set:'WVA Gifts XMas' uses the Campaign Data Set 'WVA Gifts XMas' as a drop list|World Vision Australia|
|Have Heard Of|No locales as yet||||
|Home Phone|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false||
|ID Type Sighted|No locales as yet||||
|Income|No locales as yet||||
|Interested In|interestedin_restricts:'{component name}|{component name}|{component name}|{component name},interestedin_trigger:'{answer trigger to restrict the other components}'|Based on the response to the Interested In component, other components are hidden or displayed|interestedin_restricts:'childprofilenumber\|childname\|regulargiving\|transactiontype\|paymentdays\|paymentmonth',interestedin_trigger:'Yes'|World Vision Australia|
|Interested In Volunteering|No locales as yet||||
|Last Name|No locales as yet||||
|Location|No locales as yet||||
|Location Type|No locales as yet||||
|Mobile Phone|length:'x'|Enforces a character limit of 'x' characters|length:'10',required:false|Greenpeace Canada English|
|   |prefixes:''|….. To be confirmed …..||Greenpeace Mexico|
|Monthly Amount|currency:'x'|When you replace 'x' with the currency symbol for your currency ($, £ etc), it will display that symbol on the signature screen| currency:'$' will display $ on the screen. Other currencies that have been used: 'Php', 'Kr', 'Rp', '€', ''|Monthly Amount: Greenpeace Denmark (ML Marketing), Save the Children Philippines (Equality Marketing)|
|   |free_amount:false|Removes the free text box from the screen along with any associated text |label:'big',free_amount:false|Children with Cancer Support|
|Name on Card|No locales as yet||display:'block'||
|Payment Days|use_campaign_csv_values:false|Displays the Payment Days as a drop list from 1st - 28th|use_campaign_csv_values:false,required:false|Payment days - World Vision UK|
|   |ordinalize:false|Displays the Payment Days from the campaign setup as numbers only||UNICEF Austria|
|   |ordinalize:true|Displays the Payment Days from the campaign setup as 1st, 2nd, 3rd etc|||
|Payment Month|max_days_for_payment: x|When you replace x with the maximum days of payment, it will display that number of days in months i.e. max_days_for_payment: 60 will display the next two months from the current date|max_days_for_payment: 60,required:true|Oxfam IE Support|
|Payment type|options:'x\|y\|z'|Adds x, y, z options as payment types|options:'credit\|debit\|other'|British Heart Foundation (Clear)|
|   |debit_components:'custom_2\|Personalidentificationnumber\|Interestedin'|….. To be confirmed …..|debit_components:'directdebitiban', display:'block', options:'credit\|debit\|other'|Greenpeace Spain Support|
|   |other_components:'custom_4\|custom_5'|….. To be confirmed …..||World Vision Australia|
|Personal Identification Number|No locales as yet||||
|Place of Birth|No locales as yet||||
|Preferred Phone|No locales as yet||required:false||
|Prefers Email Updates|No locales as yet||||
|Profession|No locales as yet||required:false||
|Receive Communications|No locales as yet||required:true||
|Restrict Component Visibility|restricts:'\|x\|x\|x'|Restricts the x components that are contained within the ' '|restricts:'PersonalDetails\|secondary_address'|World Vision Australia|
|   |required_if_interestedin:'x\|y'|Sets the component as required based on the response to another question|required_if_interestedin:'Go Wild Membership – Donor is not legal guardian of recipient\|Go Wild Membership – Donor is legal guardian of recipient',restricts:'custom_1\|custom_2\|custom_3\|custom_4\|custom_5\|secondary_address'|WWF WORLD CUP (Together)|
|Secondary Address (and Address and Tertiary Address)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)|
|   |po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|
|   |international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|
|   |enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|
|   |country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||
|   |postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|
|   |address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|
|   |international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|
|Secondary Person Details|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required_age:0,required:false|WWF Austria|
|Share Details|No locales as yet||required:true||
|Shopping Centre|editable:true|Displays a free text box for shopping centre||Wesley ASAP|
|Terms & Conditions|No locales as yet||||
|Tertiary Address (and Address and Secondary Address)|po_box:false|Hides PO Box tick box in address component||Save the Children (Urban Leaf)|
|   |po_box:true|Displays PO Box tick box in address component / hides the Street field||Save the Children (Urban Leaf)|
|   |international:true|Adds a drop list of countries to the address block on the form. The country must be selected first by the fundraiser and then the relevant address validation will be applied to the address fields. ||SLSA (GIG)|
|   |enable_lookup:false|….. To be confirmed …..|Used with 'international:true' constraint. |Amnesty International Ireland|
|   |country:'{country_abbreviation}',language:'{language_abbreviation}',|….. To be confirmed …..|country:'GB',language:'ENG',enable_lookup:true,house_no_mandatory:true,postcode_length:8,international:false, address_lines_mandatory:true,po_box:false,international_restricted_to:''|World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:true|Sets 'House, Bldg, or PO Box' as mandatory||World Animal Protection (Venue Fundraising)|
|   |house_no_mandatory:false|Sets 'House, Bldg, or PO Box' as optional|||
|   |postcode_length:8|Untested  ….. Sets the character limit for the postcode to 8||World Animal Protection (Venue Fundraising)|
|   |address_lines_mandatory:false|Adds a 'Street' tick box to the address component for when there is no street name||World Animal Protection (Venue Fundraising)|
|   |international_restricted_to:''|….. To be confirmed …..||World Animal Protection (Venue Fundraising)|
|Tertiary Person Details|required_age:x|The required minimum age is set to the value you replace x with (it can be set to 0)|required:false, required_age:0|PDSA sandbox|
|Tied Funding|No locales as yet||||
|Title|No locales as yet||required:false|Oxfam (Dialogue Direct)|
|Transaction Type|No locales as yet||required:true|Save the Children (Urban Leaf)|
|Work phone|length:'x'|Enforces a character limit of 'x' characters|required:false||
