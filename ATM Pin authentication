#include <stdio.h>

int main() {
    int pin, userPin = 1234;       
    int attempts = 0;

    while (attempts < 3) {
        printf("Enter your ATM PIN: ");
        scanf("%d", &pin);

        if (pin == userPin) {
            printf("PIN Correct! Access Granted.\n");
            return 0;  
        } 
        else {
            printf("Incorrect PIN. Try Again.\n");
            attempts++;
        }
    }

    printf("Your card is blocked due to 3 incorrect attempts.\n");

    return 0;
}
