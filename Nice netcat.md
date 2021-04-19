# Nice netcat...

## Description

There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 7449, but it doesn't speak English...


## Solution
typed above command in a shell and the numbers come out. After searching the number, it found that the number is decimal and needed to convert to text.
I used cryptii to decode the number as below:
https://v2.cryptii.com/decimal/text


## Flag

picoCTF{g00d_k1tty!_n1c3_k1tty!_f2d7cafa}

