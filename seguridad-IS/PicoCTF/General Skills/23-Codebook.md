
# Reto 
### - Codebook
## Descripcion
Run the Python script `code.py` in the same directory as `codebook.txt`.

- [Download code.py](https://artifacts.picoctf.net/c/2/code.py)
- [Download codebook.txt](https://artifacts.picoctf.net/c/2/codebook.txt)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/2/codebook.txt
--2026-03-04 03:18:05--  https://artifacts.picoctf.net/c/2/codebook.txt
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.77, 3.170.131.18, 3.170.131.72, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.77|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 27 [application/octet-stream]
Saving to: 'codebook.txt'

codebook.txt          100%[=======================>]      27  --.-KB/s    in 0s      

2026-03-04 03:18:06 (11.8 MB/s) - 'codebook.txt' saved [27/27]

Aaxel0583-picoctf@webshell:~$ ls
README.txt     big-zip-files.zip  codebook.txt  files.zip
big-zip-files  code.py            files         runme.py
Aaxel0583-picoctf@webshell:~$ python3 code.py
picoCTF{c0d3b00k_455157_7d102d7a}
Aaxel0583-picoctf@webshell:~$ 
```


