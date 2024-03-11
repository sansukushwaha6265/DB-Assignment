1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans.- The relationship between the "Product" and "Product_Category" entities is that a Product belongs to one Product_Category. Each product has a foreign key called "category_id" which references the primary key "id" of the               
       "Product_Category" table. This indicates that a product can only be in one category, but a category can have many products.
   
2.How could you ensure that each product in the "Product" table has a valid category assigned to it?
Ans. - When defining the "category_id" field in the "Product" table, set it as a foreign key referencing the primary key "id" of the "Product_Category" table. This enforces database-level validation, preventing products from being saved with        an invalid or non-existent category ID.
