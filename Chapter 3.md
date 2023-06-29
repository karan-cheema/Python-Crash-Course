## Chapter 3 - Introducing Lists
Challenge 3.1. Names: Store the names of a few of your friends in a list called names.
```python
friends = ["Giovanni", "Harley", "Katelynn", "Alisha", "Emmalee"]
print(friends[0])
print(friends[1])
print(friends[2])
print(friends[3])
print(friends[4])
```
Challenge 3.2. Greetings: 
```python
friends = ["Giovanni", "Harley", "Katelynn", "Alisha", "Emmalee"]
print(f"Hello {friends[0]}, how are you?")
print(f"Hello {friends[1]}, how are you?")
print(f"Hello {friends[2]}, how are you?")
print(f"Hello {friends[3]}, how are you?")
print(f"Hello {friends[4]}, how are you?")
```
Challenge 3.3. Your own list:
```python
candy = ["Pixie Stix", "Nik-L-Nips", "Milk Duds", "Hershey's Kisses", "Sour Patch Kids"]
print(f"I would like to eat {candy[0]}")
print(f"I would like to eat {candy[1]}")
print(f"I would like to eat {candy[2]}")
print(f"I would like to eat {candy[3]}")
print(f"I would like to eat {candy[4]}")
```
Challenge 3.4. Names: Store the names of a few of your friends in a list called names.
```python
guest_list = ["Michael Jordan", "Victoria Becham", "Kanye West"]
print(f"Hi {guest_list[0]}, you are invited to attend our dinner.")
print(f"Hi {guest_list[1]}, you are invited to attend our dinner.")
print(f"Hi {guest_list[2]}, you are invited to attend our dinner.")
```
Challenge 3.5. Changing Guest  List:
```python
not_coming = "Kanye West"
new_person = "Jeananne Goossen"
print(f"Hi guests, I got some news for you. {not_coming} is not coming to the party, but don't be sad as we are now inviting {new_person} for the dinner.")

guest_list.remove(not_coming)
guest_list.insert(2, new_person)
print(guest_list)

print(f"Hi {guest_list[0]}, you are invited to attend our dinner.")
print(f"Hi {guest_list[1]}, you are invited to attend our dinner.")
print(f"Hi {guest_list[2]}, you are invited to attend our dinner.")
```
Challenge 3.6. 
```python
guest_list.insert(0, "Hugh Laurie")
guest_list.insert(1, "Kate Winslet")
guest_list.append("Mary-Louise Parker")
print(f"Hi {guest_list[0]}, we would like you to know that you are invited for our dinner.")
print(f"Hi {guest_list[1]}, we would like you to know that you are invited for our dinner.")
print(f"Hi {guest_list[2]}, we would like you to know that you are invited for our dinner.")
print(f"Hi {guest_list[3]}, we would like you to know that you are invited for our dinner.")
print(f"Hi {guest_list[4]}, we would like you to know that you are invited for our dinner.")
print(f"Hi {guest_list[5]}, we would like you to know that you are invited for our dinner.")
```
Challenge 3.7
```python
print("UPDATE: Only two guests can be invited for our dinner.")
guest_removed = guest_list.pop()
print(f"We are really sorry {guest_removed} but due to unfortunate events we have to recede your dinner invite")
guest_removed = guest_list.pop()
print(f"We are really sorry {guest_removed} but due to unfortunate events we have to recede your dinner invite")
guest_removed = guest_list.pop()
print(f"We are really sorry {guest_removed} but due to unfortunate events we have to recede your dinner invite")
guest_removed = guest_list.pop()
print(f"We are really sorry {guest_removed} but due to unfortunate events we have to recede your dinner invite")
print(f"Hi {guest_list[0]}, you are still invited to our dinner.")
print(f"Hi {guest_list[1]}, you are still invited to our dinner.")
del guest_list[0]
del guest_list[0]
print(guest_list)
```
