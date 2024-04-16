# Verificar-idade

# Verificação de Idade

Este programa em C solicita ao usuário que insira a idade dez vezes e verifica se cada idade inserida corresponde a ser maior ou menor de idade, exibindo a mensagem apropriada.

## Como usar o programa

1. Compile o código-fonte usando um compilador C, como o gcc:

```
gcc -o verificacao_idade verificacao_idade.c
```

2. Execute o programa compilado:

```
./verificacao_idade
```

3. Insira a idade quando solicitado, e o programa exibirá se a pessoa é maior ou menor de idade.

## Exemplo de Uso

```
Digite sua idade: 25
Você é maior de idade!
Digite sua idade: 16
Você é menor de idade!
Digite sua idade: 20
Você é maior de idade!
...
```

## Como funciona

1. O programa utiliza um laço de repetição for para solicitar a idade do usuário dez vezes.
2. Para cada iteração do laço, o programa solicita que o usuário insira sua idade.
3. Após receber a idade, o programa verifica se é maior ou igual a 18.
4. Se a idade for maior ou igual a 18, o programa exibe a mensagem "Você é maior de idade!". Caso contrário, exibe "Você é menor de idade!".
5. O programa repete esse processo até que dez idades tenham sido inseridas.

## Observações

- O programa presume que as idades inseridas são números inteiros.
- A função `setlocale` é utilizada para configurar a localidade para "Portuguese", permitindo a exibição correta de caracteres especiais em português.
