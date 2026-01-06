# Análise de Faturamento por Canal de Venda

## Contexto
Este projeto tem como objetivo analisar o desempenho de vendas por canal (Online vs Loja Física) a partir de dados transacionais, identificando os principais drivers de faturamento e orientações estratégicas para o negócio.

## Metodologia
- Leitura e validação do dataset (`vendas.csv`)
- Padronização dos nomes das colunas
- Cálculo do faturamento total (`quantidade × preço_unitário`)
- Agregação do faturamento por canal de venda
- Visualização gráfica para comparação de desempenho

## Principais Insights
- O **canal online concentra o maior faturamento total**.
- Esse desempenho é impulsionado principalmente pelo **maior volume de vendas**, e não por um ticket médio superior.
- O dado indica que **conveniência e acessibilidade** são fatores determinantes no comportamento do cliente.

## Recomendações de Negócio
- Priorizar estratégias de **aumento de conversão no canal online**.
- Focar em **eficiência operacional e logística** para sustentar escala.
- Reduzir custo por pedido antes de buscar aumento agressivo de ticket médio.

## Ferramentas Utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Estrutura do Projeto
analise-vendas-empresa/
│
├── data/           # Dataset utilizado
├── notebooks/      # Análises exploratórias
├── src/            # Scripts auxiliares
├── powerbi/        # Dashboards (etapa futura)
├── README.md
└── requirements.txt

