
# Reto 
### ### convertme.py
## Descripcion
Run the Python script and convert the given number from decimal to binary to get the flag.[Download Python script](https://artifacts.picoctf.net/c/24/convertme.py)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/24/convertme.py
--2026-03-04 03:23:11--  https://artifacts.picoctf.net/c/24/convertme.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.72, 3.170.131.77, 3.170.131.33, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.72|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1189 (1.2K) [application/octet-stream]
Saving to: 'convertme.py.1'

convertme.py.1        100%[=======================>]   1.16K  --.-KB/s    in 0s      

2026-03-04 03:23:11 (29.3 MB/s) - 'convertme.py.1' saved [1189/1189]

Aaxel0583-picoctf@webshell:~$ python3 convertme.py
If 75 is in decimal base, what is it in binary base?
Answer: 00110111 00110101
That isn't a binary number. Binary numbers contain only 1's and 0's
Aaxel0583-picoctf@webshell:~$ python3 convertme.py
If 94 is in decimal base, what is it in binary base?
Answer: 1011110
That is correct! Here's your flag: picoCTF{4ll_y0ur_b4535_722f6b39}
Aaxel0583-picoctf@webshell:~$ 
```

## Notas adicionales 
https://gchq.github.io/CyberChef/#recipe=To_Binary('Space',8)&input=NzU


