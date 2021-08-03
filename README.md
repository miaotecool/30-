# 30-
//计算n的阶层
int main（）
{
    int i = 0;
    int n = 0;
    int ret = 1;
    scanf("%d", %n);
    for(i=1; i<=n; i++)
    {
       ret = ret * i;
    }
    printf("ret=d\n", ret);
    return 0;
}
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
//找一组序列中的一个数
//方法一
int main ()
{
   int arr[] = {1、2、3、4、5、6、7、8、9、10}；
   int k = ;
   int i = 0;
   int sz =sizeof(arr)/sizeof(arr[0]);
   for (i=0; i<sz; i++)
   {
      if(k == arr[i])
      {
         printf("找到了，下标是：%d\n", i);
         break;
      }
   }
   if(i == sz)
     printf(“找不到\n”)
   return 0;
}
//方法二（）二分查找法；折半查找法
int main()
{
   int arr[] ={1、2、3、4、5、6、7、8、9、10}；
   int k = ;
   int sz = sizerof(arr)/sizerof(arr[0]);
   int left = 0;
   int right = 0;
   while(left <= right)
   {
      int mid =(left+right)/2;
      if (arr[mid] > k)
      {
         right =mid - 1;
      }
      else if(arr[mid] < k)
      {
        left = mid + 1;
      }
      else
      {
        printf("找到了，下标是：%d\n", mid);
        break;
      }
   }
   if (left > right)
     printf("找不到\n")；
   return 0;
}
//
#include<stdio.h>
#include<strlen.h>
#include<stdlib.h>
#include<widows.h>
int main（）
{
    char arr1[] = "welcome to bit!!!!!!";
    char arr2[] = "####################";
    int left = 0;
    int right = strlen(arr1)-1;
    while(left<=right)
    {
        arr2[right] = arr1[right];
        arr2[left] = arr1[left];
        printf("%s\n", arr2);
        (//休息1秒 sleep(1000), system("cls"))
        left++;
        right--;
    }
    printf("%d\n",arr2);
 return 0;
}
