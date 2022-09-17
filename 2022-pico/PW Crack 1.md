# PW Crack 1
General Skills, 100 Points
## Description
Can you crack the password to get the flag? 

Download the password checker [here](https://artifacts.picoctf.net/c/51/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/51/level1.flag.txt.enc) in the same directory too.
## Solution
Download both files 

If you inspect the python files code you will see `user_pw == "619d"`

When you run the python file input the password `619d` and if both files are in the same location you will get the flag

Flag: picoCTF{545h_r1ng1ng_56891419}
