# Magikarp Ground Mission
General Skills, 30 Points
## Description
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `ee388b88`
## Solution
Start the instance 

connect to it with 
>ssh user@machine -p port

Then use `ls` and `cat` the first file which will give use `picoCTF{xxsh_`
The second file directs you to the directory `/`
>cd /

Then read the 2nd file which will give you `0ut_0f_\/\/4t3r_`

Reading the instruction txt file will direct you to `~` directory 
>cd 

Then read the 3rd file which will give you `3ca613a1}`

Flag: picoCTF{xxsh_0ut_0f_\/\/4t3r_3ca613a1}
