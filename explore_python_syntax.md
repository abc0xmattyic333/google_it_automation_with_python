# Explore Python Syntax
Python is a flexible programming language used in a wide range of different fields, including softeware development, machine learning, and data analysis. Python is one of the most popular languages used for data professionals, so for getting familiar with its fundamental syntax and semantics will be useful for your future career.

## The language of Python
People use language to communicate and give instructions to each other. Computers do the same thing, except they use langauages like Python, C++, and Java.

Python syntax includes words that represent objects and commands, as well as punctuation that gives the words structure, hierarchy, and context. Together, the words and punctuation communicate ideas and processes; this is known as semantics. Semantics is the meaning conveyed by the syntax. The best way to learn syntax and semantics is through exposure. Practice coding and become familiar and comfortable with reading other people’s code. In addition, there are some general conventions that practitioners use to help maintain stylistic uniformity within the language. 

Coding languages are similar to spoken languages in that they have a way to classify words according to their function. For example, English sentences are composed of nouns, verbs, prepositions, etc. Here are some of the basics:

Variables: Represent data stored as strings, tuples, dictionaries, lists, and objects (note: future readings explain these categories)

Keywords: Special words that are reserved for specific purposes and that can only be used for those purposes

```
- 1. in
- 2. not
- 3. or
- 4. for
- 5. while
- 6. return
```

Operators: Symbols that perform operations on objects and values.

```
- 1. +
- 2. -
- 3. *
- 4. /
- 5. //
- 6. %
- 7. //
- 8. >
- 9. <
- 10. ==
```

Expressions: A combination of numbers, symbols, and variables to compute and return a result upon evalutaion.

Functions: A group of related statements to perform a task and return a value.

Take a look at the below example. 

```
def to_celsius(x):
   '''Convert Fahrenheit to Celsius'''
   return (x-32) * 5/9


to_celsius(75)
```

Conditional statements: Sections of code that direct program execution based on specified conditions.

```
number = -4


if number > 0:
   print('Number is positive.')
elif number == 0:
   print('Number is zero.')
else:
   print('Number is negative.')
```

As you'll surely discover, Python generates syntax errors for incorrectly used keywords and syntax.

```
print(This will throw an error because I didn’t make it a string.)
```

Naming rules and conventions
When assigning names to objects, programmers adhere to a set of rules and conventions which will help to standardize code and make it more accessible to everyone. Here are some naming rules and conventions that you should know:

- Names cannot be spaces.
- Names may be a mixture of upper and lower case characters.
- Names can't start with a number but may contain numbers after the first character.
- Variable names and function names should be written in snake_case, which means that all letters are lowercase and words are seperated using an underscore.
- Descriptive names are better than cryptic abbreviations because they help other programmers (and you) read and interpret your code. For example, student_name is better than sn. It may feel excessive when you write it, but when you return to your code you'll find it much easier to understand.

Tim Peters, a Python programmer, wrote this now-famous "poem" of guiding principles of coding in Python:

The Zen Of Python
```
"Beautiful is better than ugly.

Explicit is better than implicit.

Simple is better than complex.

Complex is better than complicated.

Flat is better than nested.

Sparse is better than dense.

Readability counts.

Special cases aren't special enough to break the rules.

Although practicality beats purity.

Errors should never pass silently.

Unless explicitly silenced.

In the face of ambiguity, refuse the temptation to guess.

There should be one—and preferably only one—obvious way to do it.

Although that way may not be obvious at first unless you're Dutch.

Now is better than never.

Although never is often better than *right* now.

If the implementation is hard to explain, it's a bad idea.

If the implementation is easy to explain, it may be a good idea."
```