# Game--A--Thon INTRODUCTION TO GIT AND GITHUB
# Name: Samruddhi Uplapwar
# problem Statement 1:Program to Add Two Integers.
TestCase 1: input :11,12 output: 23
  
  #include <stdio.h>
int main() {    

    int number1, number2, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &number1, &number2);

    // calculating sum
    sum = number1 + number2;      
    
    printf("%d + %d = %d", number1, number2, sum);
    return 0;
}


# problem Statement 1:Find the Largest of Two Numbers.
TestCase 1: input :10,40 output: 40
#include <stdio.h>  
   
int main() {  
    int a, b;  
    printf("Please Enter Two different values\n");  
    scanf("%d %d", &a, &b);  
    
    if(a > b) 
    {
        printf("%d is Largest\n", a);          
    } 
    else if (b > a)
    { 
        printf("%d is Largest\n", b);  
    } 
    else 
    {
	printf("Both are Equal\n");
    }
   
    return 0;  
}
