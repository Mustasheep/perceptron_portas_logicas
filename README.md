# Perceptron - Tabela AND
Esse código implementa um perceptron de uma única camada, usando a função de ativação step function, para aprender a função lógica AND. 
-----------------

**Algoritmo de Aprendizado**

O algoritmo usa o método de aprendizado supervisionado pelo erro (delta rule).  Para cada entrada:

* Calcula a saída do perceptron;
* Calcula o erro entre a saída desejada e a saída calculada.
* Atualiza os pesos usando uma regra que ajusta os pesos proporcionalmente ao erro e à entrada correspondente.

O loop continua até que a margem de erro seja 0, indicando que o perceptron aprendeu a função AND perfeitamente (ou atingiu o critério de parada).

**Em resumo:** O código implementa um perceptron simples que aprende a função lógica AND através do ajuste iterativo dos seus pesos baseado no erro.  Ele usa uma função de ativação step function e um algoritmo de aprendizado supervisionado.

**Limitações:**

* **Função de ativação:** A função degrau é uma escolha simples, mas limita a capacidade do perceptron.
* **Convergência:**  Nem todos os problemas são linearmente separáveis e, portanto, este perceptron pode não convergir para uma solução perfeita para problemas mais complexos.
* **Apenas AND:** Este código está especificamente configurado para aprender a função AND. Para funções lógicas diferentes (OR, XOR), as saídas serão alteradas, e para funções mais complexas, seria necessário um perceptron multicamadas (rede neural).
