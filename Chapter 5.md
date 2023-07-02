## Chapter 5: If Statements
Challenge 5.1. Conditional Tests:
```python
#5.1 Conditional Tests
car = "Honda"
print("Is car == Honda? I predict True")
print(car == "Honda")

car = "Hyundai"
print("Is car == Hyundai? I predict True")
print(car == "Hyundai")

car = "Audi"
print("Is car == Audi? I predict True")
print(car == "Audi")

car = "VW"
print("Is car == VW? I predict True")
print(car == "VW")

car = "MG"
print("Is car == MG? I predict True")
print(car == "MG")

car = "Cheverlot"
print("Is car == Cheverlot? I predict False")
print(car == "Honda")

car = "Ferrari"
print("Is car == Ferrari? I predict False")
print(car == "Honda")

car = "Porsche"
print("Is car == Porsche? I predict False")
print(car == "Honda")

car = "Pagani"
print("Is car == Pagani? I predict False")
print(car == "Honda")

car = "Mistubishi"
print("Is car == Mistubishi? I predict False")
print(car == "Honda")
```
Challenge 5.2. More Conditional Tests:
```python
a = "apple"
b = "banana"
print(a != a)

a = "apple"
b = "banana"
print(a != b)

print("apple" == "Apple")
print("apple" == "Apple")

apple = "APPLE"
print(apple.lower() == "apple")
print(3 > 2 or 4 < 2)
print(3 > 2 and 4 < 2)
print(3 != 2)
print(3 ==3)
print(3 >= 3)
print(2 >= 3)

alphabets = ["alpha", "bravo", "charlie", "delta", "echo", "foxtrot", "echo"]
print("alpha" in alphabets)
print("india" in alphabets)
```
## Chapter 5: If Statements
Challenge 5.3. Alien Color 1:
```python 
alien_color = "yellow"
if alien_color == "green":
    print("You earned 5 points.")

alien_color = "green"
if alien_color == "green":
    print("You earned 5 points.")
```
Challenge 5.4. Alien Color 2:
```python
alien = "yellow"
if alien == "green":
    print("You earned 5 points.")
elif alien != "green":
    print("You earned 10 points.")

alien = "yellow"
if alien == "green":
    print("You earned 5 points.")
else:
    print("You earned 10 points.")
```
Challenge 5.5. Alien Color 3:
```python
alien = "yellow"
if alien == "green":
    print("You earned 5 points.")
elif alien == "yellow":
    print("You earned 10 points.")
else:
    print("You earned 15 points.")
```
Challenge 5.6. Changes of life:
```python
age = 34
if age <= 2:
    print("You are a baby.")
elif age >= 2 and age < 4:
    print("You are a toddler.")
elif age >= 13 and age <= 20:
    print("You are a toddler.")
elif age >= 20 and age <= 65:
    print("You are an adult.")
else:
    print("You are elder.")
```
Challenge 5.7. Favorite Fruit:
```python
favorite_fruit = ["mango", "apple", "dragon fruit"]
if "mango" in favorite_fruit:
    print("You really like mango.")

```
