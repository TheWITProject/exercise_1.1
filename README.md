## Summary
You will be working through some coding problems on [repl.it](https://www.repl.it/). 
When you have solved a problem, please copy and paste the solution into the code block 
below each question. Many of these problems can be solved using built-in methods. 
Try to solve them with and without!

Before you get started:
- clone this repo
- create and checkout a personal branch of this repo `git checkout -b <YOUR_NAME>_exercise_1.1`

When you are done:
- push up your personal branch `git push origin <YOUR_NAME>_exercise_1.1`
- open a PR for your branch


## Exercises

#### Loops & Lists
- [Max Value](https://repl.it/@Admin7/maxvalue)
```python#
def return_max(l):

  if not l:
    return None
  
  max = -math.inf
  for i in range(len(l)):
   if l[i] > max:
     max = l[i]

  return max
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```python#
def return_min(l):

  if not l:
    return None
  
  min = math.inf
  
  for i in range(len(l)):
   if l[i] < min:
     min = l[i]
  
  return min

```

- [Extend](https://repl.it/@Admin7/extendlist)
```python#
def return_extended(l, iter):

  l.extend(iter)

  
  return l
  
  
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python#
def create_matrix(h, w):
  list = []
  list1 = []

  for j in range(w):
    if(w>1):
     list.append('#')

  for i in range(h):
    list1.append(list)

  return list1
```


#### Dictionaries
- [Receipt Tally](https://repl.it/@Admin7/receipttally)
```python#
def get_total(trans, k ):
  
  total = 0

  

  for i in range(len(trans)):
    if k == trans[i]['category']:
      total += trans[i]['subtotal']
  
  return total
```

- [Translation](https://repl.it/@Admin7/translations)
```python#
def translation(word, lang):
  if word in translations.keys():
   return translations[word][lang]
  
  return ("")
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python#
def check_rsvp(event):
  count = 0

  for value in event.values():
    if value == True:
      count += 1

  return count 
```


#### Functions
- [Ain't No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python#
def callbacker(l, callback):

  a = []

  for i in range(len(l)):
    x = callback(l[i])
    a.append(x)

  return a
```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```python#
def recursive_countdown(n):
  # this is our base case. when should this function stop?
  if (n == 0):
    return
  print(n)
  # this is our recursive case.
  recursive_countdown(n-1) # what argument should we provide?
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

