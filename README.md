# Previsão de Preços de Veículos 🚗💰

## Visão Geral

O mercado automotivo brasileiro é um dos mais aquecidos do mundo, movimentando bilhões de reais anualmente. Seja para consumidores, revendedores ou instituições financeiras, a capacidade de prever com precisão os preços dos veículos é essencial para tomada de decisões estratégicas. 

Neste projeto, estou explorando técnicas avançadas de **Machine Learning** para criar modelos preditivos que ajudem a estimar os preços de veículos com base em suas características, como marca, modelo, quilometragem e idade.

---

## Objetivo do Projeto

O objetivo principal deste projeto é desenvolver um modelo de previsão de preços de veículos utilizando diferentes algoritmos de aprendizado de máquina. Até o momento, utilizei o **Random Forest**, e agora estou expandindo o projeto para incluir o **Multilayer Perceptron (MLP)**, uma rede neural artificial.

### Por que isso é importante?

- **Consumidores:** Ajudar compradores a identificar preços justos e evitar pagar acima do valor de mercado.
- **Revendedores:** Oferecer ferramentas para precificação precisa, otimizando lucros e competitividade.
- **Instituições Financeiras:** Melhorar a avaliação de risco em financiamentos e seguros de veículos.

---

## Técnicas Utilizadas

### 1. Random Forest 🌳
O **Random Forest** foi o primeiro modelo aplicado neste projeto. Ele é um algoritmo de aprendizado supervisionado baseado em árvores de decisão e é conhecido por:

- **Alta precisão:** Captura relações não lineares entre as variáveis.
- **Robustez:** Reduz o risco de overfitting devido ao uso de múltiplas árvores combinadas.
- **Importância das features:** Permite identificar quais características mais influenciam nos preços dos veículos.

### 2. Multilayer Perceptron (MLP) 🤖
Agora, estou introduzindo o **Multilayer Perceptron (MLP)**, uma rede neural artificial que pode capturar padrões ainda mais complexos nos dados. Algumas características do MLP incluem:

- **Capacidade de generalização:** Aprende representações complexas ao passar os dados por várias camadas de neurônios.
- **Flexibilidade:** Funciona bem para dados não lineares e de alta dimensionalidade.
- **Treinamento com backpropagation:** Os pesos da rede são ajustados iterativamente para minimizar o erro nas previsões.

---

## Estrutura do Projeto

- **`RandomFlorestAuto.ipynb`:** Notebook com o modelo de Random Forest, incluindo pré-processamento, engenharia de features e avaliação.
- **`MultilayerPerceptronAuto.ipynb`:** Notebook em desenvolvimento para aplicação do Multilayer Perceptron (MLP).
- **`README.md`:** Este arquivo, explicando o propósito e os detalhes do projeto.

---

## Próximos Passos

1. **Treinamento do MLP:** Implementar e ajustar o modelo de Multilayer Perceptron.
2. **Comparação de Modelos:** Avaliar o desempenho do MLP em relação ao Random Forest utilizando métricas como o **Mean Absolute Error (MAE)**.
3. **Otimização de Hiperparâmetros:** Aplicar técnicas como o **GridSearchCV** para encontrar a melhor configuração para cada modelo.
4. **Inclusão de Novas Variáveis:** Explorar a adição de variáveis macroeconômicas e regionais para melhorar a precisão das previsões.
5. **Publicação dos Resultados:** Compartilhar as conclusões e aprendizados no LinkedIn e outros canais.

---

## Conclusão

Este projeto é um esforço contínuo para explorar o potencial de **Machine Learning** no mercado automotivo brasileiro. A previsão de preços de veículos é uma aplicação prática e de alto impacto, com benefícios diretos para consumidores, empresas e instituições financeiras.

Convido você a explorar os notebooks disponíveis no repositório e acompanhar o progresso deste projeto! Qualquer feedback ou sugestão será muito bem-vindo. 🚀

---
