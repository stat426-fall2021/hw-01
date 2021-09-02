# Homework 1: Basic Python
### Stat 426, Fall 2021

---

**1.  Write a Python function that will compute the Euclidean distance between any two points (x<sub>1</sub>, y<sub>1</sub>) and (x<sub>2</sub>, y<sub>2</sub>).  Use your function to find the distance between (1,3) and (7,11).**


-----
**2. Write a Python function that computes the value of ``n + nn + nnn`` where ``n`` is an integer.  For example if,  ``n=2``, the function should return ``246`` (which is the sum of 2+22+222).**  

*Example output:*
```
In [1]: your_function(2)
Out[1]: 246
```


-----
**3. Write a Python function that determines if ``n`` is a perfect square, where ``n`` is an integer.  The function return either "False" or "n is a perfect square of x"  (where ``n`` and ``x`` are appropriate for the input).**

*Example output:*

```
In [1]: your_function(24)
Out[1]: False

In [2]: your_function(25)
Out[2]: 25 is a perfect square of 5
```


----
**4. Write a Python function that checks whether a string is a palindrome or not.  A palindrome is a word or phrase that reads the same forwards and backwards (ignoring spaces), such as "madam" or "nurses run".**

*Example output:*

```
In [1]: your_function('madam')
Out[1]: True

In [2]: your_function('nurses run')
Out[2]: True

In [3]: your_function('starlight')
Out[3]: False
```



----
**5. Write a Python function that accepts a string and calculates the number of upper case letters, the number of lower case letters, and the number of spaces.  The function should return a dictionary where the keys are "upper", "lower", and "space" and the value is the number of occurences.  See the example output below.**    
(Hint:  check out what methods are available for strings.)  

 *Example output:*

```
In [1]: s = "HELLO!! How are you today?"
        your_function(s)
Out[1]: {'upper': 6, 'lower': 13, 'space': 4}

```



----
**6. Write a Python function that accepts a string a returns a dictionary where the key word is a word length and the value is a list of all the words that are that word length.  See the example output below.**  

*Example output:*

```
In [1]: s = "It is a truth universally acknowledged
that a single man in possession of a good fortune
must be in want of a wife"

In [2]: your_function(s)

Out[2]: {1: ['a', 'a', 'a', 'a'],
         2: ['It', 'is', 'in', 'of', 'be', 'in', 'of'],
         3: ['man'],
         4: ['that', 'good', 'must', 'want', 'wife'],
         5: ['truth'],
         6: ['single'],
         7: ['fortune'],
         10: ['possession'],
         11: ['universally'],
         12: ['acknowledged']}
```


----
**7.  Use a list comprehension to make a list all the numbers between 0 and 300 that have a 3 in them AND are divisible by 3. How many numbers are there?**

*Desired result (just the first few elements)*
```
Out[1]: [3,
         30,
         33,
         36,
         39,
         63,
         ...
         300]

```

----
**8.  Use a dictionary comprehension to create a dictionary where the keys are the numbers between 100 and 200 (inclusive) that are divisble by 10 and the value associated with each key is the key divided by 100.**

*Desired result*
```
Out[1]: {100: 1.0,
         110: 1.1,
         120: 1.2,
         130: 1.3,
         140: 1.4,
         150: 1.5,
         160: 1.6,
         170: 1.7,
         180: 1.8,
         190: 1.9,
         200: 2.0}
 ```

---
**9. Given a sentance that is a python string, make a list of words.**

```
s = "It is a truth universally acknowledged
that a single man in possession of a good fortune
must be in want of a wife"
```
*Desired result*
```
['It',
 'is',
 'a',
 'truth',
 'universally',
 'acknowledged',
 'that',
 'a',
 'single',
 'man',
 'in',
 'possession',
 'of',
 'a',
 'good',
 'fortune',
 'must',
 'be',
 'in',
 'want',
 'of',
 'a',
 'wife']
```

---
**10. Given a list of words, make a sentence that is a python string.**

```
words = ['It',
         'is',
         'a',
         'truth',
         'universally',
         'acknowledged',
         'that',
         'a',
         'single',
         'man',
         'in',
         'possession',
         'of',
         'a',
         'good',
         'fortune',
         'must',
         'be',
         'in',
         'want',
         'of',
         'a',
         'wife']
```
*Desired result*
```
"It is a truth universally acknowledged
that a single man in possession of a good fortune
must be in want of a wife"
```
