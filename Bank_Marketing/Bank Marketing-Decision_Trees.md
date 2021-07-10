Sources: UCI Created by: Paulo Cortez (Univ. Minho) and Sérgio Moro (ISCTE-IUL) @ 2012

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.

The classification goal is to predict if the client will subscribe a term deposit (variable y).

EDA Findings:

- Age variable is right skewed, most of the values are between 20 and 40
- Average Yearly Balances are between 0 and 5000 with outliers reaching 100 K
- Most campaign values are in the lower values (1 <10)
- pdays: -1 means client was not previously contacted
- Conversion : Imbalanced values, Most of the customers in the dataset didn't convert(about 88 %, 12% converted)
- Job : Most customers are bluecollar, Management level and technicians
- Most of the customers in the dataset are married
- Secondary Education level is most common in this dataset
- Most Customers didn't default in payment, do not have loans,
- Most of the contact was via cellular
- Students have the highest conversion rate (buy bank term deposit)then retired and unemployed
- The default rate in the non-conversion group is about twice as high as the conversion group.
- The bank balances of converted customers seem to vary more than those of non-converted customers and the median value is higher for the converted group.
- Most of the converted are from the Tertiary education
- According to the variable description, campaign is the number of contacts performed during this campaign and for this client (includes last contact), Less contacts means higher conversion
- Conversion rates are higher in elder age groups
- Duration is the last contact duration, has the highest correlation with the conversion
