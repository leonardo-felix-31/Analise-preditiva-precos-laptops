# 💻 Análise Preditiva de Preços de Laptops

## 📌 Descrição

Este projeto tem como objetivo **analisar e prever os preços de laptops** com base em suas especificações técnicas e marcas. A análise foi conduzida em três frentes principais:

- 🔍 **Análise de mercado**: Exploração de tendências de preços com base em marcas, modelos e configurações.
- 📊 **Importância das características**: Identificação de quais atributos (processador, RAM, armazenamento, etc.) mais influenciam no preço.
- 🤖 **Modelagem preditiva**: Construção de modelos de machine learning para prever o preço com base nas especificações.

O estudo combina **análise exploratória de dados (EDA)**, visualização gráfica e técnicas de regressão para obter insights valiosos sobre o mercado de tecnologia.



---

## 🔧 Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Linear Regression, Random Forest, MLPRegressor)
- Jupyter Notebook

---

## 🧪 Etapas do Projeto

1. **Coleta e limpeza de dados**
   - Leitura do arquivo `precos_pc.csv`
   - Verificação de valores ausentes e dados duplicados

2. **Análise exploratória**
   - Visualizações com gráficos de dispersão, boxplots, histogramas
   - Correlação entre variáveis

3. **Pré-processamento**
   - Label Encoding e Standard Scaler
   - Bin discretization para categorização

4. **Modelagem**
   - Regressão Linear
   - Random Forest Regressor
   - Multi-layer Perceptron Regressor

5. **Avaliação**
   - Métricas: MAE, MSE, RMSE, R²

---

## 📌 Resultados
- O modelo Random Forest Regressor teve melhor desempenho, com R² próximo de 0.92.
- Características como tipo de processador, quantidade de RAM e tipo de armazenamento mostraram ser os principais influenciadores de preço.
- A abordagem pode ser estendida para marketplaces ou sites de recomendação de produtos.

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto_PC.git
   cd projeto_PC
