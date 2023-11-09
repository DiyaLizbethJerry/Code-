# Code-
How to find the mean


#include <stdio.h>

int main() {
    int n;
    double sum = 0.0;

    printf("Enter a number of values: ");
    scanf("%d", &n);


    if (n < 0) {
        printf("Please enter a  number \n");
        return 1; 
    }

    printf("enter %d values :\n",n);
    for  ( int i=0;i<n;i++) {
        doublr value;
        scanf("%lf",&value);
        sum+= value ;
    }
double mean =sum/n; 
printf("mean:%.2lf\n",mean);

    return 0;
}


