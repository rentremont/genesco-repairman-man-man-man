## Genesco Sales Analysis

##IMPORTANT

This data is not ours and should not be shared publicly.  Be sure the data is stored in the data folder of your repo.   Clear notebooks before pushing.
Data security is very important. If you are unsure, just ask.


### BACKSTORY  
In our Journeys Stores, our employees are trained in what is called “4 on the Floor”. When a customer asks to try on a shoe, the employee goes to the back room and is expected to bring the shoe that the customer wants to try on and an additional 3 pair of shoes to try to sell to them. Typically, this is the same shoe in a different color, a shoe that just came in, and a shoe that is on sale. In the real world, only those who are very experienced can do this with any accuracy.  

### DATA PROVIDED  
Data has been provided for three divisions: Little Burgundy (LB), Journeys Canada (JYCA), and Journeys US (JYUS). For each division, you've been provided sales transaction data, product dimensions, and list of departments. The transactions data can be joined to the product dimensions using DIV and parent_stockno or child_stockno. Note that the product dimension for Little Burgundy is complete, but the attributes for both Journeys divisions is only about 80% complete.

Each transaction is a sale involving at least two items. These items can be identified through the stock numbers (PARENT_STOCKNO and CHILD_STOCKNO). Note that if a transaction involves 3 or more items, it will be split over multiple rows.

### PROJECT GOALS  
Currently, Genesco has recommendations based on shoe brand. For example, if a customer requests a top five brand shoe, bring another top five brand shoe in black or white. Your goal in this project is to try and identify other useful recommendations on the basis of the product dimensions (brand, gender, etc.). The main question to explore is what sells well together by dimension.
