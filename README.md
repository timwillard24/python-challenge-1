# Variety Food Truck Ordering System
Welcome to the Variety Food Truck Ordering System! This Python script allows users to place orders from a variety of menu categories, including Snacks, Meals, Drinks, and Dessert. Users can select items, specify quantities, and receive a final order receipt with the total cost.

## Features
- **Menu Categories**: Choose from Snacks, Meals, Drinks, and Dessert.
- **Subcategories**: Some categories have subcategories (e.g., different types of Pizza or Burger).
- **Order Multiple Items**: Users can order multiple items from different categories.
- **Quantity Selection**: Specify the quantity for each item ordered.
- **Order Receipt**: Displays a detailed receipt with item names, prices, quantities, and the total cost.

## How to Use

1. **Run the Script**: Launch the script in a Python environment.
2. **Select Menu Category**: Input the number corresponding to the menu category you want to order from.
3. **Select Menu Item**: Input the number corresponding to the specific item you want to order.
4. **Specify Quantity**: Input the quantity for the selected item.
5. **Repeat or Finish**: Choose whether to keep ordering or finish the order.
6. **View Order Receipt**: After finishing the order, the script will display the order receipt with the total cost.

## Sample Output
Welcome to the variety food truck.
From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 2
You selected Meals
What Meals item would you like to order?

You selected Meals
What Meals item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49
Type Menu Item Number
Type Menu Item Number1
How many Burrito would you like?1
You've Added 1 x Burrito to the order
Would you like to keep ordering? (Y)es or (N)o n
Thanks for Ordering
This is what we are preparing for you.


Order Receipt
Item name                 | Price  | Quantity
--------------------------|--------|----------
Burrito                   | $4.49  | 1

Total Cost: $4.49

## Code Overview
The script follows these main steps:

1. **Setup Menu and Order List**: Defines the menu dictionary and initializes an empty order list.
2. **Greeting**: Displays a welcome message to the user.
3. **Order Loop**: Continuously prompts the user to select a menu category, a specific item, and the quantity.
4. **Input Validation**: Checks if the user inputs are valid numbers and within the menu options.
5. **Order Confirmation**: Asks the user if they want to keep ordering or finish.
6. **Print Receipt**: Displays the final order receipt with item details and the total cost.

## Requirements
- Python 3.x

## How to Run

1. Save the script to a file, e.g., `food_truck.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is saved.
4. Run the script using the command: `python food_truck.py`.

## Sources
1. Utilized ChatGPT to diagnose misunderstood terminal error messaging
2. Utilized ChatGPT for assistance on receipt handling/printing
3. Utilized ChatGPT to review code for consistency and formatting errors
