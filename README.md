# israelbraga_circuitex

  Cálculo automático de circuitos

  O conceito do projeto é um programa na linguagem Python para realizar cálculos de circuitos com elementos reativos de maneira interativa. Por simplicidade, serão considerados circuitos em que se pode aplicar o teorema de Milman, uma configuração usual em circuitos. A ideia surgiu através da cadeira de circuitos elétricos 1, onde usualmente era necessário obter resultados desses circuitos e demandava-se um tempo razoável de cálculo.
  
  interface gráfica:
  Classes:
  Janela, pública, que contém todos objetos de estudo
  Botão, que possui como atributos privados: Grid, width, color e método bt_click
  Entry,  que possui como atributos privados: Grid, width, color e método bt_click
  
  Lógica do programa:
  Classe:
  Ramo, que representa cada ramo do circuito, possuindo como atributos:FLOAT (Fase, frequência, amplitude, resistência)
  COMPLEX(indutância, capacitância) e método para calcular a ddp pelo teorema de Milman
