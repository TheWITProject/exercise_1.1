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
  if len(l)== 0:
    return None
  return max(l)
def return_min(l):
  if len(l)== 0:
    return None
  return min(l)
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```python
def return_min(l):
  if len(l)== 0:
    return None
  return min(l)
```

- [Extend](https://repl.it/@Admin7/extendlist)
```python
for i in iter:
    l.append(i)
  return(l)
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python
def create_matrix(h, w):
  # a list to hold the list
  aList = []
  for i in range(h):
    #make a list for each row
    bList = []
    for x in range(w):
      if w == 1:
        break
      else:
        bList.append('#')
    aList.append(bList)
  return aList
```


#### Dictionaries
- [Receipt Tally](https://repl.it/@Admin7/receipttally)
```python
def get_total(h, w):
  total = 0
  for transaction in transactions:
    if transaction.get("category") == w:
      total += transaction.get("subtotal")
  return total
```

- [Translation](https://repl.it/@Admin7/translations)
```python
def translation(word, lang):
  if len(word) == 0:
    return str('')
  return translations[word][lang]
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python
def check_rsvp(event):
  count = 0
  for attendee in event:
    if event[attendee]:
      count += 1
  return count
```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python
def callbacker(l, callback):
  newlist = []
  if callback == double:
    for num in l:
      newlist.append(double(num))
  else:
    callback == add_one
    for num in l:
      newlist.append(add_one(num))
  return newlist
```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```python
def recursive_countdown(n):
  # this is our base case. when should this function stop?
    if n < 2:
        return n
    else:
        print (n)
  # this is our recursive case.      
        return(recursive_countdown(n-1))
print(recursive_countdown(5))
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

