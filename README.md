//c语言
//第一门变编程语言
//递归台阶问题
#include<stdio.h>
int all always(int  n);
int main(void)
{
int n;
scanf("%d",&n);
int m=all always(n);
printf("%d",m);
return 0;
}
int all always(int n)
{
if(n==1||n==2)
return n;
else
return all always(n-1)+all always(n-2);
}
//这也是我的第一个githubd的代码
