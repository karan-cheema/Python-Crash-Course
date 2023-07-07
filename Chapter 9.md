## Chapter 9 - Classes
Challenge 9.1. Restaurant:
```python
class Restaurant:
    
    def __init__(self, name, cuisine):
        self.name = name
        self.cuisine = cuisine
    
describe_restaurant = Restaurant("Pizza Hut", "Italian")
print(f"{describe_restaurant.name}, {describe_restaurant.cuisine}")
```
Challenge 9.2. Three Restaurants:
```python
class Restaurant:
    
    def __init__(self, name, cuisine):
        self.name = name
        self.cuisine = cuisine
    
describe_restaurant = Restaurant("Pizza Hut", "Italian")
describe_restaurant2 = Restaurant("Dominoz", "Italian")
describe_restaurant3 = Restaurant("McDonald's", "American")
print(f"{describe_restaurant.name}, {describe_restaurant.cuisine}")
print(f"{describe_restaurant2.name}, {describe_restaurant2.cuisine}")
print(f"{describe_restaurant3.name}, {describe_restaurant3.cuisine}")
```
