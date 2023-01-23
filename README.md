# lab_1_vehicle_classes_and_objects

Create a class called Vehicle. Upon initialization, it should receive max_speed (integer, optional; 150 by default) and mileage (number). Create an instance variable called gadgets - an empty list by default.

Test Code

car = Vehicle(20)
print(car.max_speed)
print(car.mileage)
print(car.gadgets)
car.gadgets.append('Hudly Wireless')
print(car.gadgets)

Output

150
20
[]
['Hudly Wireless']
