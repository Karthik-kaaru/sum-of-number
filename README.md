# sum-of-number
To find sum of n natural number
#include <stdio.h>
int sum(int num);
int main() 
{
 int n;
  printf("Enter the no\n");
  scanf("%d",&n);
  printf ("the sum of the %d = %d",n,sum(n));
    return 0;
}
 int sum(int num)
 { 
  int a=0;
     for(int i=num;i>0;i--)
      a=a+i;
  return a;
}
