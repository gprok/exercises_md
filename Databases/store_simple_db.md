# Design DB for a simple store

A store needs to keep track of the products.   
For each product they need the following information:
1. a unique identification (id)
1. the name of the product 
1. the category of the product. A product will be set in one category only.
1. the colors of the product (this can be empty, too, if there are no colors or if color doesn't make sense)
1. the available size of the product (like color, it might be empty)
1. the price
1. the stock value (how many items are available)

A. Design the table or tables necessary to store the prosucts' data and make sure your design is in 2NF.   
B. Implement the table(s) and add a few data   
C. Write queries to display:  
1. the product names that are available in a specific color
1. all the products and the category they belong to
1. all products that are low in stock (e.g. stock is less than 5)

