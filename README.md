#include <stdio.h>

// Global variable
int globalVar = 25; 

// Static global variable
static int staticGlobalVar = 20; 

void function() {
    // Automatic variable
    auto int autoVar = 30; 

    // Static variable
    static int staticVar = 15; 

    // Register variable
    register int registerVar = 40; 

    printf("Automatic Variable: %d\n", autoVar);
    printf("Static Variable: %d\n", staticVar);
    printf("Register Variable: %d\n", registerVar);
    printf("Global Variable: %d\n", globalVar);
    printf("Static Global Variable: %d\n", staticGlobalVar);
}

int main() {
    function();
    return 0;
}
