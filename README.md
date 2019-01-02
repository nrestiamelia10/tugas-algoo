#include <stdio.h>
int JUMLAH (int x, int y);
int main ()
{
    int A,B,T;
    A=5; B=2;
    T= JUMLAH(A,B);
    printf("d",T);
}
int JUMLAH(int x, int y)
{
    int H;
    H= x+y;
    return(H);
}
