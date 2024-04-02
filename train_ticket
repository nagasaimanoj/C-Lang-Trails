#include <stdio.h>

int main(){

    // variable declaration
    int age = 0;

    char source[] = "";
    char destination[] = "";

    float ticket_cost = 100.00;


    // inputs from user
    printf("Please enter following details \n");

    printf("Customer Age : ");
    scanf("%d", &age);


    printf("Source : ");
    scanf("%s", &source);


    printf("Destination : ");
    scanf("%s", &destination);

    // ticker price calculation
    if (age >= 80){
        // giving citigens with age about 80 with 20% discount
        ticket_cost = (ticket_cost * 0.8);
    } else if (age >= 60){
        // giving citigens with age 60-80 with 10% discount
        ticket_cost = (ticket_cost * 0.9);
    }

    printf("Ticket from %s to %s is %f", source, destination, ticket_cost);

    // "ANSI-C" is the original C language. in this version, main() need to return an integer value.
    return 0;
}







