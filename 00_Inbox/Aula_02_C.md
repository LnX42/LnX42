### Laço de repetição FOR

> FOR tem uma conceito bem facil de entende:

`for (inicio; condição; incremento) {
    Código aqui
}`

- Ex:
`for (int i = 0; i < 5; i++) {
    printf("Oi\n");
}`

- Ou seja, Comece do zero, de zero a cinco, soma 1 executando o código abaixo
- Assim, vai aparecer na tela "oi" 5 vezes pois pediu para que ele executasse o código abaixo até 5.

## Ligando `for` com Arrays (IMPORTANTE)
`
int notas[5] = {7,5,7,4,10};

for (int i = 0; i < 5; i++) {
    printf("%d\n", notas[i]);
}
`
- i começa em 0
- notas[i] acessa cada posição
- `for` percorre o array inteiro
