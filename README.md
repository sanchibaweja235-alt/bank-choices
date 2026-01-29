#include<stdio.h>
int main(){

    int userchoice;
    float balance=5000,temp;
    printf("User choice\n");
    printf("1. Deposit\n");
    printf("2. Withdrawl\n");
    printf("3. Balance check\n");
    printf("4. exit\n");
    scanf("%d",&userchoice);
    switch(userchoice){
        case 1:printf("Enter amount to deposit\n");
        scanf("%f",&temp);
        balance=balance+temp;
        break;
        case 2:printf("Withdraw \n");
        scanf("%f",&temp);
        break;
        case3:printf("Balance=%f",balance);
        break;
        case4:printf("Exit\n");
        break;
        default:
        printf("invalid choice\n");
    }
    return 0;
}
