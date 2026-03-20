# Reto 
### Big Zip
## Descripcion
Unzip this archive and find the flag.

- [Download zip file](https://artifacts.picoctf.net/c/504/big-zip-files.zip)
## Solucion
Aaxel0583-picoctf@webshell:~$  grep -r pico
.bash_history:wget https://challenge-files.picoctf.net/c_fickle_tempest/2e9bfa4e1d90ac25a999fefdfb4feb8a2ff4eb73e4c61af4889a3762687ada01/file
.bash_history:cat file | grep picoctf
.bash_history:cat file | grep picoCTF
.bash_history:nc fickle-tempest.picoctf.net 57446
.bash_history:nc fickle-tempest.picoctf.net 57446 | grep picoCTF
.bash_history:wget https://artifacts.picoctf.net/c/476/enc_flag
big-zip-files/folder_pmbymkjcya/folder_cawigcwvgv/folder_ltdayfmktr/folder_fnpfclfyee/whzxrpivpqld.txt:information on the record will last a billion years. Genes and brains and books encode picoCTF{gr3p_15_m4g1c_ef8790dc}
Aaxel0583-picoctf@webshell:~$ 
