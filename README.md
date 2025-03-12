# c-19
Hollow right triangle 
#include <stdio.h>
int main() 
{
    int i,j,n;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            if(j==1||i==n||j==i){
                printf("* ");
        }else{
        printf("  ");
    }
        }
        printf("\n");
    }
    return 0;
}
