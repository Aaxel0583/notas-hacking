
# Reto 
### PW Crack 2
## Descripcion
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/15/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/15/level2.flag.txt.enc) in the same directory too.
## Solucion
```
Aaxel0583-picoctf@webshell:~$ grep "if( user_pw ==" level2.py
    if( user_pw == chr(0x33) + chr(0x39) + chr(0x63) + chr(0x65) ):
Aaxel0583-picoctf@webshell:~$ python3 -c chr(0x33) + chr(0x39) + chr(0x63) + chr(0x65)
-bash: syntax error near unexpected token `('
Aaxel0583-picoctf@webshell:~$ python3 -c "print(chr(0x33) + chr(0x39) + chr(0x63) + ch
r(0x65))"
39ce
Aaxel0583-picoctf@webshell:~$ python3 level2.py
Please enter correct password for flag: 39ce
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_502ec42e}
Aaxel0583-picoctf@webshell:~$ 
```



