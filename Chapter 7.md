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
