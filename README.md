# Trabalho_IAA015

## 1) Algoritmo Genético
##### Problema do Caixeiro Viajante
##### A Solução poderá ser apresentada em: Python (preferencialmente), ou em R, ou em Matlab, ou em C ou em Java.
##### Considere o seguinte problema de otimização (a escolha do número de 100 cidades foi feita simplesmente para tornar o problema intratável. A solução ótima para este problema não é conhecida).
##### Suponha que um caixeiro deva partir de sua cidade, visitar clientes em outras 99 cidades diferentes, e então retornar à sua cidade. Dadas as coordenadas das 100 cidades, descubra o percurso de menor distância que passe uma única vez por todas as cidades e retorne à cidade de origem.
##### Para tornar a coisa mais interessante, as coordenadas das cidades deverão ser sorteadas (aleatórias), considere que cada cidade possui um par de coordenadas (x e y) em um espaço limitado de 100 por 100 pixels.
##### O relatório deverá conter no mínimo a primeira melhor solução (obtida aleatoriamente na geração da população inicial) e a melhor solução obtida após um número mínimo de 1000 gerações. Gere as imagens em 2d dos pontos (cidades) e do caminho.
#### Sugestão:
##### (1) considere o cromossomo formado pelas cidades, onde a cidade de início (escolhida aleatoriamente) deverá estar na posição 0 e 100 e a ordem das cidades visitadas nas posições de 1 a 99 deverão ser definidas pelo algoritmo genético.
##### (2) A função de avaliação deverá minimizar a distância euclidiana entre as cidades (os pontos).
##### (3) Utilize no mínimo uma população com 100 indivíduos;
##### (4) Utilize no mínimo 1% de novos indivíduos obtidos pelo operador de mutação;
##### (5) Utilize no mínimo de 90% de novos indivíduos obtidos pelo método de cruzamento (crossover-ox);
##### (6) Preserve sempre a melhor solução de uma geração para outra.
##### Importante: A solução deverá implementar os operadores de “cruzamento” e “mutação”.
