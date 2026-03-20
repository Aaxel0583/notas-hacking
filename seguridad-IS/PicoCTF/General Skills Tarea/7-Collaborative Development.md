
# Reto 
### Collaborative Development
## Descripcion
My team has been working very hard on new features for our flag printing program! I wonder how they'll work together?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/71/challenge.zip)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ cd drop-in/
Aaxel0583-picoctf@webshell:~/drop-in$ git branch -a
Aaxel0583-picoctf@webshell:~/drop-in$ git checkout feature/part-1
Switched to branch 'feature/part-1'
Aaxel0583-picoctf@webshell:~/drop-in$ cat flag.py
print("Printing the flag...")
print("picoCTF{t3@mw0rk_", end='')Aaxel0583-picoctf@webshell:~/drop-in$ git checkout feature/part-2
Switched to branch 'feature/part-2'
Aaxel0583-picoctf@webshell:~/drop-in$ cat flag.py
print("Printing the flag...")

print("m@k3s_th3_dr3@m_", end='')Aaxel0583-picoctf@webshell:~/drop-in$ git checkout feature/part-3
Switched to branch 'feature/part-3'
Aaxel0583-picoctf@webshell:~/drop-in$ cat flag.py
print("Printing the flag...")

print("w0rk_4c24302f}")
```
}

