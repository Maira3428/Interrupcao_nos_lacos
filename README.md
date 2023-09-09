# Interrupcao_nos_lacos
GitHub Desktop tutorial repository
As linguagens de programação dispõem de dois comandos especiais para seem utilizados nas estruturas 
de repetição.
São eles: break sai do laço de repetição, enquanto o continue retorna ao inicio do laço.
Estes comandos nos auxiliam no controle de execução dos comandos do loop.

Os comandos break e continue podem ser utilizados nas tres estruturas de repetição
disponiveis: for, while ou do...while. Caso o comando continue seja executado em um laço for,
o incremento ou decremento da variavel de controle ocorre normalmente como se o laço tivesse sido
executado até o seu final.

No exemplo realizado no codigo tambem utilizados metodos prompt() e alert(), agora para demonstrar
o funcionamento dos comandos break e continue. O programa realiza a leitura de um numero e, caso o
numero for par ele exibe o dobro do numero e se for impar, o triplo. A leitura contunua até que o 
usuario informe 0 (ou algum valor invalido). Inicialmente, uma mensagem alertando sobre a execução 
do programa é apresentada.

Foi utilizado tambem um novo metodo para solicitar a confirmação de saida do programa. Trata-se do
metodo confirm(), que exibe uma caixa de dialogo com os botões ok e cancelar. Ele retorna true (ok)
ou false (cancelar) de acordo com a escolha do usuario.

Casoo usuario confirme sida do programa,o comando break é executado e o metodo alert("bye, bye..."),
apos o laço de repetição, é chamado. Contudo, caso o usuario não confirme a saida, o comando continue
retorna ao inicio do laço e uma nova leitura é realizada pelo método prompt().

A condição inserida no comando while() foi substituida pelo valor true. Isso significa que a repetição
não sairá pela análise da condição. A unica forma de saída desse laço, portanto, é pela execução do 
comando break.

Outro detalhe neste programa: as variáveis num e sair foram declaradas com const. Mas, se elas podem
receber valores diferentes a cada repetição, elas não deveriam ser declaradas com let? O que ocorre
é que as variáveis criadas dentro de um bloco de comandos (no caso, while) deixam de existir ao final
do bloco. Assim, a cada repetição, essas variáveis  são novamente criadas- sem nenhuma "lembrança" da 
declaração anterior.



