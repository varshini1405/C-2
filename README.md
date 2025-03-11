# C-2
max and min
#include <stdio.h>
#include<stdlib.h>
int main()
{
    int a=22,b=4;
    printf("Max=%d\n",((a+b)+abs(a-b))/2);
    printf("Min=%d\n",((a+b)-abs(a-b))/2);
    return 0;
}
