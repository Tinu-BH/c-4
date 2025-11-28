# c-4
Program to subtract 2 numbers
#include <stdio.h>

int main()
{
    int num1, num2, op;
    printf("Enter num1:");
    scanf("%d", &num1);
    printf("Enter num2:");
    scanf("%d", &num2);
    op= num1-num2;
    printf("Difference %d", op);
    return 0;
}
