#include <stdio.h>
#include <stdlib.h>

int main()
{
    for(int i=1 ; i<=5 ; i++){

        printf("i=%d\n",i);
    }

   for(int row=1;row<=5;row++)
    {
        for(int col=1;col<=9;col++)
        {
           printf("(%d,%d)",row,col);
        }
        printf("\n");
    }

        for(int i=1;i<=6;i++)
            {
            for(int j=1;j<=i;j++)
            {
                printf("%d",j);
            }
            printf("\n");
        }

    return 0;
}
