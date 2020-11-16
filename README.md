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

def return_max(l):
  if len(l) < 1:
    return 'None'
  else:
    return(min(l))
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
def translation(word, lang):
  ans = ''
  for key,value in translations.items():
    if key == word:
      ans = translations[key]
      ans = ans.get(lang)
  return ans
```

- [Check RSVP](https://repl.it/@Admin7/checkrsvp)
```python
def check_rsvp(event):
  attending = []
  for key, value in event.items():
    if value == True:
      attending.append(value)
  return len(attending)
```


#### Functions
- [Aint No Callback Girl](https://repl.it/@Admin7/aintnocallbackgirl)
```python
def callbacker(l, callback):
  return list(map(callback,l))
```

- [Recursion?! Recursive Countdown](https://repl.it/@Admin7/recursivecountdown)
```python
def recursive_countdown(n):
    if n > 0:
        print(n)
        return recursive_countdown(n-1)
```


## Done already?
Practice more problems on [CodeWars](https://codewars.com).

