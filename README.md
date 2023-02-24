# Analyze_Pet_Sales_Data

_**Company Background**_

PetMind is a nationwide pet product retailer in the United States. With inflation hitting 41-year highs, the company is planning to reduce the cost of customer retention by improving brand loyalty. The first strategy is to launch a monthly pet box subscription in three months. The marketing team is preparing a list of popular products for the pet box subscription. The chief marketing officer wants to know whether the list should only include the products being purchased more than once.

_**Customer Questions**_

The marketing team would like to answer the following questions to help with the decision:

● How many products are being purchased more than once?

● Do the products being purchased again have better sales than others?

● What products are more likely to be purchased again for different types of pets?

_**Data Validation**_

1.Data contains no null values in any of the columns.

2.Sales column contains characters like $ , which are removed for further analysis of Sales column.

3.The Data type of Sales column is updated to int64 which was before object type.

4.Records with pet_type column value other than “cat”,“dog”, “fish”, “bird” are dropped.

_**Data Discovery**_

1.Total 390 products were re-purchased.

2.The average price of re-buy items(i.e.,$116889.743590) is high than average of single purchased items.

3.There are single purchased products worth more than $116890 among which products only having rating higher than 7 are considered for analysis.

4.Among them most products are for dogs(Supplements,Food) and cats(Medicine).

5.Among the re-purchased items dogs and cats products are purchased more than others.

6.Common products purchased among them were Equipment,Snack,Toys,Supplements,Medicine.

7.Irrespective of pet type,on an average Medicine and Toy Products are costly.


