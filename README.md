#include <stdio.h>

int main()
{
    int num[5];
    printf(" enter the values of 5 numbers:");
    for(int i=0;i<5;i++){
        scanf("%d",&num[i]);
    }
    printf("the numbers you are entered:");
    for(int i=0;i<5;i++){
        printf("%d \n",num[i]);
    } 
    printf("%d \n",num[2]);
    return 0;
}
