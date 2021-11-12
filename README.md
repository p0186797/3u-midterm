# 3u-midterm

Optional Midterm
---

**For the following programs, leave the prompt in the input function empty.**

---
Create a python file called **fish.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

You take your daughter to the pond to see the fish. When she sees a single fish, she shouts "One fish!", when she sees two together she shouts "Two fish!, when she sees a red one she shouts "Red fish!", and a blue one, "Blue Fish!". If there are no fish in the pond, she shouts "No fish!"

Given a string of fish spotted in the pond (1 for one fish, 2 for two fish, r for red fish, b for blue fish, and 0 for no fish), predict the series of exclamations you'd expect to hear from your daughter.

### Input Specification

One string consisting of a series of characters: 1, 2, r, b, 0. Each character represents a type of fish.

### Output Specification

One string with all exclamations made in response to the fish spotted.

&nbsp;&nbsp; **Sample Input 1**

    12rb

&nbsp;&nbsp; **Sample Output 1**

    One fish! Two fish! Red fish! Blue fish!

&nbsp;&nbsp; **Sample Input 2**

    0

&nbsp;&nbsp; **Sample Output 2**

    No fish!

&nbsp;&nbsp; **Sample Input 3**

    rb22b1

&nbsp;&nbsp; **Sample Output 3**

    Red fish! Blue fish! Two fish! Two fish! Blue fish! One fish!
    
---

Create a python file called **directions.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that takes in three inputs. The first two inputs represent the x and y values of a coordinate. The third input is a string consisting of a series of characters L, R, D, U. L represents move left 1 unit. R represents move right 1 unit. D represents move down 1 unit. U represents move up 1 unit. Your program should output the final coordinate after the initial coordinate is translated the directions given.

### Input Specification

Three inputs. The first input is an integer that represents the x-value of the initial coordinate. The second input is an integer that represents the y-value of the initial coordinate. The third input is a string consisting of a series of characters: L, R, U, D. 

### Output Specification

Two outputs. The first output is the x-value of the final coordinate. The second output is the y-value of the final coordinate.

&nbsp;&nbsp; **Sample Input 1**

    4
    -3
    LRUDLLRUDU

&nbsp;&nbsp; **Sample Output 1**

    3
    -2

&nbsp;&nbsp; **Sample Input 2**

    -7
    -10
    LUUUUDDDDRRRLRLRLRUD
    
&nbsp;&nbsp; **Sample Output 2**

    -5
    -10
    
---

Create a python file called **lcm.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that reads three positive integers and outputs their lowest common multiple.

### Input Specification

Three inputs - all positive integers.

### Output Specification

One output - an integer.

&nbsp;&nbsp; **Sample Input 1**

    3
    4
    6

&nbsp;&nbsp; **Sample Output 1**

    12

&nbsp;&nbsp; **Sample Input 2**

    2
    9
    6

&nbsp;&nbsp; **Sample Output 2**

    18
    
