# 30-
if





























//计算1！+2！+3！+.....+10！的阶层
//方法一
include <stdio.h>
int main()
{
    int i = 0;
    int n = 0;
    int ret = 1;
    int sum = 0;
    for(n=1; n<=10; n++)
      {
           ret = 1;
           for(i=1; i<=n; i++)
           {
              ret = ret * i;
           }
           sum = sum + ret; 
      }
   printf("sum = %d\n", sum);
   return0
}
方法二
include <stdio.h>
int main()
{
    int i = 0;
    int n = 0;
    int ret = 1;
    int sum = 0;
    for(n=1; n<=10; n++)
    {
       ret = ret * n;
       sum = sum + ret;
    }
       printf("sum = %d\n", sum);
   return0
}
