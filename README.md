## Summary
You will be working through some coding problems on [repl.it](https://www.repl.it/). When you have solved a problem, please copy and paste the solution into the codeblock below each question. Many of these problems can be solved using built-in methods. Try to solve them with and without!

Before you get started:
- clone this repo
- create and checkout a personal branch of this repo `git checkout -b <YOUR_NAME>_exercise_1.1`

When you are done:
- push up your personal branch `git push origin <YOUR_NAME>_exercise_1.1`
- open a PR for your branch


## Exercises

#### Loops & Lists
- [Max Value](https://repl.it/@Admin7/maxvalue)
```python
# copy & paste your solution here
def return_max(l):
  if len(l)==0: 
    return None
  else: 
      l.sort()
  return l[-1]
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```python
# copy & paste your solution here
def return_min(l):
  if len(l)==0: 
    return None
  else: 
      l.sort()
  return l[0]
```

- [Extend](https://repl.it/@Admin7/extendlist)
```python
# copy & paste your solution here
def return_extended(l, iter):
  l.extend(iter)
  return l
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python
# copy & paste your solution here
def create_matrix(h, w):
    matrix=[]
    for i in range(h):
        row=[]
        for j in range(w):
          if w==1:
            break
          value='#'
          row.append(value)
        matrix.append(row)
    return matrix
```


#### Dictionaries
- [Receipt Tally](https://repl.it/@Admin7/receipttally)
```python
# copy & paste your solution here
```

- [Translation](https://repl.it/@Admin7/translations)
```python
# copy & paste your solution here
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python
# copy & paste your solution here
```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python
# copy & paste your solution here
```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```python
# copy & paste your solution here
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

