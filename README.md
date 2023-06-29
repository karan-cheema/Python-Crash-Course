# Python-Crash-Course
A book by Eric Matthes

## Chapter 1: Getting Started
Chapter 1 does not contain any challenges.
## Chapter 2: Variables and Simple Data Types
Challenge 2.1: Assign a message to a variable, and then print that message.
```python
message = "I am the answer for exercise 2.1. I LOVE CODING"
print(message)
```
Challenge 2.2: Assign a message to a variable, and print that message. Then change the value of the variable to a new message, and print the new message.
```python
message = "I am the answer of challenge 2.2"
print(message)
message = "I love coding"
print(message)
```
Challenge 2.3: **Personal Message** - 
```python
name = "Anonymous"
print(f"Hello {name}, would you like to learn some Python today?")
```
Challenge 2.4: **Name Cases** -
```python
name = "Anonymous"
print(name.lower())
print(name.upper())
print(name.title())
```
Challenge 2.5: **Famous Quote:**
```python
print('\n\tAlber Einstein once said, "A person who never made a\n\tnever tried anything new."')
```
Challenge 2.6: **Famous Quote 2:**
```python
famous_person  = "Alber Einstein"
print(f'\n\t{famous_person} once said, "A person who never made a\n\tnever tried anything new."')
```
Challenge 2.7: **Stripping Name:**
```python
random_name = " \t\nAnonymous "
random_name.rstrip()
random_name.lstrip()
random_name.strip()
