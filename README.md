# Regressão Linear - Análise de Dados com `mt_cars`

Este projeto é uma análise estatística baseada no dataset `mt_cars`. O notebook realiza etapas de limpeza de dados, visualizações gráficas e ajustes de modelos de regressão linear utilizando bibliotecas populares de Python. 

## Objetivo
O objetivo do projeto é explorar a relação entre as variáveis contidas no dataset `mt_cars`, identificar correlações importantes e ajustar modelos de regressão para prever variáveis com base em outras.

## Estrutura do Projeto
O notebook está organizado nas seguintes seções:

### 1. Importação de Bibliotecas
- `pandas`, `numpy`, `matplotlib`, `seaborn`, entre outras, para manipulação de dados e criação de visualizações.

### 2. Carregamento e Limpeza de Dados
- O dataset `mt_cars` é carregado e manipulado, com remoção de colunas desnecessárias e criação de uma matriz de correlação para análise exploratória.

### 3. Visualização dos Dados
- Criação de mapas de calor (`heatmap`) para correlações e gráficos de dispersão para variáveis selecionadas.

### 4. Modelagem Estatística
- Ajuste de modelos de regressão linear usando a biblioteca `statsmodels`, incluindo a análise de variáveis preditoras como peso (`wt`), potência (`hp`) e outras.

### 5. Resultados e Interpretação
- Exibição de resultados, como coeficientes da regressão, e discussão sobre o impacto de diferentes variáveis no modelo ajustado.

## Requisitos
Certifique-se de que as seguintes dependências estejam instaladas:

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy

Use o comando abaixo para instalar as dependências necessárias:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

## Como Executar
1. Clone este repositório:

```bash
git clone https://github.com/Jhonathan-Ferroni/Regressao_Linear.git
```

2. Certifique-se de que o arquivo `mt_cars.csv` esteja no mesmo diretório do notebook.

3. Abra o arquivo `Regressao.ipynb` no Jupyter Notebook ou Google Colab.

4. Execute as células sequencialmente para reproduzir a análise.

## Dataset
O dataset `mt_cars` contém informações sobre especificações técnicas e desempenho de diferentes carros. Algumas variáveis presentes:

- `mpg`: Milhas por galão.
- `cyl`: Número de cilindros.
- `disp`: Deslocamento (polegadas cúbbicas).
- `hp`: Potência (cavalos de força).
- `wt`: Peso do carro (em milhares de libras).

## Resultados Esperados
Ao final da execução do notebook, espera-se obter:

- Uma matriz de correlação visualizada em forma de mapa de calor.
- Gráficos de dispersão destacando relações entre variáveis.
- Modelos de regressão com interpretação dos coeficientes.


Sinta-se à vontade para contribuir com melhorias ou abrir issues para relatar problemas! 😄

