# bill-genearator-stationery
c 

#include <stdio.h>

int main() {
    int n,i;
    char item[10];
    int quantity;
    float price,total=0,amount=0;
    printf("enter number of items:");
    scanf("%d",&n);
    
    printf("\n------stationary bill generator-----\n");
    for(i=1;i<=n;i++){
        
     printf("enter item name:");
     scanf("%s",&item);
     printf("enter quantity:");
     scanf("%d", &quantity);
     printf("enter price per item:");
     scanf("%f",&price);
     amount=quantity*price ;
     printf("amount:%f\n",amount);

    total+=amount ;
     }
     printf("total:%f\n",total);
     printf("\n-----thank you-----\n");
     return 0;
}
