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
>>> tup = (21,36,14,25)
>>> tup [1]
36
>>> tup []1 = 33
  File "<stdin>", line 1
    tup []1 = 33
         ^
SyntaxError: invalid syntax
>>> tup[1] = 33
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment
>>> # in tuple we can not change the value
>>> # use : when you have a list and you dont want anyone change it's value you can use tuple, since there is no changes it's ittration will we fast
>>>
>>>
>>> Set in Python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Set' is not defined. Did you mean: 'set'?
>>> #set in Python
>>>
>>> s = {22,25,14,21,5}
>>> s
{5, 21, 22, 25, 14}
>>> #set is not followin the secuance
>>> s[2]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'set' object is not subscriptable
>>> # indexing is not sopperted in set
>>>
>>> #Dictionary in python
>>> data = {1:'pushp', 2 : 'Harsh', 3: 'Kiran'}
>>> data[2]
'Harsh'
>>> data[1]
'pushp'
>>> data.get(1)
'pushp'
>>> data.get(3,'Not Found')
'Kiran'
>>> keys =['Navin', 'Kiran', 'Harsh']
>>> valuses = ['python','java', 'js']
>>> data = dict(zip(keys,values))
>>> data
{'Navin': 9.5, 'Kiran': 'navin', 'Harsh': 25}
>>> keys =['Navin', 'Kiran', 'Harsh']
>>>  valuses = ['python','java', 'js']
  File "<stdin>", line 1
    valuses = ['python','java', 'js']
IndentationError: unexpected indent
>>> keys =['Navin', 'Kiran', 'Harsh']
>>> valuses = ['python','java', 'js']
>>> nide = dict(zip(keys,values))
>>> nide
{'Navin': 9.5, 'Kiran': 'navin', 'Harsh': 25}
>>> nide['Monika'] = 'cs'
>>> nide
{'Navin': 9.5, 'Kiran': 'navin', 'Harsh': 25, 'Monika': 'cs'}
>>> del nide['Harsh']
>>> nide
{'Navin': 9.5, 'Kiran': 'navin', 'Monika': 'cs'}
>>> keys =['Navin', 'Kiran', 'Harsh']
>>> values = ['python','java', 'js']
>>> nide = dict(zip(keys,values))
>>> nide
{'Navin': 'python', 'Kiran': 'java', 'Harsh': 'js'}
>>> nide['Kanika'] = 'cs'
>>> nide
{'Navin': 'python', 'Kiran': 'java', 'Harsh': 'js', 'Kanika': 'cs'}
>>> del nide[Harsh]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Harsh' is not defined. Did you mean: 'hash'?
>>> del nide['Harsh']
>>> nide
{'Navin': 'python', 'Kiran': 'java', 'Kanika': 'cs'}
>>> prog = {'js':'Atom', 'cs':'VS', 'Python':['pycharm','sublime'],'java':{'JSE':'Netbeans','JEE':'Eclipse'}}
>>> prog
{'js': 'Atom', 'cs': 'VS', 'Python': ['pycharm', 'sublime'], 'java': {'JSE': 'Netbeans', 'JEE': 'Eclipse'}}
>>> prog[''js]
  File "<stdin>", line 1
    prog[''js]
         ^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> prog['js']
'Atom'
>>> prog['Python'][1]
'sublime'
>>> prog['python']
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'python'
>>> prog['Python']
['pycharm', 'sublime']
>>> prog['java']
{'JSE': 'Netbeans', 'JEE': 'Eclipse'}
>>> prog['java']['JEE']
'Eclipse'
