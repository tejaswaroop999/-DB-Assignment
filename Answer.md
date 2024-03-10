# -DB-Assignment
1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram?
   
Relationship between "Product" and "Product_Category" entities.The relationship between the "Product" and "Product_Category" entities is likely a one-to-many relationship, where one product belongs to one category, but one category can have multiple products. This relationship is typically represented by a foreign key in the "Product" table that references the primary key in the "Product_Category" table.

2. How could you ensure that each product in the "Product" table has a valid category assigned to it?

Ensuring each product has a valid category assigned To ensure that each product in the "Product" table has a valid category assigned to it, you can implement a foreign key constraint in the database schema. This constraint will enforce referential integrity, meaning that any value entered into the "Product_Category" column in the "Product" table must match a valid primary key in the "Product_Category" table. Additionally, you can implement data validation checks in your application logic to ensure that products are only assigned to existing categories.

