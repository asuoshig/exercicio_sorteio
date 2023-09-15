# exercicio_sorteio
programa
{
inclua biblioteca util--> u

funcao inicio()
{
    inteiro contador, numero, mult
    escreva ("qual número você quer multiplicar?)
    leia (numero)
    contador=1

    enquanto (contador <= 10){
         mult = numero * contador
         escreva (numero, "*" , contador, "=", mult)
         escreva ("\n")
         u.aguarde (500)
         contador++
