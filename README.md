# EX-NO-6-Pseudo-Random-Number
## NAME : KARTHICK KISHORE T
## REG NO : 212223220042
## DATE : 

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random

random.seed(10) 
random_float = random.random()
random_integer = random.randint(1, 100)
random_list = [random.randint(10, 50) for _ in range(5)]

print("Pseudo-random float (0 to 1):", random_float)
print("Pseudo-random integer (1 to 100):", random_integer)
print("List of 5 pseudo-random integers (10 to 50):", random_list)

```
# OUTPUT:
![cryp 6](https://github.com/user-attachments/assets/139e001a-c0e6-4d8e-9318-179b057fe85e)

# RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.
