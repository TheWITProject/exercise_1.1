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
def return_max(aList):
  if len(aList) == 0:
    return None
  return max(aList)
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```python
# copy & paste your solution here
def return_min(aList):
  if len(aList) == 0:
    return None
  return min(aList)
```

- [Extend](https://repl.it/@Admin7/extendlist)
```python
# copy & paste your solution here
def return_extended(aList, iter):
  for item in iter:
    aList.append(item)
  return aList
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python
# copy & paste your solution here
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
# copy & paste your solution here
def get_total(h, w):
  total = 0
  for transaction in transactions:
    if transaction.get("category") == w:
      total += transaction.get("subtotal")
  return total 
```

- [Translation](https://repl.it/@Admin7/translations)
```python
# copy & paste your solution here
def translation(word, lang):
  for translation in translations: 
    if translation == word:
     return translation.get(lang) **GOT STUCK**
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python
# copy & paste your solution here
def check_rsvp(event):
  count = 0
  if event == "birthday_party":
    attendees = birthday_party
    for attendee in attendees:
      if attendees.get(attendee) == True:
        count += 1 
  else: 
    attendees = met_gala
    for attendee in attendees:
      if attendees.get(attendee):
        count += 1 
  return count 
```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python
# copy & paste your solution here
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
# copy & paste your solution here
def recursive_countdown(n):
  # this is our base case. when should this function stop?
  while (n != 0):
    print(n)
    n -= 1

  # this is our recursive case.
  return recursive_countdown(5) # what argument should we provide?
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).


