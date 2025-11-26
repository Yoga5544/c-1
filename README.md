# c-1
swapping program
#include <stdio.h>
int main(){
    int num1,num2;
    printf(" Enter an number :");
    scanf("%d",&num1);
    printf(" Eter an number 2 :");
    scanf("%d",&num2);
    printf(" Before swapping num 1 = %d, num 2 = %d \n",num1,num2);
    num1=num1+num2;
    num2=num1-num2;
    num1=num1-num2;
    printf("After swapping  num1 = %d, num2 = %d \n",num1,num2);
    return 0;
    }
