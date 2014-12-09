| MERGE FIELD | TEXT        | EXAMPLE OUTPUT|CAMPAIGNS|
|:------------|:------------|:--------------|:--------|
|${TRANSACTION_AMOUNT}|I authorize the amount of ${TRANSACTION_AMOUNT} {transactiontype} to be deducted from my account| I authorize the amount of $30 per month to be deducted from my account|HelpMeSee (Appco US)|
|{transactiontype}|I authorize the amount of ${TRANSACTION_AMOUNT} {transactiontype} to be deducted from my account|I authorize the amount of $30 per month to be deducted from my account|HelpMeSee (Appco US)| 
|${monthlyamount}|I confirm my regular ongoing monthly donation of ${monthlyamount}|I confirm my regular ongoing monthly donation of $30|Fred Hollows AIDA (Source)|
|${YEARLY_AMOUNT}|
|{TRANSACTION_AMOUNT}|
|{paymentdays} {paymentmonth}|I confirm my regular ongoing monthly donation of ${monthlyamount} will start on {paymentdays} {paymentmonth} 2013|I confirm my regular ongoing monthly donation of ${monthlyamount} will start on 18 July 2013|Forest & Bird AIDA (Kulture Marketing)|
