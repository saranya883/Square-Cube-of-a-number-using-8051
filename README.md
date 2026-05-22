# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```

MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END
 ```
## OUTPUT
<img width="579" height="444" alt="image" src="https://github.com/user-attachments/assets/a92468b6-89d0-4ef8-9e8a-b2045ab38a9f" />

<img width="671" height="407" alt="image" src="https://github.com/user-attachments/assets/d824e76b-283a-495a-8448-be803b90fb36" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```

MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END

 
```


## OUTPUT
<img width="542" height="405" alt="image" src="https://github.com/user-attachments/assets/454e2a1f-832e-4e3b-a8a5-734c35eff888" />
<img width="537" height="388" alt="image" src="https://github.com/user-attachments/assets/bdc3595f-309e-4fe2-b699-5b4dfcb3fe54" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


