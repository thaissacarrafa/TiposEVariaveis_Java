# Tipos e Variáveis - Java

O PC quebrou, então, vou usar o readme como "pasta de prints" de alguns conceitos que estou estudando pela IDE online. 


## Tipo Inteiro: Int 

![int](https://user-images.githubusercontent.com/69389369/117715207-5ac1ac80-b1ae-11eb-819c-d6a51ed55a97.PNG)

Observações:
- Lembrar do ; no final;
- Mesclar string + number. Exemplo:
 idade = 27
 System.out.println("Minha idade é " + 27);
 
 
 
 ## Tipo Flutuante: Double
 
 ![double](https://user-images.githubusercontent.com/69389369/117715838-31ede700-b1af-11eb-9dc5-7c4962a99b13.PNG)

Usarei o Double quando se tratar de números com ponto flutuante. Lembrando que separamos as casas decimais no Java com ponto (.) e não vírgula (,). 

Outro ponto de super atenção é que sempre que fazemos operações entre inteiros usando double o resultado sempre será inteiro e não de ponto flutuante. 

![double calculo inteiro](https://user-images.githubusercontent.com/69389369/117715996-68c3fd00-b1af-11eb-8627-040fbf0dbfa8.PNG)

No caso acima para aparecer o resultado de 5/2 = 2.5 é necessário transforar o 5 em número com ponto flutuante ( 5.0). Veja a seguir:


![double calculo inteiro 2](https://user-images.githubusercontent.com/69389369/117716132-9741d800-b1af-11eb-9592-79b592e000a6.PNG)

Observações: um número *inteiro* cabe em um *double*, porém o inverso não pode ocorrer, a não ser que coloquemos o (int) que é uma forma do Java assegurar que estamos cientes que "perderemos" alguns valores da casa decimal. 

Veja abaixo:

![conversao](https://user-images.githubusercontent.com/69389369/117716838-7332c680-b1b0-11eb-9966-87ce205d5bd2.PNG)

Observações: o *(int)* é um type casting - que nada mais é uma forma de fazer uma conversão onde pode haver perda de informações.


 ## Float
 
![float](https://user-images.githubusercontent.com/69389369/117743231-c7ec3680-b1dc-11eb-849a-7d0837a6e252.PNG)

Float tem uma limite de casa de decimais, já o double aparecem várias casas decimais após a virgula ( caso tenha o *f* no número decimal). Para utilizar o float é necessário colocar o *f* após o número decimal para que o Java compreenda. 

## Char

- Comentários no código

![char](https://user-images.githubusercontent.com/69389369/117744576-5b266b80-b1df-11eb-8e19-6dde6d122a4a.PNG)


## Variáveis primitivas ( guardando valores)

- Comentários no código

![treinando valores](https://user-images.githubusercontent.com/69389369/117747301-4e584680-b1e4-11eb-9b9e-5baafec1295d.PNG)

