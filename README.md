# lovely_love_seats
for learning python


# define Lovely Love Seat

lovely_loveseat_description = """
Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white.
"""

# define lovely love seat price

lovely_loveseat_price = 254.00

# define sytlish settee

stylish_settee_description = """
Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black.
"""

# define stylish settee price

stylish_settee_price = 180.50

# define luxurious_lamp

luxurious_lamp_description = """
Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade.
"""

# define luxurious lamp price

luxurious_lamp_price = 52.15

# define sales tax

sales_tax = .088

# calculate customer 1 total
customer_one_total = 0

# itemise customer 1 purchases

customer_one_itemisation = ""

customer_one_total += lovely_loveseat_price
customer_one_itemisation += lovely_loveseat_description
customer_one_total += luxurious_lamp_price
customer_one_itemisation += luxurious_lamp_description
customer_one_tax = (customer_one_total * sales_tax)
customer_one_total += customer_one_tax

print("Customer one Items: ")
print(customer_one_itemisation)
print("customer one total:")
print(customer_one_total)

# customer 2

customer_two_total = 0
customer_two_itemisation = ""

customer_two_total += stylish_settee_price
customer_two_itemisation += stylish_settee_description
customer_two_total += luxurious_lamp_price
customer_two_itemisation += luxurious_lamp_description
customer_two_tax = (customer_two_total * sales_tax)
customer_two_total += customer_two_tax

print("Customer two Items: ")
print(customer_two_itemisation)
print("customer two total:")
print(customer_two_total)
