#include <stdio.h>
int main () {
    int num1, num2, sum;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    sum = num1 + num2;
    if (num1 == num2) {
        sum = 3 * sum;
        printf("sum = %d\n", sum);
    }
    return 0;
}
