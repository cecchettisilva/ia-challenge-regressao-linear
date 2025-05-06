# Desafio de Regressão Linear

## Objetivo

Desafio de regressão linear do curso "Desenvolvimento de IA" da Rockeseat.
O objetivo deste projeto é analisar dados de irrigação para entender a relação entre o tempo de irrigação e a área efetivamente irrigada. Utilizamos um modelo de regressão linear para prever a área irrigada com base nas horas de irrigação, otimizando assim os recursos hídricos da fazenda.

## Estrutura do Projeto

- **dados_de_irrigacao.csv**: Arquivo contendo os dados de entrada para análise.
- **ia-challenge-regressao-linear.ipynb**: Notebook principal com o código e análises realizadas.
- **Pipfile** e **Pipfile.lock**: Arquivos para gerenciamento de dependências do projeto.

## Instalação

1. Certifique-se de ter o Python 3.8 ou superior instalado.
2. Instale o gerenciador de pacotes `pipenv` com o comando:
   ```bash
   pip install pipenv
   ```
3. Navegue até o diretório do projeto e instale as dependências com:
   ```bash
   pipenv install <nome_da_biblioteca>
   ```
4. Ative o ambiente virtual:
   ```bash
   pipenv shell
   ```

## Execução

1. Abra o arquivo `ia-challenge-regressao-linear.ipynb` em um ambiente compatível com Jupyter Notebook, como o VS Code ou Jupyter Lab.
2. Execute os blocos de código sequencialmente para reproduzir a análise e os resultados.

## Etapas do Projeto

### 1. Importação de Bibliotecas
- Importamos bibliotecas como `pandas`, `scikit-learn`, `seaborn` e `matplotlib` para manipulação de dados, visualização e construção do modelo.

### 2. Carregamento e Visualização dos Dados
- Carregamos os dados do arquivo CSV e realizamos uma inspeção inicial para entender a estrutura e verificar a presença de valores nulos.

### 3. Análise Exploratória dos Dados (EDA)
- Calculamos estatísticas descritivas e criamos gráficos de dispersão e mapas de calor para analisar a correlação entre as variáveis.

### 4. Construção do Modelo de Regressão Linear
- Dividimos os dados em conjuntos de treino e teste.
- Treinamos um modelo de regressão linear para prever a área irrigada com base nas horas de irrigação.
- Imprimimos a equação da reta obtida pelo modelo.

### 5. Avaliação do Modelo
- Avaliamos o desempenho do modelo utilizando métricas como MSE (Erro Quadrático Médio) e MAE (Erro Absoluto Médio).
- Visualizamos os resultados reais e preditos em gráficos.

### 6. Análise de Resíduos
- Calculamos os resíduos do modelo e verificamos sua normalidade utilizando testes estatísticos e gráficos QQ-Plot.

### 7. Predições de Exemplo
- Utilizamos o modelo para prever a área irrigada para diferentes valores de horas de irrigação.

## Conclusão

Este projeto demonstrou como a regressão linear pode ser utilizada para modelar relações entre variáveis e otimizar processos agrícolas. A análise de resíduos e as métricas de desempenho indicaram que o modelo é adequado para prever a área irrigada com base nas horas de irrigação.