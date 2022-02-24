# simple-calculation
simple calculation
by James Kalyonge
feb 2022
MIT license
c89 compiler
*/
#include <stdio.h>
#iclude <stdlib.h>
#include <stdlib.h>
int main()
{
      //variable Declaration
      int num1,num2,sum,diff,product;
      float quotient;
      printf("simple calculator!\n");
      //capture  inputs
      printf("Enter two values: ");
      scanf("%d%d",&num1, &num2;
      //computation
      sum = num1 + num2;
      diff = num1 - num2;
      product = num1 * num2;
      quotient = (float)num1 /num2;
      //output
      printf("%d+%d\n",num1,num2,sum);
      printf("%d-%d=%d\n",num1,num2,diff);
      printf("%d*%d=%d\n",num1,num2,product);
      printf("%d/%d=%f\n",num1,num2,quotient);
      return 0;
}      
      
