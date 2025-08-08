# ✈️ Previsão de Atrasos em Voos

Este projeto tem como objetivo **analisar e prever atrasos em voos** utilizando técnicas de ciência de dados e machine learning. Foram explorados dados de voos, feita a análise exploratória, limpeza, modelagem preditiva e avaliação de desempenho.

## 📂 Estrutura do Projeto

* **`data/`** → Contém os arquivos de dados originais e processados.
* **`notebooks/`** → Notebooks Jupyter com análises exploratórias e modelagem.
* **`src/`** → Scripts Python para tratamento de dados, treino e avaliação de modelos.
* **`models/`** → Modelos treinados salvos para reutilização.

## 📊 Objetivos do Projeto

1. Entender o comportamento dos atrasos em voos.
2. Identificar variáveis mais relevantes para previsão.
3. Construir modelos preditivos para estimar se um voo atrasará.
4. Avaliar e comparar o desempenho entre diferentes algoritmos.

## 🗂️ Base de Dados

O dataset contém informações sobre voos, como:

* Companhia aérea
* Aeroporto de origem e destino
* Data e horário de partida
* Distância
* Tempo previsto e tempo real
* Atraso (em minutos)

📌 **Fonte:** (adicione o link da base de dados se for pública)

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Bibliotecas:**

  * `pandas`
  * `numpy`
  * `matplotlib` / `seaborn`
  * `scikit-learn`

## 🔍 Metodologia

1. **Coleta e Limpeza de Dados** → Tratamento de valores ausentes, inconsistências e formatação de colunas.
2. **Análise Exploratória (EDA)** → Visualização de padrões e tendências.
3. **Modelagem Preditiva** → Algoritmos testados:

   * Regressão Logística
   * Árvore de Decisão
4. **Avaliação de Modelos** → Métricas utilizadas:

   * Acurácia
   * Precisão
   * Recall
   * F1-Score
   * Curva ROC e AUC

## 📈 Resultados

* Comparação de desempenho entre modelos.
* Insights relevantes sobre os fatores que mais influenciam atrasos.
* Identificação de possíveis melhorias para previsão.

## 🚀 Como Executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook ou script principal:

   ```bash
   jupyter notebook notebooks/analise_voos.ipynb
   ```

## 📌 Melhorias Futuras

* Testar modelos mais complexos como **Random Forest** e **XGBoost**.
* Implementar validação cruzada para evitar overfitting.
* Criar API para servir previsões em tempo real.
