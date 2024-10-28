---
title: "EEE023 - Trabalho de Conclusão de Curso"
collection: assignments
category: undergrad
excerpt: TCC na área de robótica (2022/2)
date: 2022-10-30
---
Orientador: Vinicius Mariano

Banca: Luciano Pimenta + Vinicius Mariano

Nota Final: 100

[Texto completo](https://raw.githubusercontent.com/fbartelt/tcc-apresentacao/master/Modelagem_e_Controle_de_um_Robo_para_Cirurgias__Felipe_Bartelt.pdf), [Slides da Apresentação](https://fbartelt.github.io/tcc-apresentacao/) ([repositório da apresentação](https://github.com/fbartelt/tcc-apresentacao)).

**Abstract:** A robótica cirúrgica é uma área, atualmente, com ativo desenvolvimento e pesquisas. Entretanto, não há exemplos de sistemas cirúrgicos autônomos devido a alta complexidade e grande número de restrições que regem procedimentos cirúrgicos. Dessa forma, o intuito desse trabalho é implementar o sistema da Vinci Si, bastante conhecido no mercado, no simulador UAIBot, um simulador desenvolvido para fins didáticos pelo prof. Vinicius e por isso contém diversas funções úteis para implementações rápidas de uma alta gama de algoritmos de controle. Dessa forma, tornar-se-á possível a implementação e desenvolvimento de estratégias de controle no simulador para o da Vinci.

Para a implementação do robô, tornou-se necessário a estimativa dos seus parâmetros de Denavit-Hartenberg, uma vez que não há material oficial com essas informações, assim como a criação de primitivas de colisão para cálculo de distância em ambientes com obstáculos. A fim de testar a implementação feita, propõe-se, por simulação, controlar um dos braços do robô para realizar a tarefa de atingir uma pose alvo em um ambiente com obstáculos complexos. Dada as restrições do problema, é de interesse o uso de algoritmos de controle baseados em programação quadrática que permitem minimizar uma função objetivo, atendendo-se a restrições de desigualdade quaisquer. Ainda, pretende-se considerar juntas passivas do da Vinci Si como atuadas, visando estudar a possibilidade de maiores graus de liberdade e, consequentemente, maior autonomia para o robô.

A estratégia de controle, com restrições de colisão, será comparada com uma outra formulação que não envolve restrições de colisão. Analisando-se o desempenho de ambas as estratégias, notou-se a incapacidade de evitar colisões quando essas restrições não são explícitas. Demonstrou-se a capacidade da otimização por programação quadrática convergir a uma pose alvo realizando, concomitante, evitamento de obstáculos. Observou-se que o gargalo para a utilização desses métodos no contexto de robótica cirúrgica é a construção do problema e não sua solução, devido ao tempo empregado para calcular diversas distâncias e concatenar todas as restrições em uma única representação.

**Palavras-chaves:** robótica cirúrgica; da Vinci Si; programação quadrática convexa; controle com restrição; manipuladores robóticos.