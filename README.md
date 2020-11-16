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
    print ('None')
  else: 
      l.sort()
      max_number=l[0]
      for i in range(1,len(l)):
        if l[i] >max_number:
          max_number=l[i]
          print (max_number)
  return
```

- [Min Value](https://repl.it/@Admin7/minvalue)
```python
# copy & paste your solution here
def return_min(l):
  if len(l)==0: 
    print ('None')
  else: 
      l.sort()
      min_number=l[0]
      for i in range(1,len(l)):
        if l[i] < min_number:
          min_number=l[i]
          print (min_number)
  return 'a string to make sure all cases fail'
```

- [Extend](https://repl.it/@Admin7/extendlist)
```python
# copy & paste your solution here
```

- [Extend](https://repl.it/@Admin7/creatematrix)
```python
# copy & paste your solution here
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

