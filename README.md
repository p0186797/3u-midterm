

**For the following programs, leave the prompt in the input function empty and make sure to also strip the input.**

---
Create a python file called **fish.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

You take your daughter to the pond to see the fish. When she sees a single fish, she shouts "One fish!", when she sees two together she shouts "Two fish!, when she sees a red one she shouts "Red fish!", and a blue one, "Blue Fish!". If there are no fish in the pond, she shouts "No fish!"

Given a string of fish spotted in the pond (1 for one fish, 2 for two fish, r for red fish, b for blue fish, and 0 for no fish), predict the series of exclamations you'd expect to hear from your daughter. *Make sure to validate the input.*

### Input Specification

One string consisting of a series of characters: 1, 2, r, b, 0. 0 would only occur by itself. Each character represents a type of fish. 

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

Write a program that takes in three inputs. The first two inputs represent the x and y values of a coordinate. The third input is a string consisting of a series of characters L, R, D, U. L represents move left 1 unit. R represents move right 1 unit. D represents move down 1 unit. U represents move up 1 unit. Your program should output the final coordinate after the initial coordinate is translated the directions given. *You do not need to validate input.*

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

Create a python file called **secret.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

You are your friend share a locker which uses a directional lock. The directional lock has 4 directions: N, S, E, W. You forgot the combination so your friend leaves coded instructions for you.

Each instruction is a sequence of 5 digit numbers which represents one direction.

If the sequence of numbers sums to 0 to 10 inclusive, move the lock to N.

If the sequence of numbers sums to 11 to 20 inclusive, move the lock to S.

If the sequence of numbers sums to 21 to 30 incluside, move the lock to E.

If the sequence of numbers sums to 31 to 40 inclusive, move the lock to W.

If the sequence of numbers sums to 41 to 45 incluside, then this is the last line and there are no more directions.

Write a program that reads a series of 5 digit coded directions and outputs the directions for the directional lock. *You do not need to validate input.*

### Input Specification

There will be at least two lines of input. Each line except the last line will contain exactly five digits representing an instruction. The last line will contain a 5 digit number whose digits sum to 41 to 45 inclusive. No other line will sum to 41 to 45 inclusive.


### Output Specification

A string of characters containing N, S, W, E.

&nbsp;&nbsp; **Sample Input 1**

    12345
    02849
    48697
    87395
    99999

&nbsp;&nbsp; **Sample Output 1**

    SEWW

&nbsp;&nbsp; **Sample Input 2**

    42393
    21332
    01002
    98799

&nbsp;&nbsp; **Sample Output 2**

    ESN
    
