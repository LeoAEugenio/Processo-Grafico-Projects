Projeto de Processamento Grafico.

PARTE 1 - Sem matriz de transformação
Exercício 1
Crie uma função:

GLuint createTriangle(float x0, float y0, float x1, float y1, float x2, float y2);
Essa função deve criar um triângulo com as coordenadas dos vértices v0, v1 e v2 passadas por parâmetro, retornando seu identificador de VAO.

Exercício 2
Instancie 5 triângulos na tela utilizando a função criada anteriormente.

Sugestão:

Utilize um array ou vector para armazenar os VAOs retornados pela função.
Para desenhá-los, itere sobre o array ou vector no loop de renderização.
PARTE 2 - Com matriz de transformação
A partir deste exercício, sugere-se utilizar a biblioteca GLM para cálculos matemáticos.

Exercício 3
Crie uma estrutura (struct ou classe) chamada Triangle que armazene:

 A posição do triângulo (x, y);
 A cor do triângulo (componentes RGB).
Utilizando a função criada anteriormente, gere um único VAO para um triângulo padrão com os seguintes vértices:  v0(-0.1, -0.1),   v1(0.1, -0.1),  v2(0.0, 0.1)

Usando um array, vector ou list de estruturas Triangle e o VAO criado, o programa deverá criar novos triângulos posicionados a partir do clique do mouse na tela. A cor de cada triângulo deve variar, sorteando-se valores para as componentes RGB da cor.
