# Interview Collections

Here are the collected interview questions asked by companies in Singapore (unless stated otherwise). 
Please do contribute by making a PR if you want to! 🤙

## Indeed - Karat

### 1. Identify unbalanced entry and exit

```python
Input = [ 'James-Entry@2030','James-Exit@2000' ]
Output = ['James']
Explanation
since the entry is after exit, it is invalid and something is not balanced
```

### 2. Identify unbalanced entry and exit + Print the time period when when the room is occupied for more than 2 hours,

```python
Input = [ 'James-Entry@2030','James-Exit@2000','James-Exit@2050',' Rane-Enter@2040','Rane-Exit@2240', ]
Output = ['2030-2240']
Explanation
THe room is occupied for more than 2 hours. from 2030 to 2240
```

## Indeed - Batch Day

### 1. Keyword Matching

```python
keyword = ['Soft Eng','Senior Soft Eng', 'Mech Eng', 'Cook', 'Waiter', 'Truck Driver', 'Lorry Driver']
queryString = 'I need a Senior Soft Eng.`

output = 'Senior Soft Eng'
Explanation
highest matching word count.
```

### 2. Python-like validation function

```python
Rules:
1. every line that ends with a ':' is a command line
2. every line after a command line must have more whitespace than the command line
3. every line that is not a command line should either
    a. have same whitespace as the previous line
    b. have same whitespace as the previous command line

input = '''
print('adf')
for i in range(10):
  if i == 5:
    print('anjing')
  print('colek')
print('asdf')
'''
output = true
highest matching word count.
```

### 3. Product/System Design

> Hypothesis: Employers on our platform complains that they are reciving incompetent applicants. How can we investigate this and solve this problem?

## Shopee

### 1. balanced string

no of `a` must be equal to no of `b`

```python
input = 'ab'
output = true

input ='abbb'
output = false
```

### 2. longest balanced substring

```python
input = 'abaababa`
output = 'abab' or 'baba'
explanation.
abab is the longest balanced substring in the input.
```
