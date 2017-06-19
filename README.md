# lab8
Question 1：
-----------
The following program terminates without showing "I love C++." because of the keyword "throw" has two meanings in the program, and one of meaning is "to return". So the program will immediately stoped and get out of the main function. It also mean that the function won't continue complete the instruction "I love C++."


Question 2：
-----------
The following program will show "I love C++." because when the program execute to 

    throw 3.0;

the function will return and find the closest matched keyword "catch" and execute the instruction inside.

When the catch function complete its work, it will get out the parameter and continuously execute the following instruction "I love C++."

How does it compile：
--------------------
    make
    ./Tetris
    
    
