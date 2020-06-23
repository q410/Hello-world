# Hello-world
Now it maybe plain , but it will be better
//动态申请一个数组内存
#include<stdio.h>
#include<stdlib.h>
int main()
{
int *a;
int number;
printf("input number");
scanf("%d",&number);
a=(int*)malloc(number*sizeof(int));
return 0;
}
