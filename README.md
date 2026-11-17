#include <stdio.h>

int main(void) {
    int num1, num2, sum;

    // Ask the user for two integers
    printf("Enter two integers: ");
    scanf("%d %d", &num1, &num2);

    // Calculate the sum
    sum = num1 + num2;

    // Print the result
    printf("%d + %d = %d\n", num1, num2, sum);

    return 0;
}
