# Online_Shop


## Project description
This project is a backend application for an online store. The customer can see the products in this store, having at the same time the possibility to sort them by certain criteria. Also, the manufacturer has the possibility to manage the products on the site. It can set the number of products in stock, the date a certain order was shipped, etc.

## Business requirements

1. As a customer, I want to be able to have my own account
2. As a customer, I want to be able to view existing orders
3. As a customer, I want to be able to add an order
4. As a customer, I want to be able to search for products by name
5. As a producer, I want to see information about the inventory of a product
6. As a producer, I want to be able to divide the products according to certain categories
7. As a producer, I want to delete the product that is no longer of interest
8. As a producer, I want to be able to see all the categories that exist in the store
9. As a producer, I would like to see a list of all existing clients
10. As a producer, I want to be able to edit the data about a certain product

## Endpoints:

1. Category: this class contain:
   - The name of category
   - A list of products

- *Add new category:* 
    - path: /category/addCategory
    - params: @RequestBody CategoryRequest 
- *Edit category*
    - path: /editCategory
    - params: @RequestBody CategoryRequest
