#include <stdio.h>
#include <stdlib.h>

void main(int argc, char *argv[])
{
if (argc == 1)
{
    printf("Você não digitou nada");
    exit(0);
}
else
{
    printf("Você digitou %s", argv[1]);
}
    printf("\nCriado por Gustavo Moraes\n");
}
