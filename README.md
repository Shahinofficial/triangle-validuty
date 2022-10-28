#include<stdio.h>


int main(){
int n,a,b,c;

        printf("Enter Tringale Value of a b c:");
        scanf("%d %d %d",&a,&b,&c);

        n= a+b+c;

        if (n==180 && a>0 && b>0 && c>0){
            printf("Tringale Valid");
        }
        else {
            printf("Tringale invalid");
        }
        return 0;
        }
