**Write a program that prompts the user to enter the weight of a person in kilograms and outputs the equivalent weight in pounds. (Note that 1 kilogram = 2.2 pounds).**
```python
kilograms = float(input("Enter weight in kilograms: "))
pounds = kilograms * 2.2
print(f"{kilograms} kilograms is equal to {pounds:.2f} pounds.")
```

netBalance = float(input("Enter net balance: "))
payment = float(input("Enter payment: "))
d1 = int(input("Enter number of days in the billing cycle: "))
d2 = int(input("Enter number of days payment is made before billing cycle: "))
interestRatePerMonth = float(input("Enter monthly interest rate (e.g., 0.0152): "))
averageDailyBalance = ((netBalance * d1) - (payment * d2)) / d1
interest = averageDailyBalance * interestRatePerMonth
print(f"Interest on unpaid balance: {interest:.2f}")


import math
x = float(input("Enter the average speed of Car A (mph): "))
y = float(input("Enter the average speed of Car B (mph): "))
hours = int(input("Enter elapsed time (hours): "))
minutes = int(input("Enter elapsed time (minutes): "))
t = hours + minutes / 60.0
distanceA = x * t
distanceB = y * t
shortest_distance = math.sqrt(distanceA**2 + distanceB**2)
print(f"Shortest distance between the cars: {shortest_distance:.2f} miles")
