#Menu Options
The menu consists of the following items:

Soup - 5$
Burger - 8$
Pizza - 12$
Salad - 4$
Water - 2$
Beer - 4$
Coffee - 5$
Example Usage
The program welcomes you to the DuckyRestaurant and displays the menu.
You are prompted to enter the number corresponding to the item you want to add to your cart.
After selecting an item, you are asked if you want to add more items to your cart.
You can continue adding items until you choose not to.
The program then displays the contents of your cart and the total cost.
Finally, it shows your remaining balance after the purchase.
Code Explanation
Here is a brief explanation of the code:

myPocket(int balance): A function that prints the remaining balance.
main(): The main function where the program execution starts.
Displays the restaurant welcome message and menu.
Initializes the options and prices arrays.
Uses a loop to let the user choose items and add them to the cart.
Calculates the total cost of the items in the cart.
Displays the cart contents and total cost.
Updates and displays the remaining balance.
Note
This project uses scanf_s for input, which is specific to Microsoft Visual Studio. If you are using a different compiler, you might need to replace scanf_s with scanf.
The initial balance is set to 300$.
Future Improvements
Add input validation for non-integer inputs.
Allow the user to remove items from the cart.
Save and load the cart from a file.
Implement a more user-friendly interface.
