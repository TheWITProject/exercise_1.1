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
def return_max(l):
  if len(l) < 1:
    return 'None'
  else:
    return(max(l))
```
- [Min Value](https://repl.it/@Admin7/minvalue)

```python

def return_min(l):
  if len(l) == 0:
    return None
  result = l[0]
  for i in l:
    if i < result:
      result = i
  return result
```

- [Extend](https://repl.it/@Admin7/extendlist)
```python
def return_extended(l, iter):
  for i in iter:
    l.append(i)
  return l
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python
def create_matrix(h, w):
  result = []
  for i in range(h):
    row = []
    for x in range(w):
      row.append('#')
    result.append(row)
  return result
```


#### Dictionaries
- [Receipt Tally](https://repl.it/@Admin7/receipttally)
```python
def get_total(h, w):
  total = 0
  new = 0
  for i in h:
    for key,value in i.items():
        if value == w:
            total = i.get('subtotal')
  return total
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

