#include<stdio.h>
int main()
{
    int a=10;
    int *ptr=&a;
    printf("value of a : %d \n",a);
    printf("address of a : %p \n",&a);
    printf("Pointer stores the address of a : %p \n",ptr);
    printf("Value stored at the pointer of a : %d \n",ptr);
    printf("address of a : %d \n",&a);
    return 0;
}
