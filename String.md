# Strings in Python

## Table of Contents

- [Strings in Python](#strings-in-python)
  - [Table of Contents](#table-of-contents)
  - [Declaration](#declaration)
  - [Multiple Line Strings](#multiple-line-strings)
  - [Characters](#characters)
    - [Looping through the characters of a String](#looping-through-the-characters-of-a-string)
  - [String length](#string-length)
  - [Check the presence of a String in another String](#check-the-presence-of-a-string-in-another-string)
  - [Slicing a String](#slicing-a-string)
  - [UpperCasing \& LowerCasing a String](#uppercasing--lowercasing-a-string)
  - [Replace String](#replace-string)
  - [Split](#split)
  - [Concatenation](#concatenation)

## Declaration

You can use Strings with single quote(') and double quotes(") in python.

for e.g:

```python
name = "hello"
# or
name = 'hello'
```

## Multiple Line Strings

In order to have multiple line Strings you can use triple double quotations(""") or triple single quotation('''):

for e.g:

```python
paragraph = """Hi this is a test paragraph,
in which we have multiple line sentences.
you can add as much you want!"""
# or
paragraph = '''Hi this is a test paragraph,
in which we have multiple line sentences.
you can add as much you want!'''
```

## Characters

Like other programming languages, Strings in python are also like arrays which means you can access the characters of the string as an element of an array.

for e.g:

```python
word = "Python"
p_character = word[0]
```

### Looping through the characters of a String

In order to loop through the characters of a String you can use __for__ loops:

for e.g:

```python
word = "Python"
for character in word:
    print(character)
```

## String length

Use __len()__ function to get the length of a String:

for e.g:

```python
word = "Python"
print(len(word))
```

## Check the presence of a String in another String

As we already know character is a String with one character.
Use __in__ keyword for this purpose(You can use the not version too):

for e.g:

```python
word = "Python"
print("P" in word)
print("S" not in word)
```

## Slicing a String

Sometimes you need a sub-string of the original String, then you should use slice the original String:

[starting_point : ending_point(not included)]

for e.g:

```python
sentence = "Python is amazing"
python_word = sentence[0:6]
```

## UpperCasing & LowerCasing a String

Make all of the characters capital case:

for e.g:

```python
word = "Python"
print(word.upper())
```

Make all of the characters small case:

for e.g:

```python
word = "Python"
print(word.lower())
```

## Replace String

Replacing a String with another String.

for e.g:

```python
sentence = "python is amazing"
print(sentence.replace("python", "Python"))
```

## Split

Spliting a String into into a list of substrings.

for e.g:

```python
languages = "python,c++,c,java,php"
print(languages.split(","))
```

## Concatenation

In order to concate or combine multiple strings you can use '+' operator:

for e.g:

```python
hello = "Hello"
world = "world"
print(hello + ", " + world + "!")
```
