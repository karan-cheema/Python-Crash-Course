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
Challenge 9.3. Users:
```python
class User:
    def __init__(self, first, last, email, age):
        self.first = first
        self.last = last
        self.email = email
        self.age = age

user1 = User("Marcus", "Peppers", "MarcusRPeppers@jourrapide.com", 27)
user2 = User("Minnie", "Wiese", "MinnieWWiese@jourrapide.com", 36)
user3 = User("Audrey", "Salazar", "AudreyWSalazar@rhyta.com", 52)
print(f"Hello, {user1.first} {user1.last} your {user1.email} and your age is {user1.age}.")
print(f"Hello, {user2.first} {user2.last} your {user2.email} and your age is {user2.age}.")
print(f"Hello, {user3.first} {user3.last} your {user3.email} and your age is {user3.age}.")
```
