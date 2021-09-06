# Elite-Tech-Group-Inventory-Management-System-Project
Assignment summation 

This is a project based on Inventory Management System.
It contain 3 files: 
1.> Record.json 
In this file he have data of 35+ grocerys items present in his shop, this data is stored in from of dictornary in which key of dictornary represent a uniqe ID (called Bar code) and Value of particular key is data of that item as
{ "12201": { "name": "Milk", "price": 100, "quantity": 190, "exp": [ 2021,10,29], "manuf": [2018, 8,19 ] } }, this store name,price,  quantity,expriy date, Manufacturing date.

2.>final.ipynb
This is main python file of this project it has two options 1--> to  puschase and 2--> to add new item in the shop.
if 1 entered then the user will asked to enter the bar code of that product ,then how much quantity of product he wants 
if he doesn't have that much quantity in the  store then print "This product is out of stock".and if he have that much quntity then the current date with expriy date will get campared ,if the product get expried then print "This product is expried".
else calculate the amount and show  user the BILL.

example like this
       
************************************
           Final Bill               
Product:  Cheese
Price:  100
Expiry date:  2021-10-29
Manufacturing date:  2021-08-19
Amount:  1500
        Thanks for shopping         
************************************
and then the detail of that BILL will store in sell_til_now.json file.

If he enters 2 to Add item in record
then he will be asked to enter Bar code of that product , quantity of prodct and if this product allready exits in our record then that much quantity of product will be get added in record.
else full information of product like name,price,expriy date, manufacturing date will be ask and it will be added in his record


3.> sell_till_now.json 
This file basiclly store the detail of each product soled till now.
example like this 
{
 "12201": {"name": "Milk", "quantity": 30, "Amount": 3000},

 "12204": {"name": "Soup", "quantity": 13, "Amount": 1300}
}

