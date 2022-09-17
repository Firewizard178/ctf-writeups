# PW Crack 2
General Skills, 100 Points
## Description
Can you crack the password to get the flag?

Download the password checker [here](https://artifacts.picoctf.net/c/17/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level2.flag.txt.enc) in the same directory too.
## Solution
In the python file you will see `user_pw == chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39)` 

This is ASCII

Using python you can use this code to get the password
>print(chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39))

which is `4ec9`

Then run the original python file and use the password to get the flag

Flag: picoCTF{tr45h_51ng1ng_9701e681}
