# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE:
## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display hardware details such as price, product name and price using structure.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

## Program:
```
/*
C program to display Hardware details such as price, product name and price using structure.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008
*/
```
```
#include<stdio.h> 
struct hardware
{
char qr[10];
char product[10]; 
int price;
}j[10];
int main()
{
int i; 
for(i=0;i<3;i++)
scanf("%s%s%d",j[i].qr,j[i].product,&j[i].price); 
for(i=0;i<3;i++)
printf("QRcode:%s\nproduct:%s\nprice :%d\n",j[i].qr,j[i].product,j[i].price);}
```


## Output:
<img width="1013" height="492" alt="439190048-511eb4f2-6cd2-4774-ae07-7a0ddc859a5d" src="https://github.com/user-attachments/assets/1af5fa5f-f599-4489-a287-7aa52f07a5ab" />



## Result:
Thus the program was executed and the output was verified successfully.
