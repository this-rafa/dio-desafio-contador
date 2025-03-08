# Desafio DIO - Contador em Java

Este repositório contém a solução para um desafio proposto pela [DIO](https://www.dio.me/) utilizando a linguagem Java.

## Descrição

O programa solicita dois números inteiros ao usuário e imprime uma contagem entre eles. Caso o primeiro número seja maior que o segundo, uma exceção personalizada é lançada.

## Estrutura do Código

- O programa utiliza a classe `Scanner` para capturar a entrada do usuário.
- Os valores informados são passados para o método `contar(int parametroUm, int parametroDois)`, que realiza a contagem.
- Caso o primeiro número seja maior que o segundo, uma exceção do tipo `ParametrosInvalidosException` é lançada com uma mensagem de erro.
- Se os valores forem válidos, o programa imprime a contagem do primeiro até o segundo valor.

## Exemplo de Entrada e Saída

### Entrada:
```
Digite o primeiro parâmetro
2
Digite o segundo parâmetro
5
```

### Saída:
```
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```

## Exceções
Caso o primeiro número seja maior que o segundo, a seguinte mensagem será exibida:
```
O segundo parâmetro deve ser maior que o primeiro
```

## Como Executar o Programa

1. Certifique-se de ter o [Java](https://www.oracle.com/java/technologies/javase-downloads.html) instalado.
2. Compile o programa:
   ```sh
   javac Contador.java
   ```
3. Execute o programa:
   ```sh
   java Contador
   ```

## Autor
Desenvolvido como parte de um desafio da DIO.

