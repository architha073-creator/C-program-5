# C-program-5
Ticket 
#include <stdio.h>
int main()
{
    int age,day,price;
    printf("enter age");
    scanf("%d",&age);
    printf("enter day");
    scanf("%d",&day);
    if (age<=12)
    {
        price=100;
        printf("price ₹%d",price);
    }
    else if(age>12 && age<60)
    {
        price=150;
        printf("price ₹%d",price);
    }
    else
    {
        price=120;
        printf("price ₹%d",price);
    }
    if (day==4)
    {    
        price=price-20;
        printf("price after discount ₹%d",price);
    }
    return 0 ;
    }
