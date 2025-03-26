# Previsão de Preços de Veículos 🚗💰

## Visão Geral

O mercado automotivo brasileiro é extremamente aquecido, movimentando bilhões de reais anualmente. A previsão de preços de veículos pode oferecer benefícios significativos para consumidores, revendedores e instituições financeiras, auxiliando na tomada de decisões estratégicas e na avaliação de riscos.

Neste projeto, estou explorando diversas técnicas de Machine Learning para desenvolver modelos preditivos que estimem com precisão os preços de veículos. Inicialmente, utilizei o Random Forest, e agora estou ampliando o escopo com a implementação de modelos de Multilayer Perceptron (MLP) e LightGBM.

---

## Objetivos do Projeto

- Desenvolver modelos preditivos que estimem os preços de veículos com base em suas características (como marca, modelo, quilometragem, idade, entre outros).
- Comparar o desempenho de diferentes algoritmos utilizando métricas de avaliação, especialmente o MAE (Mean Absolute Error).
- Explorar e otimizar hiperparâmetros utilizando técnicas como GridSearchCV para atingir a melhor performance possível.
- Oferecer insights que possam auxiliar consumidores, revendedores e instituições financeiras na tomada de decisões.

---

## Técnicas Utilizadas

### 1. Random Forest 🌳

O Random Forest é uma técnica de ensemble learning que utiliza várias árvores de decisão para obter previsões mais robustas e precisas.  
**Principais Características:**
- Alta precisão na captura de relações não lineares.
- Redução do risco de overfitting por meio do uso de bagging e da amostragem aleatória de features.
- Capacidade de fornecer insights sobre a importância de cada feature na previsão.

---

### 2. Multilayer Perceptron (MLP) 🤖

O MLP é uma rede neural artificial composta por uma ou mais camadas ocultas, capaz de aprender representações complexas dos dados.  
**Principais Características:**
- Modela relações altamente não lineares.
- Flexível para capturar padrões complexos mesmo em dados com alta dimensionalidade.
- Treinamento por meio de backpropagation, onde os pesos são ajustados iterativamente para minimizar os erros.

---

### 3. LightGBM 🌟

O LightGBM é um algoritmo de gradient boosting otimizado para velocidade e eficiência, ideal para grandes conjuntos de dados.  
**Principais Características:**
- Processa grandes volumes de dados de maneira rápida e eficiente.
- Excelente na captura de interações complexas entre variáveis.
- Escalável e adequado para aplicações do mundo real.

---

## Estrutura do Projeto

- **RandomFlorestAuto.ipynb**: Notebook contendo o modelo Random Forest, com etapas de pré-processamento, engenharia de features e avaliação.
- **MultilayerPerceptronAuto.ipynb**: Notebook em desenvolvimento para a implementação e ajuste do modelo MLP.
- **LightGBM_Auto.ipynb**: Notebook dedicado ao desenvolvimento e otimização do modelo LightGBM.
- **README.md**: Este arquivo, que descreve o propósito, as técnicas e a estrutura do projeto.

---

## Conclusão e Próximos Passos

Ao longo do projeto, irei implementar, treinar e avaliar cada um dos modelos propostos. Os resultados serão analisados e comparados, e os insights obtidos contribuirão para definir qual abordagem é a mais adequada para a previsão dos preços de veículos no cenário atual.

Na conclusão do projeto, farei uma análise comparativa detalhada com as métricas de avaliação (como o MAE), tempos de treinamento e outras observações relevantes para cada modelo. Essa comparação será integrada à seção de Conclusão, permitindo uma visão clara de qual técnica apresentou um desempenho superior.

---
