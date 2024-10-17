# Reg_linear_LimiteCheque
Este repositório contém o código e os dados utilizados para construir um modelo de Regressão Linear Múltipla que visa prever o limite de crédito de clientes de um banco com base em variáveis como idade, rendimento, salário, escolaridade e outros fatores

# Previsão de Limite de Crédito - Regressão Linear Múltipla

Este repositório contém o código e os dados utilizados para construir um modelo de **Regressão Linear Múltipla** que visa prever o **limite de crédito** de clientes de um banco com base em variáveis como idade, rendimento, salário, escolaridade e outros fatores. O projeto utiliza Python, juntamente com bibliotecas de aprendizado de máquina, para análise e visualização dos resultados.

## Estrutura do Projeto

O projeto está estruturado em um notebook Jupyter com as seguintes etapas principais:

### 1. **Análise Exploratória de Dados (EDA)**
   - Carregamento e visualização dos dados.
   - Verificação das variáveis disponíveis e suas relações com o target (Limite de Crédito).
   - Estatísticas descritivas e gráficos de dispersão para entender melhor o comportamento das variáveis.

### 2. **Pré-processamento dos Dados**
   - Transformação de variáveis categóricas em variáveis dummies (indicadoras).
   - Normalização dos dados usando `MinMaxScaler` para ajustar os valores em uma escala de 0 a 1.
   - Divisão dos dados em conjunto de treino e teste.

### 3. **Modelagem com Regressão Linear Múltipla**
   - Construção do modelo de **regressão linear múltipla** usando a biblioteca `sklearn`.
   - Ajuste do modelo com os dados de treino e realização de previsões no conjunto de teste.
   - Avaliação do modelo com métricas como **MAE**, **MSE** e **R²**.

### 4. **Visualização dos Resultados**
   - Gráfico comparando os valores reais com as previsões.
  
## Resultados

O modelo foi avaliado usando as seguintes métricas:

- **MAE (Mean Absolute Error)**: Indica o erro médio absoluto entre as previsões e os valores reais.
- **MSE (Mean Squared Error)**: Penaliza mais os erros maiores, mostrando o desvio em relação ao valor real.
- **R² (Coeficiente de Determinação)**: Mede o quanto da variabilidade dos dados é explicada pelo modelo.

