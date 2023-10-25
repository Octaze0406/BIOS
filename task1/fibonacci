#include <stdio.h>

void generateFibonacci(int n, int x) {
    int a = 0, b = 1;

    // Move to the nth term
    for (int i = 2; i <= n; ++i) {
        int next = a + b;
        a = b;
        b = next;
    }

    // Print x Fibonacci numbers
    for (int i = 0; i < x; ++i) {
        printf("%d ", b);
        int next = a + b;
        a = b;
        b = next;
    }

    printf("\n");
}

int main() {
    int n, x;

    // Input n and x
    printf("Enter the value of n: ");
    scanf("%d", &n);
    printf("Enter the value of x: ");
    scanf("%d", &x);

    // Generate and print Fibonacci numbers
    generateFibonacci(n, x);

    return 0;
}
