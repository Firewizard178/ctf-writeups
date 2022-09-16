# Nice netcat...
General Skills, 15 Points
## Description
There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 7449, but it doesn't speak English...
## Solutions
Connect to the port with netcat using 
>nc mercury.picoctf.net 7449


Then this ASCII Code is outputted 

112 105 99 111 67 84 70 123 103 48 48 100 95 107 49 116 116 121 33 95 110 49 99 51 95 107 49 116 116 121 33 95 102 50 100 55 99 97 102 97 125 10 

Using [this](https://www.duplichecker.com/ascii-to-text.php) translator is got the flag

Flag: picoCTF{g00d_k1tty!_n1c3_k1tty!_f2d7cafa}
