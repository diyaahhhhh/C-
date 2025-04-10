#include <stdio.h>

// External variable declaration
int extVar = 10;

void autoDemo() {
    auto int a = 5; // auto is default for local variables
    printf("Auto variable: %d\n", a);
}

void staticDemo() {
    static int s = 0; // static retains value between function calls
    s++;
    printf("Static variable: %d\n", s);
}

void registerDemo() {
    register int r = 15; // register is a hint to store variable in CPU register
    printf("Register variable: %d\n", r);
}

void externDemo() {
    extern int extVar; // uses external variable declared globally
    printf("Extern variable: %d\n", extVar);
}

int main() {
    printf("Demonstrating storage classes:\n\n");

    printf("1. Automatic Storage Class:\n");
    autoDemo();

    printf("\n2. Static Storage Class:\n");
    staticDemo();
    staticDemo(); // calling again to show static retains value

    printf("\n3. Register Storage Class:\n");
    registerDemo();

    printf("\n4. External Storage Class:\n");
    externDemo();

    return 0;
}
