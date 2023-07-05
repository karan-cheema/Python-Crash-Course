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
Challenge 8.6. City Name:
```python
def city_country(city_name, country_name):
    citycountry = f"{city_name} {country_name}"
    return citycountry.title()

city_and_country = city_country("Santiago", "Chile")
print(city_and_country)
```

Challenge 8.7. Album:
```python
def make_album(artist_name, album_name, songs=None):
    album = {'artist' : artist_name, 'album' : album_name}
    if songs:
        album['songs'] = songs
    return album

album_1 = make_album("Everywhere you go", "Mari Kvien Brunvoll")
print(album_1)
album_2 = make_album("2845", "Convexion", 10)
print(album_2)
album_3 = make_album("Bleach", "Nirvana")
print(album_3)


```

Challenge 8.8. 
