algoritmo - "nome_programa"
Inicio - Inicia
escreva -  exibe a mensagem na tela
fim - determina o inicio e fim do nome_programa
inteiro - Ex. 10, 5, -3 (Int)
real- Ex. 3.12, 5.12 (Float)
caracter - "João", "Al" (String)
logicos - Valores Booleanos (true, false)
var

algoritmo "OPERACOES"
var
    num1, num2, soma: inteiro
inicio
    escreva("Digite o primeiro numero: ")
    leia(num1)
    escreva("Digite o segundo numero: ")
    leia(num2)
    soma <- num1 + num2
    escreva("A soma é: ", soma)
fim



algoritmo "Maioridade"
var
    idade: inteiro
inicio
     escreva("Digite sua idade: ")
     leia(idade)
     se idade >= 18 então
        escreva("Você é maior de idade.")
    senao
        escreva("Você é menor de idade.")
    fimse
fim

algoritmo "Contagem"
var
    i: inteiro
inicio
    i <- 1
    enquanto i <= 10 faca
        escreva (i, " ")
    fimenquanto
fim