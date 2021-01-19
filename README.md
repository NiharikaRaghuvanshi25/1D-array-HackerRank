1D array HackerRank
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int n,i,s=0;
    scanf("%d",&n); 
    int array[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&array[i]);
        s+=array[i];
    } 
    printf("%d",s); 
    return 0;
}
