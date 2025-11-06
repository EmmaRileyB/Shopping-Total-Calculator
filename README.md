# Shopping-Total-Calculator
This script to guess how much shopping total will be
# Simple Python program: Shopping total calculator

# Ask for user input
item_name = input("Enter the name of the item: ")
price = float(input("Enter the price of one item ($): "))
quantity = int(input("Enter the quantity you want to buy: "))

# Calculate total cost
total_cost = price * quantity

# Display results
print("\n--- Purchase Summary ---")
print("Item:", item_name)
print("Price per item: $", price)
print("Quantity:", quantity)
print("Total cost: $", total_cost)

# Example of another data type (boolean)
is_discounted = total_cost > 50
print("Is your total above $50 (eligible for discount)?", is_discounted)
