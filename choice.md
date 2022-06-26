#include<stdio.h>
int main()
{
    int n,choice;
    printf("enter the choice : \n");
    scanf("%d",&choice);
    printf("enter the combo : \n");
    scanf("%d",&n);
    switch(choice)
    {
        case 1: 
        switch(n)
        {
            case 1: 
            printf("noodles");
            break;
            case 2:
            printf("burger");
            break;
            case 3:
            printf("pizza");
            break;
            case 4:
            printf("french fries");
            break;
            case 5:
            printf("momos");
            break;
            case 6:
            printf("puff");
            break;
            case 7:
            printf("cake");
            default:
            printf("invalid combo");
            break;
        }
        break;
        case 2:
        switch(n)
        {
            case 1:
            printf("coke");
            break;
            case 2:
            printf("mountain dew");
            break;
            case 3:
            printf("limca");
            break;
            case 4:
            printf("milkshake");
            break;
            case 5:
            printf("juice");
            break;
            default:
            printf("invalid combo");
            break;
        }
        break;
        default:
        printf("invalid choice");
        break;
    }
    return 0;
}
