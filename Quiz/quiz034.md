 # code
```.py
#Create a new Python function called to_roman(num) that takes a singke interger as input. It ertuens a string representing the Roman nueral equivalent of the input number
#Conditions: The function should only work for integers below 100,if the input is greater than 100,raise a ValueError with a message indicating that the ipuut must be less than or equal to 100.

class quiz034:
    def __init__(self, num:int):
        self.num = num
    def solve(self):
        out=""
        roman= {100:'C', 90:'XC', 50:'L', 40:'XL', 10:'X', 9:'IX', 5:'V', 4:'IV', 1:'I'}
        if self.num < 1 or self.num >100:
            raise ValueError("Number must be between 1 and 100")
        if not isinstance(self.num,int):
            raise TypeError("Number must be an integer")
        while self.num>0:
            for i in roman.keys():
                if self.num>=i:
                    out+=roman[i]
                    self.num-=i
                    break
        return out

def to_roman(num:int):
    out = ""
    roman = {100: 'C', 90: 'XC', 50: 'L', 40: 'XL', 10: 'X', 9: 'IX', 5: 'V', 4: 'IV', 1: 'I'}
    if num < 1 or num > 100:
        raise ValueError("Number must be between 1 and 100")
    if not isinstance(num, int):
        raise TypeError("Number must be an integer")
    while num > 0:
        for i in roman.keys():
            if num >= i:
                out += roman[i]
                num -= i
                break
    return out

```
# test code
```.py
from quiz34 import to_roman

import pytest


def test_to_roman():
    assert to_roman(1) == 'I'
    assert to_roman(4) == 'IV'
    assert to_roman(9) == 'IX'
    assert to_roman(37) == 'XXXVII'
    assert to_roman(44) == 'XLIV'
    assert to_roman(50) == 'L'
    assert to_roman(99) == 'XCIX'
    assert to_roman(100) == 'C'
    assert to_roman(77) == 'LXXVII'
    assert to_roman(93) == 'XCIII'


def test_to_roman_exceptions():
    # check that the program raises a ValueError
    with pytest.raises(ValueError):
        to_roman(101)
  ```
  
# test pass
[]!
