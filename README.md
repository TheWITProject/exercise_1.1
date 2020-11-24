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
```
# write your code here
def return_max(l):
  if len(l) == 0:
    return None
  else:
    m = l[0]
    for element in l:
      if element > m:
        m = element
  return m
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```
# write your code here
def return_min(l):
  if len(l) == 0:
    return None
  else:
    m = l[0]
    for element in l:
      if element < m:
        m = element
  return m
```

- [Extend](https://repl.it/@Admin7/extendlist)
```
# write your code here
def return_extended(l, iter):
  for element in iter:
    l.append(element)
  return l
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```
# write your code here
def create_matrix(h, w):
  row = list()
  for i in range(h):
    col = list()
    for j in range(w):
      if h == 1 and w == 1:
        break
      col.append('#')
    row.append(col)
  return row
```


#### Dictionaries
- [Receipt Tally](https://repl.it/@Admin7/receipttally)
```
# write your code here
def get_total(trans, category ):
  total = 0
  for element in trans:
    if(element['category'] == category):
      total = total + element['subtotal']
  return total
```

- [Translation](https://repl.it/@Admin7/translations)
```
# write your code here
def translation(word, lang):
  if word != '' and lang != '':
    return translations[word][lang]
  else:
    return ''
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```
# write your code here
def check_rsvp(event):
  total = 0
  for key in event:
    if event[key] == True:
      total += 1
  return total
```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```
# write your code here
def callbacker(l, callback):
  for i in range(len(l)):
    l[i] = callback(l[i])
  return l
```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```
# write your code here
def recursive_countdown(n):
  # this is our base case. when should this function stop?
  if (n == 1):
    print(1)
    return

  # this is our recursive case.
  print(n)
  recursive_countdown(n-1) # what argument should we provide?
  return
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

