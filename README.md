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
  result = l[0]
  if len(l) == 0:
    return None
  for i in l:
    if i > result:
      result = i
  return result

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
def return_extended(e, iter):
  for i in iter:
    e.append(i)
  return e

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
def get_total(x, y):
  total = 0
  for tally in x:
    if tally[‘y’] == y:
      total = total + tally['subtotal']
  return total

```

- [Translation](https://repl.it/@Admin7/translations)
```python
def translation(word, lang):
  a = ''
  for key,value in translations.items():
    if key == word:
      a = translations[key]
      a = a.get(lang)
  return a

```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python
def check_rsvp(event):
  total = 0
  for i in event:
    if event.get(i) == True:
      total = total + 1
  return total

```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python
def callbacker(l, callback):
  return list(map(callback, l))

```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```python
def recursive_countdown(n):
  if (n == 1):
    print(1)
  else:
    print(n)
    recursive_countdown(n-1)

```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

