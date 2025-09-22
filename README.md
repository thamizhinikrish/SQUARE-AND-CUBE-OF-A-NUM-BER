# SQUARE AND CUBE OF A NUMBER
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
ORG 0000H
MOV DPTR,#4500H
MOVX A,@DPTR 
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
## OUTPUT
<img width="611" height="382" alt="image" src="https://github.com/user-attachments/assets/11b780ac-0885-4d22-bb15-61101ed933a5" />
<img width="628" height="306" alt="image" src="https://github.com/user-attachments/assets/a49918d7-c289-48d3-84b6-04b519ded533" />

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
ORG 0000H
MOV DPTR,#4500H
MOVX A,@DPTR 
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
END
## OUTPUT
<img width="548" height="342" alt="image" src="https://github.com/user-attachments/assets/f573e387-04cf-4ac2-b450-a9eca70fd7d8" />
<img width="543" height="326" alt="image" src="https://github.com/user-attachments/assets/c3ae7fa6-eda4-417c-b2e5-db8b4aa46580" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
