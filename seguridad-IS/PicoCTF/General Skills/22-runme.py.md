
# Reto 
### runme.py
## Descripcion
#### Description

Run the `runme.py` script to get the flag. Download the script with your browser or with `wget` in the webshell.[Download runme.py Python script](https://artifacts.picoctf.net/c/34/runme.py)
## Solucion
```
Aaxel0583-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/34/runme.py
--2026-03-04 03:10:14--  https://artifacts.picoctf.net/c/34/runme.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.72, 3.170.131.18, 3.170.131.33, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.72|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 270 [application/octet-stream]
Saving to: 'runme.py'

runme.py              100%[=======================>]     270  --.-KB/s    in 0s      

2026-03-04 03:10:14 (80.1 MB/s) - 'runme.py' saved [270/270]

Aaxel0583-picoctf@webshell:~$ python3 runme.py
picoCTF{run_s4n1ty_run}
Aaxel0583-picoctf@webshell:~$ 
```


