# Inventory-Management-System-ETG
This repository is having all the codes used in the 'Inventory Management using json' project of the AI/ML internship by ETG.

**What is in this repository?**
This repository consist of an inventory. You can add items to the inventory and also purchase from it.

**About the repository:**
The project is mainly based on **json nosql** format. The code is able to perform **ERROR HANDLING** if the user entered data is incorrect. It also makes use of pandas library to form a bill in tabular format.

**Features of the repository:**
1. Adding new products to the inventory.
2. Updating the quantity of the existing product in inventory.
3. Users can purchase items from the inventory.
4. **Bill in tabular format** will be provided to the user.
5. On purchase above Rs.2000, **10% discount** is given.
6. **Multiple orders** can be taken at one time.
7. **User input** taken in the form of strings is **not case sensitive**.
8. records.json file contains the entire inventory.
9. sales.json files contains the sales made along with the time and day of purchase.

**Files:**
1. record.json: 
        Consist of the products in the inventory. Any new product added, is updated in it. The quantity of products purchased by customer is reduced from the original quantity present in this file.
 
 2.sales.json:
        1.Consist of the list of the sales made and also the day and time of purchase. 
        2.The purchase is not overwritten on the older ones. 
        3.All the purchases are retained in one file.
        
        
3. ADDING PRODUCTS TO INVENTORY.ipynb:
        1.Asks if new product is to be added or an already existing one is to be updated. 
        2.If updation is selected then product id and new quantity is asked. 
        3.The new quantity is added to the already existing one. 
        4.If new product is selected then the product id is generated as the number after the already existing product id. 
        5.If the user enters a wrong input in place of product id or quantity then the error is displayed. 
        6.The code is run irrespective of the case in which the user enters 'yes' or 'no'.
       
4. PURCHASING PRODUCTS FROM INVENTORY.ipynb:
       1. Displays all the products in the inventory with the product ids. 
       2. Manages wrong user inputs. 
       3. Displays bill. 
       4. Gives discount.
       5. Makes the updation in sales and record file.

**Who am I:**
I am Isha Desai a novice coder. 

**Social media handles:**
LinkedIn: www.linkedin.com/in/isha-desai-a1362821a
instagram: https://www.instagram.com/ishhh_2112/

        

