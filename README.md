# caixaeletronico.py Readne do código do Caixa Eletrônico

Exibe uma mensagem inicial:

Caixa Eletrônico


Solicita que o usuário digite um valor inteiro para saque:

Digite um valor para saque (mínimo R$2):


Lê o valor digitado e armazena na variável valor.

Verifica se o valor é menor que R$2:

Se for menor que 2, exibe a mensagem:

Valor inválido


Se for maior ou igual a 2, realiza os seguintes passos:

Calcula a quantidade de notas necessárias, sempre pegando o maior valor primeiro:

Divide o valor por 100 para saber quantas notas de R$100.

Atualiza o valor com o resto da divisão.

Repete esse processo para as notas de:

R$50

R$20

R$10

R$5

R$2

Exibe a mensagem de sucesso:

Saque Realizado com Sucesso!


**Exibe a quantidade de cada tipo de nota usada, somente se for maior que zero:

Exemplo:

Notas de 100: 2
Notas de 50: 1
Notas de 2: 2

⚠️ Observações importantes:

O código não trata sobras (por exemplo, se o usuário pedir para sacar R$3, ele ignora o R$1 que sobra — isso pode causar erro).

O código vai tentar imprimir as variáveis notasX mesmo se o valor for inválido, o que causará erro se valor < 2.

✅ Exemplo de execução:

Entrada do usuário:

Digite um valor para saque (mínimo R$2): 186


Saída esperada:

Saque Realizado com Sucesso!
Notas de 100: 1
Notas de 50: 1
Notas de 20: 1
Notas de 10: 1
Notas de 5: 1
Notas de 2: 0
