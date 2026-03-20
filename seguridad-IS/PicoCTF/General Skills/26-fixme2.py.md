
# Reto 
### fixme2.py
## Descripcion
Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/4/fixme2.py)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/4/fixme2.py
--2026-03-04 03:34:10--  https://artifacts.picoctf.net/c/4/fixme2.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.33, 3.170.131.18, 3.170.131.77, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.33|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1029 (1.0K) [application/octet-stream]
Saving to: 'fixme2.py'

fixme2.py             100%[=======================>]   1.00K  --.-KB/s    in 0s      

2026-03-04 03:34:10 (319 MB/s) - 'fixme2.py' saved [1029/1029]

Aaxel0583-picoctf@webshell:~$ nano fixme2.py
Aaxel0583-picoctf@webshell:~$ python3 fixme2.py
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}
Aaxel0583-picoctf@webshell:~$ 

```



