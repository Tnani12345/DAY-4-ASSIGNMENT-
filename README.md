# DAY-4-ASSIGNMENT-
DAY-4 ASSIGNMENT SUBMITTED 
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a value for n: ");
    scanf("%d", &n);

    for (int i = 1; i <= n; i++) {
        sum += 2*i-1; // ith odd number is 2i-1
    }

    printf("Sum of the first %d odd numbers is: %d\n", n, sum);
    printf("n^2 is: %d\n", n*n);

    if (sum == n*n) {
        printf("The fact is verified!\n");
    } else {
        printf("The fact is not verified!\n");
    }

    return 0;
}
