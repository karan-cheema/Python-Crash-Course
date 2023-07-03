## Chapter 6: Dictionaries
Challenge 6.1. Person:
```python
name = {
    'first_name' : 'Destiney', 
    'last_name' : 'Hale', 
    'age' : '21', 
    'city' : 'New York',
    }

print(name['first_name'])
print(name['last_name'])
print(name['age'])
print(name['city'])
```
Challenge 6.2. Favorite Number:
```python
number = {'Lillian' : 20, 'Armani' : 17, 'Raquel' : 51, 'Jaida' : 55, 'Elyse' : 31}
print(number['Lillian'])
print(number['Armani'])
print(number['Raquel'])
print(number['Jaida'])
print(number['Elyse'])
```
Challenge 6.3. Glossary:
```python
glossary = {
    "print" : "Prints out the output in the terminal.",
    "list" : "Lists are also known as arrays.",
    "dictionary" : "The thing which you are currently looking at righ now.",
    "conditional statements" : "Based on the specified conditions, the response will change.",
    }
glossary_item_1 = glossary['print']
glossary_item_2 = glossary["list"]
glossary_item_3 = glossary["dictionary"]
glossary_item_4 = glossary["conditional statements"]

print(f"Print:\n{glossary_item_1}")
print(f"List:\n{glossary_item_2}")
print(f"Dictionary:\n{glossary_item_3}")
print(f"Conditional Statements:\n{glossary_item_4}")
```
Challenge 6.4. Glossary 2:
```python
glossary = {
    "print" : "Prints out the output in the terminal.",
    "list" : "Lists are also known as arrays.",
    "dictionary" : "The thing which you are currently looking at righ now.",
    "conditional statements" : "Based on the specified conditions, the response will change.",
    }
for name, definition in glossary.items():
    print(f"{name.title()}: {definition}")
```
Challenge 6.5. Rivers:
```python
rivers = {"Meghna" : "Bangladesh", "Ganges" : "India", "Irtysh" : "Russia", "Angara" : "Siberia", "Yukon" : "british Colombia"}
for water, location in rivers.items():
    print(f"The {water.title()} river flows through {location.title()}.")
    
for water in rivers.keys():
    print(water)

for location in rivers.values():
    print(location)
```
