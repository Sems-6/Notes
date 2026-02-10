## loop control statement
 ----------

- do while
----------
    - Break
    - Continue
    - Pass

### Break
----------
- used to change or alter the flow of execution
- the looping statement iterate till the text expression true
- the current iteration of the loop need to be terminated
- the break statement used in this case
- [ x ]

- syntax
    - Break

```python
for val in "welcome":
    if val == 'c':
        break
        print(wel)
        print(program terminated)
```

----------
## special characters

- character&description
- /d-> decimal digit equalent set[0-9]
- /D->non digit character equalent to [0-9]
- /s->white space character
- /S->non white space character
- /w->alphanumenic character [a-z A-Z 0-9]
- /W->non alphanumenic character [a-z A-Z 0-9]

- for eg:

```python
import re # a package
print(20 * " ")
res=findall("\S happy 123","happy")
print(res)
```

- There are many operation you can perform by making use of regular expression
- re package provide multiple method to perform queries in the input string
    1. re.match()
    2. re.search()
    3. re.findall()
    4. re.split()
    5. re.sub()
    6. re.compile()

