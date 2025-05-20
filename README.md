# Creditos
Programa de créditos para funcionários de uma empresa.

Projeto demo de programa de créditos para ter um controle sobre o uso dos créditos dos funcionários nos produtos da empresa.

O código Python foi utilizado no Colab Notebook do Google, podendo ser executado no mesmo terminal com a linguagem Python.

## Instruções de Execução
Esse script pode ser rodado na plataforma do Notebook Google. Ao abrir o Notebook Google você abre um Notebook, onde você consegue inserir esse código (caso queira pode copiar o código e colar no notebook). Na parte superior esquerdo da tela você verá um sinala de play onde ao clicar você consegue rodar o código.

Ao rodar o código aparecera quatro campos para inserir as informações requisitadas (Nome do funcionário, Valor do crédito, Nome do produto e Valor do produto em sequência)  para rodar o programa.

Após o preenchimento dessas quatro informações irá aparecer duas mensagens, sendo a segunda mensagem dividida em duas mensagens dependendo do valor colocado no campo Valor do produto. A primeira irá mostrar quanto restou de créditos. Já a segunda mensagem se divide em duas, caso tenha colocado um valor abaixo do valor colocado no campo Créditos (por exemplo, 300 reais de crédito e o valor do produto de 259 reais), a mensagem será de que você tem créditos sobrando. Caso seja um valor maior do que o valor colocado no campo Créditos (por exemplo, 300 reais de crédito e o valor do produto de 301 reais), a mensagem será de que você está devendo créditos.

Após essas duas mensagens irá aparecer mais um campo perguntando se deseja adicionar mais alguma peça. Caso a resposta seja "sim" você é direcionado para mais dois campos para adicionar as informações requisitadas (Nome do produto e Valor do produto em sequência). Se digitar qualquer outra coisa o código quebra (break).

Após isso irá aparecer as duas mensagens, a primeira avisando o que restou dos seus créditos e a segunda seguindo a mesma lógica de antes, caso o valor tenha ultrapassado o valor de 300 reais (valor de exemplo usado na explicação) irá aparecer uma mensagem avisando que você está devendo, caso não tenha ultrapassado o valor de 300 reais, irá aparecer a mensagem de você tem créditos sobrando.

Após isso o código chega o seu fim/é encerrado, podendo ser reiniciado quantas vezes quiser.


## Explicação dos códigos:
O comando Input foi utilizado nas primeiras 4 linhas para a inserção/entrada dos valores como nome do funcionário, crédito recebido, nome e valor do produto.

O comando Num_float foi utlizado para transformar a variável "valor" em um número real.

Na linha 6 utilizou Print para mostrar as informações de quem retirou tal peça e seu valor.

Já das linhas 8 ao 11, X representa a variável credito e Y representa a variável valor, onde na linha 10 se tem a subtração desses dois valores (credito - valor). O Print mostra o valor restante dessa subtração.

Nas linhas de 13 a 16 utilizou o comando If para uma condição utilizando >, caso Soma dê um valor maior que o credito (gastou mais que os créditos que você recebeu naquele mês) vai aparecer uma frase de Print avisando que está devendo. Else foi utilizado para caso essa comparação seja falsa (ou seja, tem mais créditos do que gastou) você recebe uma mensagem Print dizendo que sobrou créditos.

Das linhas do 18 ao 23 criou uma nova variável Nome2 com o comando Input para caso o funcionário queira adicionar mais um produto. Na linha 19 foi utilizado If igual a sim caso o funcionário queira, se responder outra coisa o programa se encerra. Criou-se as variáveis Peça2, Valor2, Num_float2 para a inserção dos valores e transformar o valor Valor2 em um número real. Print mostra as informações da peça e seu valor em número real adicionada.

Nas linhas de 25 a 27 criou-se W igual ao Num_float2 e Soma2 para fazer a subtração da peça em cima dos créditos restantes do calculo Soma feito na linha 10 do código. A partir disso Print mostra o valor restante dos créditos.

Nas últimas linhas do código de 29 a 32 utilizamos If como condição para caso o valor Soma2 for menor que credito aparecer a mensagem de Print alertando que está devendo. Else utilizado para caso seja contrário o Print mostrar a mensagem de que tem créditos sobrando.
