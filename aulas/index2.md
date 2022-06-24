# Introdução ao Cálculo Numérico

Cálculo numérico é a parte da matemática que se dedica a encontrar soluções numéricas para problemas definidos nas demais áreas, tais como, álgebra, aritmética, cálculo diferencial e integral.

Tais soluções são encontradas por meio de algoritmos que, no mais das vezes, buscam uma aproximação da

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




