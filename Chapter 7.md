## Chapter 7: User Input and While Loops
Challenge 7.1. Rental Car:
```python
car = input("What kind of rental car do you want? ")
print(f"Let me see if we have {car.title()} available.")
```
Challenge 7.2. Restaurant Seating:
```python
seating = input("How many people are in your group? ")
seating = int(seating)

if seating >= 8:
    print("We are sorry, but you will have to wait for some time.")
else:
    print("Your table is ready.")
```
Challenge 7.3. Multiples of Ten:
```python
number = input("Choose a number? ")
number = int(number)

if number % 10 == 0:
    print("The number is a multiple of 10.")
else:
    print("The number is not a multipe of 10.")
```
Challenge 7.4. Pizza Toppings:
```python
prompt = "Please enter the toppings you want to put in your pizza?"
prompt += "\n(Enter quit when you are finished.)"

pizza_topping = []

while True:
    topping = input(prompt)
    print(f"Adding {topping} in your pizza.")
    pizza_topping.append(topping)
    
    if topping == 'quit':
        break

print(f"We are adding the following toppings in your pizza.")
for top in pizza_topping:
    print(top)
```
Challenge 7.5. Movie Tickets:
```python
ticket = 0
age = int(input("What is your age? "))
if age <= 2:
  ticket += 0
elif age >= 3 and age <= 12:
  ticket += 10
else:
  ticket += 15

print(f"The cost of your ticket is ${ticket}.")
```
Challenge 7.7. Infinity:
```python
x = 1
while x <= 5:
    print(x)
```
Challenge 7.8. Deli:
```python
finished_sandwiches = []
sandwich_orders = ["bologna", "chili burger", "Chimichurris", "natmad", "Tramezzino"]
while sandwich_orders:
    sandwich = sandwich_orders.pop()
    print(f"I made you a {sandwich}")
    finished_sandwiches.append(sandwich)
print("I made you the following sandwiches")
for fin in finished_sandwiches:
    print(fin)
```
Challenge 7.9. No Pastrami:
```python
finished_sandwiches = []
sandwich_orders = ["bologna", "Pastrami", "chili burger", "Chimichurris", "Pastrami", "natmad", "Tramezzino", "Pastrami"]
print("We have sadly ran out of Pastrami sandwiches.")
while "Pastrami" in sandwich_orders:
    sandwich_orders.remove("Pastrami")
while sandwich_orders:
    sandwich = sandwich_orders.pop()
    print(f"I made you a {sandwich}")
    finished_sandwiches.append(sandwich)
print("I made you the following sandwiches")
for fin in finished_sandwiches:
    print(fin)
```
Challenge 7.10. Dream Vacation:
```python
responses = {}
polling_status = True

while polling_status:
    name = input("What is your name? ")
    location = input("If you could visit one place, where would you go? ")
    responses[name] = location
    repeat = input("Would you like to let another person respond? Yes or No? ")
    
    if repeat == "No":
        polling_status = False

print("Poll result are as follows:")
for loc in responses.values():
    print(loc)
```
