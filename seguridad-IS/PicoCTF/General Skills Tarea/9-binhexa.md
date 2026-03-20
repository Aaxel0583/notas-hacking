
# Reto 
### binhexa
## Descripcion
How well can you perfom basic binary operations?Start searching for the flag here `nc titan.picoctf.net 64049`
## Solucion
```
Aaxel0583-picoctf@webshell:~$ nc titan.picoctf.net 60204

Welcome to the Binary Challenge!"
Your task is to perform the unique operations in the given order and find the final result in hexadecimal that yields the flag.

Binary Number 1: 10001101
Binary Number 2: 00011110


Question 1/6:
Operation 1: '>>'
Perform a right shift of Binary Number 2 by 1 bits .
Enter the binary result: 010101011
Incorrect. Try again
Enter the binary result: 00001111            
Correct!

Question 2/6:
Operation 2: '*'
Perform the operation on Binary Number 1&2.
Enter the binary result: 01000010000110
Correct!

Question 3/6:
Operation 3: '+'
Perform the operation on Binary Number 1&2.
Enter the binary result: 010101011
Correct!

Question 4/6:
Operation 4: '<<'
Perform a left shift of Binary Number 1 by 1 bits.
Enter the binary result: 0001 1010

Incorrect input. Provide the right input
Enter the binary result: 100011010
Correct!

Question 5/6:
Operation 5: '&'
Perform the operation on Binary Number 1&2.
Enter the binary result: 00001100           
Correct!

Question 6/6:
Operation 6: '|'
Perform the operation on Binary Number 1&2.
Enter the binary result: 10011111
Correct!

Enter the results of the last operation in hexadecimal: 9f

Correct answer!
The flag is: picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_d9a7ddd2}
```


## Referencias

https://www.calculator.net/binary-calculator.html?number1=10001101&c2op=%2B&number2=00011110&calctype=op&x=Calculate
