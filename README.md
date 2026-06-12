#include<stdio.h>

int main()
{
    int n1 = 0, n2 = 1;
    int next, n;

    printf("Enter your limit: ");
    scanf("%d", &n);

    printf("Fibonacci Series:\n"); // aita holo n tomo porjonto koyta fibonacci ache

   while(n1<= n)
    {
        printf("%d\n", n1);

        next = n1 + n2;
        n1 = n2;
        n2 = next;
    }

    return 0;
}
