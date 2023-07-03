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
