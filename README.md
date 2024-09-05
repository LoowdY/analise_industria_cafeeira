# Análise da Indústria Cafeeira

## Descrição

Este projeto realiza uma análise detalhada dos dados de vendas da indústria cafeeira. O objetivo é fornecer insights sobre as vendas de diferentes tipos de café, preferências de pagamento dos clientes e padrões temporais das vendas. Os dados analisados incluem informações sobre o valor das vendas, método de pagamento, tipo de café e o momento da transação.

## Estrutura dos Dados

O dataset contém as seguintes colunas:

- **date**: Data da transação.
- **datetime**: Data e hora da transação.
- **cash_type**: Tipo de pagamento (por exemplo, "card").
- **card**: Identificador do cartão utilizado para a transação.
- **money**: Valor da venda (em unidades monetárias).
- **coffee_name**: Nome do tipo de café vendido.

## Análise Realizada

A análise dos dados incluiu as seguintes etapas:

1. **Distribuição dos Valores de Vendas**
   - Foi gerado um histograma para visualizar a distribuição dos valores de venda. Isso ajuda a entender a faixa de valores mais comuns e a frequência de cada intervalo.

2. **Resumo Estatístico dos Valores de Venda**
   - Estatísticas descritivas foram calculadas, incluindo média, mediana e desvio padrão, para fornecer uma visão geral dos valores de venda.

3. **Análise dos Tipos de Pagamento**
   - A distribuição dos métodos de pagamento foi analisada para identificar preferências dos clientes em relação ao pagamento.

4. **Análise por Nome do Café**
   - Foi examinada a frequência de vendas de diferentes tipos de café para entender quais produtos são mais populares.

5. **Análise Temporal**
   - As vendas foram analisadas ao longo do tempo para identificar padrões e tendências diárias ou mensais.

6. **Tratamento de Valores Nulos**
   - Valores nulos na coluna `money` foram identificados e tratados para garantir a integridade da análise.

## Insights Obtidos

- **Distribuição dos Valores de Vendas:** A análise revelou [insira aqui um resumo dos principais achados sobre a distribuição dos valores de venda].
- **Estatísticas Descritivas:** A média dos valores de venda é [valor], com uma mediana de [valor] e um desvio padrão de [valor]. Isso indica [insira interpretação].
- **Métodos de Pagamento:** A maioria das transações é realizada por [tipo de pagamento]. Isso pode indicar [insira interpretação].
- **Tipos de Café:** Os cafés mais vendidos são [tipos de café]. Esse dado sugere que [insira interpretação].
- **Padrões Temporais:** As vendas aumentam [ou diminuem] durante [insira período]. Esse padrão pode ser útil para [insira interpretação].
- **Tratamento de Valores Nulos:** Valores nulos foram tratados substituindo-os pela média dos valores de venda, garantindo dados mais completos.

## Gráficos

Os seguintes gráficos foram gerados para visualizar os dados:

- **Histograma da Distribuição dos Valores de Vendas:** Mostra a frequência dos valores de venda.
  
  ![Histograma](path/to/histograma.png)

- **Distribuição dos Tipos de Pagamento:** Gráfico de barras mostrando a distribuição dos métodos de pagamento.

  ![Distribuição dos Tipos de Pagamento](path/to/distribuicao_pagamento.png)

- **Frequência dos Tipos de Café:** Gráfico de barras mostrando a popularidade dos diferentes tipos de café.

  ![Frequência dos Tipos de Café](path/to/frequencia_cafe.png)

- **Tendências Temporais:** Gráfico mostrando as vendas ao longo do tempo.

  ![Tendências Temporais](path/to/tendencias_temporais.png)

## Conclusão

A análise dos dados fornece uma visão detalhada das vendas na indústria cafeeira, revelando padrões importantes sobre os valores das vendas, preferências dos clientes e popularidade dos produtos. Esses insights podem ser usados para ajustar estratégias de marketing, otimizar o estoque e melhorar a compreensão das preferências dos clientes.

## Como Executar

Para reproduzir esta análise, clone este repositório e execute o script `analise_industria_cafeeira.py`. Certifique-se de ter as seguintes bibliotecas instaladas:

- pandas
- matplotlib
- seaborn (opcional para gráficos adicionais)
- numpy

```bash
pip install pandas matplotlib seaborn numpy
