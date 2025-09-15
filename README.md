# 📊 Análise de Dados de Vendas - Projeto Data Science

## 📖 Sobre o Projeto
Análise completa de dados de vendas internacionais com foco em segmentação de clientes, análise temporal e identificação de padrões de compra.

## 🎯 Objetivos
- Identificar países com maior potencial de vendas
- Segmentar clientes usando metodologia RFM
- Analisar tendências e sazonalidade nas vendas
- Gerar insights acionáveis para estratégia comercial

## 📊 Dataset
- **Fonte**: [Nome da fonte ou contexto]
- **Período**: Dezembro 2010 - Dezembro 2011
- **Registros**: [X] mil transações
- **Variáveis**: 8 colunas incluindo data, produto, quantidade, preço, país

## 🛠️ Tecnologias Utilizadas
- **Python 3.9+**
- **Pandas** - Manipulação de dados
- **Matplotlib/Seaborn** - Visualizações
- **Scikit-learn** - Análise estatística
- **Jupyter Notebook** - Análise iterativa

## 📈 Principais Descobertas

### 🌍 Análise Geográfica
- Reino Unido representa 82% do volume total de vendas
- 37 países identificados com padrões distintos de compra

### ⏰ Análise Temporal
- Forte sazonalidade em Dezembro/Janeiro (+40% de vendas)
- Tendência de crescimento ao longo de 2011

### 👥 Segmentação RFM
- **Melhores Clientes**: 15% dos clientes, 60% da receita
- **Clientes em Risco**: 12% precisam de ações de retenção
- **Novos Clientes**: 8% com alto potencial de crescimento

## 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/LuanRob/projeto_data_science.git

# Instale as dependências
pip install -r requirements.txt

# Execute os notebooks na ordem:
# 1. 01_eda.ipynb
# 2. 02_preprocessing.ipynb
# 3. 03_rfm_analysis.ipynb
# 4. 04_time_series.ipynb
