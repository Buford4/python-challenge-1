# EdX Food Truck, it's interactive!
## Designing an interactive ordering system.
Provided with a menu from a local food truck, we will be adapting this menu to allow for customers to place an order, store the order, and having the order print a receipt containing the total price of the itmes that were ordered. 

## Challenge Requirements:

## Order System
1. An order list is initialized.
2. User is prompted for their menu items selection. The item selection is saved as a varialble menu_selection.
3. User input menu_selection is checked as a number and an error is printed if it is not.
4. an if-else statement is used to check if menu_selection is in the menu_items keys, and an error is printed if it isn't.
5. The item name of the customer's selection is extracted from the menu_items.
6. The customer is prompted for a quantity of their item selection and the value defaults to 1 if the customer does not input a valid number.
7. The customer's selected item, price, and quantity are appended to the order list in dictionary format.
8. A match-case statement is used to check if the customer would like to keep ordering, and performs the correct actions for y, n, and default cases.
9. The match-case statement converts the use input to lowercase or uppercase before checking the case.

## Order Receipt
1. A for loop is used to loop through the order list.
2. The value of each key in each order dictionary is saved as a variable.
3. Space strings are created using string multiplication. 
4. The customer's order is printed with the item name, price, and quanitity.
5. List coomprehension is used to calculate the total price of the order.
6. The total price of the order is printed to the screen. 