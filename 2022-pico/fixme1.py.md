# fixme1.py
General Skills, 100 Points
## Description
Fix the syntax error in this Python script to print the flag. 

[Download Python script](https://artifacts.picoctf.net/c/38/fixme1.py)
## Solution
The first error is an indentation error in line 20 

Fix this by going back 2 spaces in the before the print() function

To fix the other errors you remove the `\` and change the `''` to `""` at the start and end 

the line should look like this 
>print("That is correct! Here's your flag: " + flag)

then run the script and it should output
>That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}

Flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}
