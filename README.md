# EX-11-EMI-CALCULATOR

## AIM

To write a program to prepare EMI calculator using function without return type and with arguments.

## ALGORITHM

1.	Start the program.
2.	Read principal amount, rate of interest and months.
3.	Pass these values as arguments to function.
4.	Calculate EMI using the formula, amt=(prpow(1+r,t))/(pow(1+r,t)-1)
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include<math.h>
int main(){
    float p,r,t,emi;
    scanf("%f%f%f",&p,&r,&t);
    r=r/(12*100);
    t=t*12;
    emi=(p*r*pow(1+r,t))/(pow(1+r,t)-1);
    printf("Monthly EMI is= %.3f",emi);
    return 0;
}

```

## OUTPUT
![image](https://github.com/user-attachments/assets/12ada506-4785-4127-9909-d8d797587548)





## RESULT

Thus the program to prepare EMI calculator using function without return type with arguments has been executed successfully
 
 


# EX-12-PRIME-NUMBER
## AIM
To Count Number of Prime Numbers in a Given Range.

## ALGORITHM
1. Start.
2. Input two integers, start and end, representing the range of numbers to check.
3. Initialize count to 0 to keep track of prime numbers.
4. Loop through each number i from start to end
5. Call the isPrime(i) function to check if i is a prime number.
6. If i is prime, increment the count.
7. Print the value of count (the number of primes found) with the given range.
8. End.



## PROGRAM
```
#include<stdio.h>
int isPrime(int n){
    if(n<2)return 0;
    for (int i=2;i*i<=n;i++)
    if(n%i==0)return 0;
    return 1;
}
int main(){
    int start,end,count=0;
    scanf("%d%d",&start,&end);
    for(int i=start;i<=end;i++)
    if(isPrime(i))count++;
    printf("Number of Prime numbers between 5 and 19 are: %d\n",count);
    return 0;
}
```
## OUTPUT

![image](https://github.com/user-attachments/assets/f337676d-9465-415d-a4a0-b11fbd2cb1bf)





## RESULT
Thus the program  to Count Number of Prime Numbers in a Given Range has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY
## AIM
To read n elements as input and print the second element of the array (integer).

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	Print the second element.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main()
{
    int n;
    scanf("%d",&n);
    int a[n];
    for(int i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
}
        printf("%d ",a[1]);

    return 0;
}
```
## OUTPUT

![image](https://github.com/user-attachments/assets/cd70d1d4-f69b-4507-9a60-3238a8010012)








## RESULT
Thus the program to read n elements as input and print the second element of the array has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS
## AIM
To search an element in an array .

## ALGORITHM
1. Start.
2. Input the integer n, which is the size of the array.
3. Input the n elements into the array a[].
4. Initialize the number b = 5 .
5. Loop through each element in the array.
6. If an element is equal to 5, print its position.
7. End.

## PROGRAM
```
#include<stdio.h>
int main(){
    int n;
    scanf("%d",&n);
    int a[n];
    for(int i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    int b=5;
     for(int i=0;i<n;i++){
         if(a[i]==b){
             printf("%d is found at position %d",b,i+1);
         }
     }
     return 0;
}
```
## OUTPUT

![image](https://github.com/user-attachments/assets/25627b1c-3a99-481c-95a7-44588e07f106)




## RESULT
Thus the program to search an element in an array  has been executed successfully.





 
 


# EX -15 - READ AND PRINT ELEMENTS IN THE ARRAY

## Aim:
to read n elements as input and print the elements of the array

## Algorithm:
1. Start.
2. Input the integer a (size of the array).
3. Input a integers into the array arr[].
4. Output the elements of the array, one by one.

## Program:
```
#include<stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    int arr[a];
    for(int i=0;i<a;i++){
        scanf("%d",&arr[i]);
    }
    for(int i=0;i<a;i++){
        printf("%d ",arr[i]);
    }
}
    

```
## Output:
 


## Result:

Thus, the program to read n elements as input and print the elements of the array was verified successfully.



