# scratch-programming



# Week 1

### Write a beautiful program
To write a beautiful program, breakdown solution to small pieces. This is called modular programming. Think of lego blocks which allow you to create whatever you imagine by interchanging lego blocks. Same is true with programming. Scratch also allows modular programming using functions.

### Practice:

#### 1. Even or Odd
Write a scratch program to accept a number and check if the number is even or odd.

#### Instructions:
- A number is even if a number is divisible by 2. In other words, a number is a even number if the remainder is zero after the number is divided by 2. Scratch provides "mod" operator for the remainder calculation.

<br /><br />

#### Example 1:

![Even or Odd](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11114013/scratch_even_or_odd.png)

#### Example 2:
![Even or Odd](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11114241/scratch_even_or_odd2.png)

<br /><br />
<br /><br />
<br /><br />

#### 2. Scratch program to check leap year
Every year that is exactly divisible by four is a leap year, except for years that are exactly divisible by 100, but these centurial years are leap years if they are exactly divisible by 400. For example, the years 1700, 1800, and 1900 were not leap years, but the years 1600 and 2000 were.

Write a scratch program to check if a given year is a leap year.

#### Instructions:
1. Using a pencil and paper, write down several examples such as 400, 1700, 1800, 1900, 1600, 2000 and 2004.
2. Write down the logic with a pencil and paper before starting to write code.
3. Test if the logic is correct.
4. Once logic is complete, start to write down beautiful code that means code should be modular, simple and optimized.

<br /><br />

#### Example:

##### Pseudocode (Using pencil and paper):
```
If num % 400 == 0
  Leap
Else If num % 100 == 0
  NoLeap
Else If num % 4 == 0
  Leap
Else
  No Leap
```

##### Scratch Code
![Leap Year](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11114312/scratch_leapyear.png)

---

# Week 2
### Review of the homework for Week 1(FizzBuzz)
Nice job for solving the homework. There are many different ways to solve this problem. Here are three examples each of which uses different techniques:

##### Example 1 - Using If...Else...
This is a pretty general way for solving the fizzbuzz problem.
![Using If Else](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115402/scratch_fizzbuzz.png)

* * *

##### Example 2 - Using String
Instead of handling the case for "15 (3 and 5)", this uses a string to join "fizz" and "buzz" when necessary.
![Using String](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115440/scratch_fizzbuzz_string.png)

* * *

##### Example 3 - Using Recursion
Instead of using loop, this example uses a technique called recursion.
![Using Recursion](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115507/scratch_fizzbuzz_recursion.png)


* * *
### Pseudocode
Pseudo means _fake_. [Pseudocode](https://en.wikipedia.org/wiki/Pseudocode) is not a real code, but a human readable description of a computer program. Let's look at real examples:

Example 1 - Scratch Programming - Say "Hello"
```
Say "Hello!"
```
![Hello](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115537/scratch_hello.png)
<br /><br />
Example 2 - Scratch Programming - Even or Odd
```
EvenOrOdd(num)
  if num % 2 = 0
    Say "Even"
  else
    Say "Odd"
```
![Even or Odd](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11114013/scratch_even_or_odd.png)

Isn't it fairly easy to understand? As long as you or your friend understands how to read your pseudocode, your pseudocode is doing its job. There is no standard for pseudocode syntax. Why do you need to know how to write pseudocode?

First of all, pseudocode will help you get warmed up with the upcoming python class and c++ languages. You will later find that python looks surprisingly similar to pseudocode.

Last but not least, it is a good practice to solve a problem with pencil and paper before writing program because writing program is much more time consuming than writing on a paper. By writing pseudocode, you can draw the logic of your program quickly on paper without needing to worry about the details of actual program.

Here are some examples of pseudocode:


### String Processing
A string is a series of characters that is treated as a single unit.

#### Practice

##### 1. Spell out each character from a given string.

Pseudocode
```
  for pos = 1 to str.length
    Say str[pos]
```
![Each char](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115721/scratch_str1.png)
* * *

##### 2. Spell out each character backward from a given string.

Pseudocode
```
  for pos = str.length downto 1
    Say str[pos]
```
![Each char](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115754/scratch_str2.png)
* * *

##### 3. Create a reversed string from a given string, and say the reversed string.

Pseudocode
```
  str2 = ''
  for pos = str.length downto 1
    str2 = str2 + str[pos]
  Say str2
```
![Each char](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11115822/scratch_str3.png)
* * *
##### 4. Create a new Scratch project, and write your own Vowel-couting program using Figure 8-2. Vowel-counting program in the text book.

Pseudocode
```
  CountVowels(str)
    cnt = 0
    for pos 1 to str.length
      c = str[i].toUpper
      if c = 'A' or c = 'E' or c = 'I' or c = 'O' or c = 'U'
        cnt = cnt + 1
    Say cnt
```
* * *

##### 5. Create a new Scratch project, and write your own palindrome program using Figure 8-4.

Pseudocode
```
  IsPalindrome(str)
    for pos 1 to str.length/2
      if str[pos] != str[str.length + 1 - pos]
        Say "No"
        break
    Say "Yes"
```
