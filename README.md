# Python-Projects
This Repository includes all the Python projects that I practiced during my course of learning Python.
#Project Number 1 : Rent Calculator

rent = int(input("Enter your flat rent:"))
food = int(input("Enter the amount of food ordered:"))
electricity_spend = int(input("Enter the total electricty spent:"))
charge_per_unit = int(input("Enter the charge per unit:"))
persons = int(input("Enter the total number of occupants:")) 
electricity_bill = (electricity_spend * charge_per_unit)

output = (rent+food+electricity_bill) // persons

print ("Charge per person is", output)
