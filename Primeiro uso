#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#define T 10
// Avaliação 3.
//Ordenador com algoritimo Bubble sort ou clasificação por bolhas.
//Utilizando linguagem c.
// Nome: Miguel Bregalda Ferrari.

// Bubble sort, funciona do seguinte modo, ele pega o primeiro valor e compara com o valor seguinte, ou seja compara a posição 0 e 1, assim caso o valor 1 seja menor que o 0 eles trocam de posição, assim sucessivamente  1 e 2, 2 e 3...
// Fazendo esse lupem ate todos os numeros fiquem em ordem.

int main()
{
    setlocale(LC_ALL, "Portuguese");

    //Primeiro cria um vetor chamado de n, que tem seu tamanho definido pela constante T.
    int n[T];
    int x, y, c;
    // n = numero
    // T = tamanho
    // x e y = variaveis auxiliares
    // c = contador

    //Aqui pede para o usuario escrever os 10 numeros que serão ordenados.
    printf("Digite dez numeros, apertando enter apos cada numero:\n");
    for (x = 0; x < T; x++) {
        scanf("%d", &n[x]);
    //Aqui por um for,  pegas o numeros inteiros pela função scanf e armezana elas no vetor nm na posição x.
    //O for vai de x igual a zero ate x menor que tamanho, indo  a varredura ate 9, pois tamanho é igual a 10.

    }

    printf("Esta é a ordem atual dos itens:\n");
    // Para olhar como esta a ordem atual dos item a partir de um novo for.
    printf("\n=============//===============\n");
    for (x = 0; x < T; x++) {
        printf("%5d", n[x]);
    // Foi utilizado o %5 para que os numeros não fiquem grudados.
    }
     printf("\n=============//===============\n");


    // Aqui é o algoritimo de ordenação, que possui 2 laços for encadiados e 1 if.
     for (c = 1; c < T; c++) {
    // Primeiro temos um contador, onde vai do primeiro item ate o penultimo, pois o ultimo item não se compara a ninguem.
        for (x = 0; x < T - 1; x++) {
    // Nesse laço for , vai de 0 e vai ate  tamanho menos 1
            if ( n[x] > n[x + 1]) {
    // Se o numero da posição x for maior que o x + 1 que o proximo numero faz  a troca, utilizando os seguintes algoritimos para fazer a troca.
                y = n[x]; // y recebe oque esta em nx
                n[x] = n[x + 1]; // nx recebe oque esta em x + 1, ou seja a posição seguinte
                n[x + 1] = y; // a posição seguinte vai para a proxima.
    // fazendo isso ate todos os numeros ficarem em sequencia crescente.
    // Pronto isso é o Bubble sort
            }
        }
     }

     // Apos fazer a ordenação basta imprimir os numeros na tela, utilizando o mesmo for.
     printf("\n Seus numeros em forma ordenada: \n ");
     printf("\n=============//===============\n");
     for ( x = 0; x < T; x++) {
        printf("%5d", n[x]);
     }
     printf("\n=============//===============\n");









    return 0;
}
