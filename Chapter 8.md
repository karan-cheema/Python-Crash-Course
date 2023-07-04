##  Chapter 8 - Functions
Challenge 8.1. Message:
```python
def display_message():
    print("I am learning about functions.")

display_message()
```
Challenge 8.2. Favorite Book:
```python
def favorite_book(title):
    print(f"My favorite book is {title.title()}")

favorite_book()
```
Challenge 8.3. T-Shirt:
```python
def make_shirt(tsize, ttext):
    print(f"The size of your shirt is {tsize} and text in your shirt is {ttext}.")

make_shirt("M", "Python is cool")

def make_shirt(tsize, ttext):
    print(f"The size of your shirt is {tsize} and text in your shirt is {ttext}.")

make_shirt(ttext="Python is cool", tsize="M")
```
Challenge 8.4. Large Shirts:
```python
def make_shirt(tsize="L", ttext="I love Python"):
    print(f"The size of your shirt is {tsize} and text in your shirt is {ttext}.")

make_shirt()
```
Challenge 8.5. Cities:
```python
def describe_city(city, country="Argentina"):
    print(f"{city} is in {country}.")

describe_city("Rosario")
describe_city("Abidjan", "Ivory Coast")
describe_city("Córdoba")
```
