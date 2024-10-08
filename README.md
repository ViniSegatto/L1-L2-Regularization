# **Regressão L1 e L2: Ridge e Lasso**

![image](https://github.com/user-attachments/assets/6688ae32-adb3-4eb0-9c23-3858b49348cd)


Este repositório explora as técnicas de regularização em modelos de regressão linear, focando nas abordagens Ridge (L2) e Lasso (L1). Essas técnicas são amplamente utilizadas para melhorar a performance de modelos, principalmente em cenários com alto risco de overfitting ou com grande quantidade de variáveis.

![image](https://github.com/user-attachments/assets/dc304968-e4b1-4c61-a690-734d926ad51c)

## **Descrição**

A regularização é uma abordagem essencial para controlar a complexidade de modelos, especialmente em problemas de aprendizado de máquina com muitas características. Aqui, discutimos e implementamos as duas formas mais comuns de regularização:

 * **Regressão Ridge (L2)**: Adiciona uma penalidade proporcional ao quadrado da magnitude dos coeficientes. Isso reduz o impacto de variáveis menos importantes sem forçá-las a zero, sendo eficaz em situações onde todas as variáveis têm algum grau de relevância.

 * **Regressão Lasso (L1)**: Aplica uma penalidade proporcional ao valor absoluto dos coeficientes, permitindo que alguns coeficientes se tornem exatamente zero. Isso faz com que Lasso também funcione como uma técnica de seleção de características. 

Essas duas técnicas, embora similares na teoria, possuem diferenças cruciais que afetam a escolha de cada uma conforme o problema a ser resolvido.

## **Implementação**
O repositório inclui notebooks com a implementação dessas técnicas em Python, usando bibliotecas como "scikit-learn" e "pandas". 

Os principais pontos abordados são:

 * Explicação teórica dos métodos Ridge e Lasso.
 * Implementação prática com exemplos.
 * Comparação entre os dois métodos em diferentes conjuntos de dados.
 * Visualização dos impactos da regularização no ajuste dos modelos.

## **Conceitos Fundamentais**
### **Regularização**

Regularização é uma técnica que visa evitar o overfitting ao adicionar uma penalidade à função objetivo, forçando os coeficientes dos modelos a valores menores. Isso melhora a capacidade de generalização dos modelos, tornando-os mais robustos para dados novos.

### **Ridge (L2)**
 * Penaliza o quadrado dos coeficientes.
 * A função objetivo minimiza: Erro LS + α * (soma dos coeficientes²).
 * Útil quando queremos reduzir o impacto das variáveis sem excluir nenhuma.
   
### **Lasso (L1)**
 * Penaliza o valor absoluto dos coeficientes.
 * A função objetivo minimiza: Erro LS + α * (soma dos coeficientes absolutos).
 * Indicado para seleção de características, pois alguns coeficientes podem se tornar zero.

A seguir consegui apenas encontrar imagens em ingles para mostrar essas equações na pratica. 
![image](https://github.com/user-attachments/assets/be3bf611-0a97-4f18-b067-c0676637c5a3)

