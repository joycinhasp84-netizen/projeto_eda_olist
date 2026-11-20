
# Análise Exploratória de Dados — Olist

## Sobre o projeto

Este projeto foi desenvolvido como atividade do curso de Analista de Dados II, utilizando Python para realizar uma Análise Exploratória de Dados (EDA) do e-commerce brasileiro Olist.

O objetivo é identificar padrões de vendas, comportamento dos pedidos, distribuição geográfica e desempenho das categorias de produtos.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Etapas do projeto

### 1. Contexto e objetivos
Definição do problema de negócio e das perguntas que orientam a análise.

### 2. Carregamento dos dados
Importação dos arquivos CSV e identificação das estruturas das bases.

### 3. Exploração inicial
Análise das dimensões, tipos de dados e características das variáveis.

### 4. Diagnóstico e limpeza dos dados
- Identificação de valores ausentes
- Verificação de duplicidades
- Análise de valores inconsistentes
- Investigação de outliers
- Tratamento das categorias não informadas
- Validação da integridade dos dados

### 5. Integração e análise dos dados
- Relacionamento entre pedidos, itens, produtos e clientes
- Criação de variáveis
- Cálculo dos indicadores de vendas
- Análise temporal e geográfica
- Análise por categorias de produtos

### 6. Visualização dos resultados
Construção de gráficos para identificar padrões e facilitar a interpretação dos dados.

### 7. Conclusões
Interpretação dos resultados obtidos e identificação dos principais padrões comerciais.

### 8. Validação final
Verificação da consistência das quantidades de registros e dos valores de vendas.

## Principais resultados

| Indicador | Resultado |
|---|---|
| Pedidos entregues | 96.478 |
| Registros de itens | 110.197 |
| Valor total das vendas (sem frete) | R$ 13.221.498,11 |
| Valor total dos fretes | R$ 2.198.275,64 |
| Ticket médio por pedido | R$ 137,04 |
| Estado com maior valor de vendas | São Paulo |
| Participação de São Paulo | 38,33% |
| Categoria líder | Beleza e Saúde |

## Principais visualizações

- Evolução mensal das vendas
- Ranking de vendas por estado
- Distribuição dos valores dos pedidos
- Ranking das 10 categorias com maior valor de vendas

## Base de dados

Os dados utilizados são públicos e estão disponíveis no Kaggle:

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Os arquivos CSV não foram incluídos neste repositório devido ao tamanho.

Para executar o projeto:

1. Baixe os dados no Kaggle.
2. Extraia os arquivos CSV.
3. Coloque os quatro arquivos utilizados na mesma pasta do notebook.
4. Abra o arquivo `projeto_eda_olist.ipynb`.
5. Execute as células na ordem apresentada.

## Validação final

O projeto passou por sete verificações automatizadas de consistência, incluindo quantidades de pedidos, itens e valores das vendas.

Todas as verificações foram aprovadas.

## Arquivo principal

[Visualizar o notebook do projeto](projeto_eda_olist.ipynb)
