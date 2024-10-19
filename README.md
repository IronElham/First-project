# First-project

Introduction: 

Business case: I am a data analyst in a firm specialized in retail and e-commerce consulting. For this project I looked at 'footwear data' from Shein platfom in fashion industry. Main objective is to analyze customer behavior and propose the best selling product category. 
Problem statement: Which factors influence the customer’s rating per footwear category? 

Hypotheses:

H1: Fit accuracy or fit true to size 
Footwear with more than 70% of percentage overall fit true to size are more likely to have high ranking among customers.
H2: Duration of delivery
Faster delivery times increase the likelihood of footwear receiving higher customer ranking rates.

H3: Price difference or discount price
Footwear with the high price difference (retail price and sales price) are more likely to have high ranking among customers.

Data preparation and cleaning: 
Dataframe was obtained by concatinating data from 13 pages of the Shein platform, and setting keywords in search bar (param=querystring{}) as 'shoes'
The data contained nested lists and dictionaries, json_normalization used which flattening it added to the number of columns. 
Data cleaning techniques used for dropping unnecessary columns, duplicates, null values, fillna, renaming, changing data types

For more specific information on cleaning data please refer to the Jupyter Notebook in our repo

Findings: 
H1: Fit accuracy or fit true to size: Validated as 97% of customers rated the footwear to be true to size. 
H2: Duration of delivery: Rejected as 96% of customers No quick delivery rated higher than thoes had quick delivery. 
H3: Price difference or discount price: Not validated, price difference of $10 had higher rank in comparison to a higher discount price $13

More analysis: 
1) Average rank / shoe category, illustrated the specific category of shoes with higher ranking. Women’s Sports Shoes highest average rank. 
2) Total number items sold/ price difference,to show how many items were sold on which discount price, $6 discount the highest sales volume
3) Best seller / shoe category, Number of times footwear was a best seller. Women’s Casual Shoes was 39 times as best seller

*For further information please refer to the Jupyther notebook and presentation on this repo. 
