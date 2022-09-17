# Static ain't always noise
General Skills, 20 Points
## Description
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/static)? This [BASH script](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/ltdis.sh) might help!
## Solution
Make sure you have binutils installed using 
>sudo apt install binutils

Download both files and use the command 
>chmod u+x static

to execute the file

Then run the script on the static file using
>bash ltdis.sh static 

This will put all of the lines in the file in a text file called static.ltdis.strings.txt

Then use 
>cat static.ltdis.strings.txt

and the flag is in there

Flag: picoCTF{d15a5m_t34s3r_f5aeda17}
