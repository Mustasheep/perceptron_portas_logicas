## Algoritmos de aprendizado de máquina para portas lógicas

Este repositório contém dois códigos Python que implementam diferentes algoritmos de aprendizado de máquina para resolver o problema da porta AND e XOR.

--------------------------
**Código 1: Perceptron Simples**

O primeiro código implementa um perceptron simples, um modelo de aprendizado de máquina mais básico.

* **Objetivo:** Treinar um perceptron para aproximar a função AND. Embora não seja ideal para este problema (por sua natureza linear), o código demonstra um algoritmo de aprendizado mais simples.
* **Metodologia:** Utiliza a função de ativação degrau (step function) e ajusta os pesos iterativamente com base no erro.
* **Métricas:** O erro total a cada iteração é exibido, mostrando o processo de treinamento até que o erro seja zerado (ou um critério de parada seja atingido).

---------------------------
**Código 2: Rede Neural com Backpropagation**

O segundoo código implementa uma rede neural de duas camadas (uma camada de entrada, uma camada oculta e uma camada de saída) usando o algoritmo de backpropagation para ajustar os pesos sinápticos.

* **Objetivo:** Treinar uma rede neural para aproximar a função XOR. O algoritmo ajusta iterativamente os pesos da rede com base no erro entre a saída prevista e a saída desejada.
* **Metodologia:** Utiliza a função sigmoide como função de ativação e o gradiente descendente para minimizar o erro. O momentum é incorporado para acelerar a convergência.
* **Métricas:**  A margem de erro (média do erro absoluto) é impressa a cada iteração, mostrando a convergência do modelo.
