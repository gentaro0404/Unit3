 # code
```.py
# Wrire the function mystery and pass the tests contained in the file test_quiz_33.py

# the function takes two lists,list1 and list2, as input ans creates an empty list

def mystery(list1, list2:list):
    output = []
    for i in range(len(list1)):
        for j in range(len(list2)):
            if list1[i] == list2[j]:
                output.append(list1[i])
    return output

#print(mystery([1, 2, 3], [3, 4, 5]))

```
# test code
```.py
import pytest
from quiz33 import mystery

def test_empty_lists():
  assert mystery([], []) == []

def test_one_common_element():
  assert mystery([1, 2, 3], [3, 4, 5]) == [3]

def test_multiple_common_elements():
  assert mystery([1, 2, 3, 4], [3, 4, 5, 6]) == [3, 4]
  ```
  
# test pass
[]!
