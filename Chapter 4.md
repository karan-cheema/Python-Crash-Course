## Chapter 4: Working With Lists
Challenge 4.1. Pizza:
```python
pizzas = ["Chicken Tikka", "Peri Peri", "Dominator"]
for pizza in pizzas:
    print(pizza)
    print(f"I like {pizza} pizza.")
    print(f"I like {pizza} pizza as it's delicious\nIt's got amazing texture\nand to an extent {pizza} is also spicy.")
```
Challenge 4.2. Animals:
```python
animals = ["dog", "cat", "raccoon"]
for animal in animals:
    print(animal)
    print(f"{animal} is an amazing house pet.")
print("All these animals would making an amazing pet for your room.")
```
Challenge 4.3. Counting to twenty:
```python
for value in range(1, 21):
    print(value)
```
Challenge 4.4. One Million:
```python
million = list(range(1, 1000001))
print(million)
```
Challenge 4.5. Summing a Million:
```python
odd_number = list(range(1, 20, 2))
print(odd_number)
```
Challenge 4.6. Odd Number:
```python
odd_number = []
for value in range(1, 20, 2):
    odd_number.append(value)
print(odd_number)
```
Challenge 4.7. Threes:
```python
threes = []
for value in range(3, 33, 3):
    threes.append(value)
print(threes)
```
Challenge 4.8. Cubes:
```python
cubes = []
for value in range(1, 10):
    cubes.append(value ** 3)
print(cubes)
```
Challenge 4.9. Cube Comprehension:
```python
cubes = [value ** 3 for value in range(1, 10)]
print(cubes)
```
Challenge 4.10. Slices:
```python
list = ["Pez", "Candy corn", "Twizzlers", "Jawbreakers", "Nik-L-Nips", "Peeps", "Pocky", "Red Vines", "Cotton candy", "Gummi Bears", "Pop Rocks", "Wax lips", "Circus peanuts", "Toblerone", "Blue chips"]
print(f"The first three items in the list are: {list[:3]}")
print(f"The first three items in the middle are: {list[6:-6]}")
print(f"The last three items in the list are: {list[-3:]}")
```
Challenge 4.11. My Pizzas, Your Pizzas:
```python
pizzas = ["Chicken Tikka", "Peri Peri", "Dominator"]
friend_pizzas = pizzas[:]
pizzas.append("Fully Loaded")
friend_pizzas.append("Paradise")

print(f"My favorite pizzas are:")
for pizza in pizzas:
    print(pizza)
    
print(f"My friend's favorite pizzas are:")
for pizza in friend_pizzas:
    print(pizza)
```
Challenge 4.12. More Loops
**TO BE COMPLETED**
