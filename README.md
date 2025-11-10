# Find-square-root-using-iterative-method
Using C language program is made which gives the output to find the square root using Iterative method
#include <stdio.h>
int main() {
    float n, guess;
    scanf("%f", &n);
    guess = n/2;
    int i = 0;
    while(i < 10) {  // 10 iterations
        guess = (guess + n/guess)/2;
        i++;
    }
    printf("%f", guess);
    return 0;
}
