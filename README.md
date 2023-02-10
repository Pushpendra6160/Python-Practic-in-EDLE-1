# Python-Practic-in-EDLE-1
Python Practice  
>>> 3+4
7
>>> 6+4
10
>>> 2+3
5
>>> 9-8
1
>>> 4*6
24
>>> 8/4
2.0
>>> 5/2
2.5
>>> 8//2
4
>>> 8+9-10
7
>>> 8+9-
  File "<stdin>", line 1
    8+9-
        ^
SyntaxError: invalid syntax
>>> 2**3
8
>>> 5**3
125
>>> 10/3
3.3333333333333335
>>> 10%3
1
>>> 'Navin'
'Navin'
>>> print('navin')
navin
>>> print('Navin's laptop')
  File "<stdin>", line 1
    print('Navin's laptop')
          ^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> print("Navin's Laptop")
Navin's Laptop
>>> print("navin "laptop"")
  File "<stdin>", line 1
    print("navin "laptop"")
          ^^^^^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> print ('navin\'s'"laptop"')
  File "<stdin>", line 1
    print ('navin\'s'"laptop"')
                             ^
SyntaxError: unterminated string literal (detected at line 1)
>>> print('navin\'s "laptop"')
navin's "laptop"
>>> 'navin'+"navin"
'navinnavin'
>>> 10*"navin"
'navinnavinnavinnavinnavinnavinnavinnavinnavinnavin'
>>> print('c:\docs\navin')
c:\docs
avin
>>> print(r'c:\docs\navin')
c:\docs\navin
>>> 2+3
5
>>>
>>>
>>> x = 2
>>> x+3
5
>>> y = 3
>>> x+y
5
>>> x = 9
>>> x + y
12
>>> x
9
>>> abc
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'abc' is not defined. Did you mean: 'abs'?
>>> x+10
19
>>> _+y
22
>>> name = "youtube"
>>> name
'youtube'
>>> name + 'rock'
'youtuberock'
>>> name[0]
'y'
>>> name[6]
'e'
>>> name[8]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
IndexError: string index out of range
>>> name[-1]
'e'
>>> name[-7]
'y'
>>> name[0:2]
'yo'
>>> name[1:4]
'out'
>>> name[1:]
'outube'
>>> name[:4]
'yout'
>>> name[3:10]
'tube'
>>> name[0:3] = 'My'
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> #string in python is immutable
>>> 'my' + name[3:]
'mytube'
>>> 'my ' + name[3:]
'my tube'
>>> myname = 'Pushpendra Singh'
>>> len(myname)
16
>>> myname = 'PushpendraSingh'
>>> len(myname)
15
>>>
>>>
>>> #List in Python
>>>
>>> nums = [25,12,36,95,14]
>>> nums
[25, 12, 36, 95, 14]
>>> nums[0]
25
>>> nums[4]
14
>>> nums[2:]
[36, 95, 14]
>>> nums[]
  File "<stdin>", line 1
    nums[]
         ^
SyntaxError: invalid syntax
>>> 1nums[]
  File "<stdin>", line 1
    1nums[]
    ^
SyntaxError: invalid decimal literal
>>> nums[]
  File "<stdin>", line 1
    nums[]
         ^
SyntaxError: invalid syntax
>>> nums[
...
...
... ]
  File "<stdin>", line 4
    ]
    ^
SyntaxError: invalid syntax
>>> nums[-1]
14
>>> nums[-5]
25
>>> names = ['navin','kiran','john']
>>> names
['navin', 'kiran', 'john']
>>> values = [9.5, 'navin', 25]
>>> values
[9.5, 'navin', 25]
>>> mil = [nums, names]
>>> mil
[[25, 12, 36, 95, 14], ['navin', 'kiran', 'john']]
>>> nums.append(45)
>>> nums
[25, 12, 36, 95, 14, 45]
>>> nums.insert(2,77)
>>> nums
[25, 12, 77, 36, 95, 14, 45]
>>> nums.remove(14)
>>> nums
[25, 12, 77, 36, 95, 45]
>>> nums.pop(1)
12
>>> nums
[25, 77, 36, 95, 45]
>>> nums.pop()
45
>>> nums
[25, 77, 36, 95]
>>> del nums[2:]
>>> nums
[25, 77]
>>> nums.extend([29,12,14,36])
>>> nums
[25, 77, 29, 12, 14, 36]
>>> min(nums)
12
>>> max(max)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'builtin_function_or_method' object is not iterable
>>> max(nums)
77
>>> sum(nums)
193
>>> nums.sort()
>>> nums
[12, 14, 25, 29, 36, 77]
>>>
>>> Touple in Python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Touple' is not defined. Did you mean: 'tuple'?
>>>
>>> #Touple in Python
>>>
>>>
