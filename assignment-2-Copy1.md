1.What are the two values of the Boolean data type? How do you write them?

ans.There are two boolean values:True and False.

2. What are the three different types of Boolean operators?

ans.The three boolean operators are :AND , OR and NOT.

3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean
values for the operator and what it evaluate ).

ans.condition 1  condition 2  NOT X     X AND Y     X OR Y  
     eg : X       eg : Y       (~X)
     false        false       true       false      false
     false        true        true       false      true
     true         false       false      false      true
     true         true        false      true       true

4. What are the values of the following expressions?
(5 > 4) and (3 == 5)
not (5 > 4)
(5 > 4) or (3 == 5)
not ((5 > 4) or (3 == 5))
(True and True) and (True == False)
(not False) or (not True)

ans.False
    False
    True
    False
    False
    True

5. What are the six comparison operators?

ans.Six comparison operators: less than ( < ),less than or equal to ( <= ),greater than ( > ),greater than or equal to ( >= ), equal to ( == ),and not equal to ( != ).

6. How do you tell the difference between the equal to and assignment operators?Describe a
condition and when you would use one.

ans.The “=” is an assignment operator is used to assign the value on the right to the variable on the left.
The '==' operator checks whether the two given operands are equal or not. If so, it returns true. Otherwise it returns false.

7. Identify the three blocks in this code:



```python
spam = 0
if spam == 10:
    print("eggs")
    if spam > 5:
        print("bacon")
else:
    print("spam")
    print("spam")
    print("spam")
```

    spam
    spam
    spam
    

8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints
Greetings! if anything else is stored in spam.


```python
spam=int(input())
if spam==1:
    print("Hello")
elif spam==2:
    print("Howdy")
else:
    print("Greeting!")
```

    2
    Howdy
    

9.If your programme is stuck in an endless loop, what keys you’ll press?

ans.ctrl+c

10. How can you tell the difference between break and continue?

ans.Break Statement : The break statement is usually used with the switch statement, and it can also use it within the while loop, do-while loop, or the for-loop.
Continue Statement : The continue statement is not used with the switch statement, but it can be used within the while loop, do-while loop, or for-loop.

11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?

ans.In for loop there is no difference between range(10),range(0,10) and range(0,10,1) they all give same output as :
0
1
2
3
4
5
6
7
8
9

12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent
program that prints the numbers 1 to 10 using a while loop.


```python
for i in range(1,11):
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
i = 1
while(i<=10):
    print(i)
    i += 1
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    

13. If you had a function named bacon() inside a module named spam, how would you call it after
importing spam?


```python
This function can be called with spam. bacon().

```
