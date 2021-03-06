| COMPONENT | CONDITIONS| DETAILS |CAMPAIGNS|
|:------------|:-----------|:---------------|:-------|
|Payment Type|pledge.payment_method == 'directdebit'|Email is sent if payment method is direct debit|The Nature Conservancy (Future Fundraising), IHC AIDA (AFNZ1-Wellington)|
||pledge.payment_method == 'creditcard'|Email is sent if payment method is credit card|The Nature Conservancy (Future Fundraising), IHC AIDA (AFNZ1-Wellington)|
|||||
|Custom Fields|pledge.custom_2.present?|Email is sent if there is an entry in the custom 2 free text box|Australian Conservation Foundation (KKSM)|
||pledge.custom_1 != "Please don't send me a print"|Email is sent based on response to Custom 1|Greenpeace UK|
||pledge.custom_1 == "Please don't send me a print"|Email is sent based on response to Custom 1|Greenpeace UK|
|||||
|||||
|Payment frequency|pledge.transaction_type == Pledge::TRANSACTION_TYPE_MONTHLY|Email is sent if the payment frequency is monthly|Oxfam Dialogue Direct (Support), TWS 2013|
||pledge.transaction_type == Pledge::TRANSACTION_TYPE_ANNUAL|Email is sent if the payment frequency is annual|Children International (Appco US), TWS 2013|
||pledge.transaction_type == Pledge::TRANSACTION_TYPE_SEMI-ANNUAL|Email is sent if the payment frequency is semi-annual|Children International (Appco US)|
||pledge.transaction_type == Pledge::TRANSACTION_TYPE_HALFYEARLY|Email is sent if the payment frequency is half-yearly|Children International (Appco US)|
||pledge.transaction_type == Pledge::TRANSACTION_TYPE_DONATION|Email is sent if the payment frequency is donation|Greenpeace Canada Français & English, Oxfam Dialogue Direct (Support)|
||pledge.transaction_type == Pledge::TRANSACTION_TYPE_QUARTERLY|Email is sent if the payment frequency is quarterly|Oxfam Dialogue Direct (Support), Children International (Appco US)|
|||||
|Interested In|pledge.supporter_interested_in == 'Supporter of Change'|Email is sent if Interested In = Supporter of Change||
||pledge.supporter_interested_in == 'Child Sponshorship'|Email is sent if Interested In = Child Sponorship||
|||||
|Gift Aid|pledge.gift_aid == 'true'|Email is sent if gift aid is selected|Concern NI 2015|
||pledge.gift_aid == 'false'|Email is sent if gift aid isn't selected|Concern NI 2016|
|||||
|Gender|pledge.supporter_gender == 'male'|Email is sent if donor is male|UNICEF Austria|
||pledge.supporter_gender == 'female'|Email is sent if donor is female|UNICEF Austria|