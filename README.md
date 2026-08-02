# Integer-Arithmetic-Operations-in-C
This program demonstrates basic arithmetic operations using int variables in C. It calculates the value of king using multiplication, addition, and subtraction, then displays the result using printf() with the correct format specifier for integers.
#include <stdio.h>
int main(){
    int i, king, issac, noteit;

    i = 5;
    issac = 10;
    noteit = 20;

    i = i + 1;
    king = issac*234 + noteit - 7689;
    printf("The value of king is %d", king);
    return 0;
}
