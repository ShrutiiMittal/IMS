# IMS
Its a small project on JSON based Inventory Management System using Python

# Overview
This is a project on inventory management of an ice cream parlour.This can be used to generate bills, update items on the inventory, add products to the records, keep a purchase tracking information along with date and time the purchase is made.

# All files file
record.json- It contains all the items present in stock along with product features.
add_products.ipynb- It contains the code to add new items or update existing ones in the record .One can add new items with all feautures or update quantity ,price or any other feature except the product ID to the existing records.One can also delete any particular product from the record.
sale.json- It contains all the transaction history.
sell_products -It contains the code to generate bills and also update record.json with the remaining quantities after purchase. It also updates sale.json to maintain transaction records.

# Features
Make multiple purchases in single bill.Transaction history would be added separately for each order. The amount for each order is displayed separately while the total amount of all the orders is displayed at the end of the bill.The bill also has a transaction time on it.

# Product features
Product id is the primary key which has all the values of a particular product. It has feautures like name,quantity,expiry date, vendorID,category, 2 varities to choose from: cup and cone each having a different price.

# Transaction features
Transaction history is maintained by the file sale.json and also "update" dictionary. Transaction Id is the unique key which is generated as the max number of all keys plus one. It has feautures of name, product ID, quantity purchased, amount of that order and time of the order purchased.

# About Me
I'm Shruti, a student persuing BTech in the field of Computer Science and Engineering. I'm new to the field of data science and Python. Aiming to learn and explore more.

# Important Links
https://www.linkedin.com/in/shruti-mittal-1a85521b8
