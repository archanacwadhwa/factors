//factors
//finds the factors of the number
#include <stdio.h>

int main()
{
   int num,i;
   printf("\n ENTER THE NUMBER");
   scanf("%d",&num);
   printf("\n FACTORS ARE:");
   for(i=1;i<=num;++i)
    {
        if(num%i==0)
            printf("%d\t",i);
    }
    return 0;
}
