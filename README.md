# Imersão de Dados com Python

## Descrição

Este projeto faz parte de uma imersão no universo de dados utilizando Python, com foco em análise salarial na área de dados. A base utilizada é um dataset do Kaggle sobre salários em profissões de análise de dados.

## Objetivo

Explorar e visualizar tendências salariais na área de dados, facilitando a análise para profissionais e interessados no setor.

## Sobre o Projeto

- **Análise de Dados:** Utiliza um DataFrame extraído do Kaggle, contendo informações sobre salários, cargos, senioridade, tipo de contrato, tamanho da empresa, entre outros.
- **Visualização Interativa:** O dashboard foi desenvolvido com Streamlit e Plotly, permitindo a exploração dos dados por meio de gráficos interativos e filtros dinâmicos.
- **Principais Métricas:** O painel exibe KPIs como salário médio, salário máximo, total de registros e cargo mais frequente.
- **Gráficos:** Inclui visualizações como distribuição de salários, comparação entre cargos, proporção de trabalho remoto e mapa de salários por país para cientistas de dados.

## Ferramentas Utilizadas

- Python
- Pandas
- Streamlit
- Plotly

## Como Executar

1. Instale as dependências:
   ```
   pip install -r src/requirements.txt
   ```
2. Execute o dashboard:
   ```
   streamlit run src/app.py
   ```
