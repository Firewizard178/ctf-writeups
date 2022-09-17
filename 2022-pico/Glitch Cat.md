# Glitch Cat
General Skills, 100 Points
## Description
Our flag printing service has started glitching! 
>$ nc saturn.picoctf.net 53933
# Solution
Connect to the port using netcat 
>nc saturn.picoctf.net 53933

this outputs 
>'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'

then in a new python file write 
>print('picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}')

Flag: picoCTF{gl17ch_m3_n07_a4392d2e}

