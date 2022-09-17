# strings it
General Skills, 100 Points
## Description
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings) without running it?
## Solution
I used 
>touch output.txt

>strings strings > output.txt

To save all the output in a file to do search in the file for "pico" to save time
>grep "pico" output.txt

this will give you the flag

Flag: picoCTF{5tRIng5_1T_827aee91}
