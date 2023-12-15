# Problem-2
# Problem 2: Item Unit Price

# Get user input for item and quantity
item = input("Enter item (A or B): ")
quantity = int(input("Enter quantity: "))

# Determine unit price based on the item
if item.upper() == "A":
    unit_price = 10.00
else:
    unit_price = 20.00

# Calculate extended price
extended_price = quantity * unit_price

# Display results
print(f"\nItem: {item}")
print(f"Unit Price: ${unit_price:.2f}")
print(f"Extended Price: ${extended_price:.2f}")
