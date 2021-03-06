# leap-year

##### A little program that takes a year and determines if it is a leap year.

#### By Epicodus Lessons

## Description

This application takes a single input from the user and evaluates whether it is a leap year based on divisibility by 4, 100 and 400.  

## Setup

Install leap-year by cloning this repository.

## Tests

| Behavior | Input | Output |
| ------------- |:-------------:| -----:|
| a year that is NOT a leap year | 1993 | false |
| a year that is divisible by 4 | 2004 | true |
| a year that is divisible by 100 | 1900 | false |
| a year that is divisible by 400 | 2000 |true |

**Describe: isLeapYear()** <br>
Test: "It returns false for years that are not a leap year" <br>
Expect(isLeapYear(1993)).toEqual(false);

Test: "It returns true for years that are divisible by 4" <br>
Expect(isLeapYear(2004)).toEqual(true);

Test: "It returns false for years that are divisible by 100" <br>
Expect(isLeapYear(2100)).toEqual(false);

Test: "It returns true for years that are divisible by 400" <br>
Expect(isLeapYear(2000)).toEqual(true);

## Technologies Used

Application: JavaScript and jQuery
Testing:  Mocha and Chai

### Legal

Copyright (c) 2015 **Epicodus**

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
