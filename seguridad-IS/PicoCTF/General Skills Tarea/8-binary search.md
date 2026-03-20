
# Reto 
### binary search
## Descripcion
Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses.Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools!You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_atlas/20/challenge.zip)

`ssh -p 56503 ctf-player@atlas.picoctf.net`Using the password `6abf4a82`. Accept the fingerprint with `yes`, and `ls` once connected to begin. Remember, in a shell, passwords are hidden!
## Solucion

```
Aaxel0583-picoctf@webshell:~$ python3 auto_bsearch.py
[*] Conectando a atlas.picoctf.net:55646...
[+] ¡Conexión exitosa!

Welcome to the Binary Search Game!
I'm thinking of a number between 1 and 1000.
Enter your guess: 
[*] Intento 1: Enviando 500...
Respuesta: 500
Higher! Try again.
Enter your guess:

[*] Intento 2: Enviando 750...
Respuesta: 750
Lower! Try again.
Enter your guess:

[*] Intento 3: Enviando 625...
Respuesta: 625
Higher! Try again.
Enter your guess:

[*] Intento 4: Enviando 687...
Respuesta: 687
Lower! Try again.
Enter your guess:

[*] Intento 5: Enviando 656...
Respuesta: 656
Lower! Try again.
Enter your guess:

[*] Intento 6: Enviando 640...
Respuesta: 640
Higher! Try again.
Enter your guess:

[*] Intento 7: Enviando 648...
Respuesta: 648
Lower! Try again.
Enter your guess:

[*] Intento 8: Enviando 644...
Respuesta: 644
Lower! Try again.
Enter your guess:

[*] Intento 9: Enviando 642...
Respuesta: 642
Congratulations! You guessed the correct number: 642
Here's your flag: picoCTF{g00d_gu355_bee04a2a}


[🏆] ¡BANDERA ENCONTRADA!
```
## Notas adicionales 
se uso codigo python para automatizar, codigo encontrado en la red
## Referencias
https://andrejtopalov.medium.com/ctf-challenge-writeup-picoctf-binary-search-2b2706dc9d5d

