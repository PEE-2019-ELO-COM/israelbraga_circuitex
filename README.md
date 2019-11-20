

# Descrição do conceito
  O conceito do projeto é um programa na linguagem Python com a biblioteca gráfica [Tkinter](https://docs.python.org/3/library/tkinter.html) para realizar cálculos de circuitos com elementos reativos de maneira interativa. Por simplicidade, serão considerados circuitos em que se pode aplicar o [teorema de Milman](http://www.ufrgs.br/eng04030/Aulas/teoria/cap_06/millman.htm), uma configuração usual em circuitos.Ressaltando que no programa as resistências serão generalizadas para impedâncias, devido à presença de fontas AC com elementos reativos.
# Motivação
  A ideia surgiu através da cadeira de circuitos elétricos 1, onde usualmente era necessário obter resultados desses circuitos e demandava-se um tempo razoável de cálculo, em especial por envolver números complexos.
# Funções do programa
  O programa trabalhará recebendo entradas de cada ramo do circuito (frequência angular, resistência, capacitância, indutância e Vpp). Efetuará o teorema de Milman no domínio dos números complexos e devolverá a forma de onda senoidal resultante da difereça de potencial comum a todos os ramos.

# Instruções de uso
  O usuário, na posse de vários ramos de um circuito irá inserir em cada infromação de cada ramo. É Necessário ressaltar que o programa foi feito para o regime estacionário de circuitos senoidais. Dessa forma, devemos colocar a frequência angular da fonte de tensão, seu Vpp, sua fase e seus elementos passivos.
  




![imagem2_exemplo](https://user-images.githubusercontent.com/55092617/69278423-13fa8400-0bc1-11ea-831f-7890bac99fb6.png)
