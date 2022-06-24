# 1. Introdução ao Cálculo Numérico

[Cálculo numérico](https://www.conexaogeoclima.com.br/post/o_que_e_calculo_numerico) é a parte da matemática que se dedica a encontrar soluções numéricas para problemas definidos nas demais áreas, tais como, álgebra, aritmética, cálculo diferencial e integral.

Tais soluções são encontradas por meio de algoritmos que, no mais das vezes, provêem uma resposta aproximada ao problema.

As referências básicas para este texto são:

- [Almeida (2015)](https://repositorio.ufu.br/bitstream/123456789/25218/1/Calculo%20Numerico.pdf)
- [Franco (2007)](https://www.amazon.com.br/C%C3%A1lculo-num%C3%A9rico-Neide-Bertoldi-Franco/dp/8576050870), e
- [Justo et Al (2020)](https://github.com/reamat/CalculoNumerico)


## Aproximações sucessivas e sequências

Grande parte dos problemas numéricos de interesse prático não apresentam solução analítica exata.  Por isso, é preciso que especifique previamente o quão precisa deve ser a solução encontrada para que se saiba quando a aproximação é suficientemente adequada.  De fato, os métodos do cálculo numérico consistem na aplicação recursiva de um mesmo procedimento para obter uma aproximação cada vez melhor para a solução do problema.  A cada aplicação do método a distãncia entre a solução com um número infinito de casas decimais e a solução obtida fica menor.  Deste modo, pode-se garantir que o método poderá atingir a aproximação desejada.

Matematicamente, a ideia que fundamenta tais procedimentos é a noção de sequência convergente. Por isso, os métodos do cálculo numérico precisam ser formalizados em termos de uma função definida nos números naturais que representa a sequência dos passoa realizados para obtenção da solução do problema.

# 2. Do cálculo numérico à computação científica

Matematicamente, os métodos do cálculo numérico tem a capacidade de aproximar a solução tão bem quanto se queira.  Ocorre que a execução dos algoritmos do cálculo numérico se dá em computadores concretos que possuem limitação de memória para armazenar os valores da sequência construída pelo método bem como poder computacional limitado em termos de velocidade de processamento.  Por isso é preciso que os métodos do cálculo numérico sejam além de sequencias convergentes sejam eficientes, isto é, a convergência ocorra com poucos passos.  Uma medida da velocidade de convergência é dada pela notação O.

Veja mais sobre isso em [Franco e al (2007, cap. 2](https://www.ufrgs.br/reamat/CalculoNumerico/livro-py/rdneadm.html).

# 3. Organização de computadores

De modo simplificado, computadores são formados por:

- dispositivo de entrada de dados (E)
- unidade central de processamento (UCP)
- memória (MEM)
- dispositivo de saída de dados (S).

Estes dispositivos operam em conjunto sob a coordenação da UCP (que é mais conhecida pela sigla em inglês CPU).  Com efeito, o funcionamento do computador pode ser descrito como segue.  A CPU faz a leitura de dados e de um conjunto de instruções gravados pelo usuário no dispositivo de entrada de dados, armazena tais dados na memória, executa as instruções (operações) nos dados em memória e escreve os dados resultantes das operações no dispositivos de saída para os usuários.  Terminada a escrita, a CPU fica pronta novamente para ler o dispositivo de entrada e recomeçar todas as operações realizadas anteriormente em um ciclo infinito até que ela seja desligada.


# 4. Sistemas numéricos e análise de arredondamento de ponto flutuante.

Um [sistema numérico](http://www.inf.ufsc.br/~bosco/extensao/sistemas-de-numeracao.pdf) é um conjunto de símbolos denominados algarismo utilizados para representar elementos de conjuntos numéricos.

O número de algarimos utilizados para representar os números é chamado de de base do sistema numérico.  Por exemplo, o [sistema numérico decimal](http://mdmat.mat.ufrgs.br/anos_iniciais/sn_decimal_posicional/sn_decimal_posicional.htm), que é o mais usado e conhecido, possui dez algarismos, quais sejam, 0, 1, 2,3, 4, 5, 6, 7, 8 e 9.  Com estes 10 algarimos todos os números racionais podem ser escritos.

Existem, porém, outros sistemas numéricos além do decimal.  Os mais utilizados em computadores são o [sistema binário](https://pt.wikipedia.org/wiki/Sistema_de_numera%C3%A7%C3%A3o_bin%C3%A1rio) (0 e 1), [sistema octal](https://pt.wikipedia.org/wiki/Sistema_octal#:~:text=Sistema%20Octal%20%C3%A9%20um%20sistema,programa%C3%A7%C3%A3o%20em%20linguagem%20de%20m%C3%A1quina.) (0,1,2,3,4,5,6,7) e o [sistema hexadecimal](http://marco.uminho.pt/~joao/Computacao2/node10.html) (0,1,2,3,4,5,6,7,8,9, A, B, C, D, E, F).

É particularmente interessante o sistema binário, pois computadores reais trabalham com transistores que alterando a tensão da corrente elétrica que recebem de modo denotar um estado sem alteração como 0 e um estado alterado como 1.  Ou seja, o formato nativo de operação dos circuitos da CPU é binário.

## 4.1 Sistema binário

### Representação de um número binário


### Conversão para o sistema decimal


### Conversão de decimal para binário.

