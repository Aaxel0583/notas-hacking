
# Reto 
### blame game
## Descripcion
Someone's commits seems to be preventing the program from working. Who is it?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/158/challenge.zip)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ cd drop-in/
Aaxel0583-picoctf@webshell:~/drop-in$ ls
message.py
Aaxel0583-picoctf@webshell:~/drop-in$ git blame message.py
```

```
8c83358c (picoCTF{@sk_th3_1nt3rn_2c6bf174} 2024-03-12 00:07:11 +0000 1) print("Hello, World!"
```







