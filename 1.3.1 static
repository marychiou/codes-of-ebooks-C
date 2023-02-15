#include <stdio.h>

static int j;

void fun1()
{
    static int i = 0;
    i ++;
    printf("i: %d\n",i);
}
void fun2()
{
    j = 0;
    j++;
}
int main()
{
    for(int k=0; k<10; k++)
    {
        fun1();
        fun2();
    }
    // printf("%d",i);  //'i' undeclared
    printf("j: %d\n",j);
    return 0;
}
