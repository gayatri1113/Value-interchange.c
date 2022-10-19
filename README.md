//# Value-interchange.c//
#include<stdio.h>
int main()
{
   double first,second,temp;
   printf("enter first number:");
   scanf("%lf",&first);
   printf("enter second number:");
   scanf("%lf",&second);
   temp=first;
   first=second;
   second=temp;
   printf("After swapping,first number=%2lf\n",first);
   printf("After swapping,secomnd number=%2lf\n",second);
   return 0;
}
