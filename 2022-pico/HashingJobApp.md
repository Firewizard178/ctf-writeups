# HashingJobApp
General Skills, 100 Points
## Description
If you want to hash with the best, beat this test! 

`nc saturn.picoctf.net 63116`
## Solution 
You need to connect to the port with netcat and complete a series of requests to convert the strings to hash using md5

You I used [this](https://www.md5hashgenerator.com/) tool

```firewizard@firewizard-VirtualBox:~$ nc saturn.picoctf.net 63116

Please md5 hash the text between quotes, excluding the quotes: 'computer hackers'

Answer: 

1034abc8025edcc22f58c35abc21e36f

1034abc8025edcc22f58c35abc21e36f

Correct.

Please md5 hash the text between quotes, excluding the quotes: 'hair transplants'

Answer: 

5b416c0db26c7e0478766fc51931a3ab

5b416c0db26c7e0478766fc51931a3ab

Correct.

Please md5 hash the text between quotes, excluding the quotes: 'Cindy Crawford'

Answer: 

2ee8ebf845baa7f500e153417cf691fd

2ee8ebf845baa7f500e153417cf691fd

Correct.

picoCTF{4ppl1c4710n_r3c31v3d_bf2ceb02}
```

Flag: picoCTF{4ppl1c4710n_r3c31v3d_bf2ceb02}


