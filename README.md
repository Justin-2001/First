# First
First activity
#include<stdio.h>

int main()
{
    int g1, g2, g3, g4, g5, gt;
    int av;

    printf("Grades: \n");
    printf(" ");
    scanf("%d", &g1);
    printf(" ");
    scanf("%d", &g2);
    printf(" ");
    scanf("%d", &g3);
    printf(" ");
    scanf("%d", &g4);
    printf(" ");
    scanf("%d", &g5);
    gt=g1+g2+g3+g4+g5;
    printf("Total Grade %d\n", gt);
    av=gt/5;
    printf("General Average %d", av);
     return 0;
}
