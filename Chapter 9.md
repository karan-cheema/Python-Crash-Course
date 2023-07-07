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
