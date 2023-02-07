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
//这也是我的第一个github的代码


//汉诺塔问题
//对于这个问题,我们假设有n个盘子在A上,于是我们先从A拿出n-1个放到B上面,再把A里面最大的盘子放到C中,再从B中拿出n-2个放到A中,再从B中拿出一个到C中......此时A上面有n-2个盘子,B上面有0个盘子,c上面有2个盘子......于是这个问题巧妙地解决了.
#include<stdio.h>
void hanoi(int n,char a,char b,char c);
int main()
{
int n;
int m=hanoi(n,a,b.c);
scanf("%d",&n);
printf("%d",m);
hanoi(n,'a','b','c');
return 0;
}
hanoi(int n,char a,char b,char c)
{
if(n==1)
{
printf("%c->%c",a,c);
}else{
hanoi(A,n-1,B);
hanoi(A,1,C);
hanoi(B,n-2,A);
hanoi(B,1,C);
//以下是书上的算法和代码
hanoi(n-1,a,c,b);
printf("%c->%c",a,b);
hanoi(n-1,c,b,a);
}
}







