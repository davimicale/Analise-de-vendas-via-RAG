# Geração Aumentada por Recuperação Aplicada à Análise de Vendas: Comparação de Categorias de Produtos e Períodos

Com o crescimento do comércio eletrônico, decidi desenvolver uma solução inteligente que ajuda a interpretar e comparar o desempenho de produtos vendidos em diferentes períodos e categorias.

Minha proposta integra:

 - Entrada em linguagem natural

 - Geração de embeddings (com all-MiniLM-L6-v2)

 - Busca vetorial via FAISS

 - Geração textual automática com o modelo FLAN-T5

 - Visualizações com gráficos interativos (barras e pizza)

Os usuários podem digitar perguntas como “celulares vendidos no verão e inverno?” ou “compare o desempenho de vendas entre celulares e TVs”, e recebem respostas interpretativas com métricas como receita, ticket médio, avaliação e descontos.

O diferencial? Unir técnicas avançadas de NLP com dados simulados de vendas da Amazon e aplicar RAG para gerar análises automatizadas — acessíveis mesmo para quem não tem conhecimento técnico.

O projeto mostra como LLMs podem ser usados não só para responder perguntas, mas também para gerar insights de negócios, democratizando o acesso à inteligência analítica no e-commerce.

Agradeço ao meu orientador, à banca e a todos que apoiaram essa jornada!

## Análise por Período: “TV camera sold in spring and winter”

### Tabela 1 – Métricas de desempenho para “TV camera” em Spring e Winter:

| Período | Total de Vendas | Receita Estimada | Ticket Médio | Desconto Médio (%) | Avaliação Média |
|---------|------------------|------------------|---------------|---------------------|------------------|
| Spring  | 2,655            | $6,001,792       | $2,260        | 59.5                | 4.1              |
| Winter  | 1,003            | $1,817,607       | $1,812        | 68.09               | 4.08             |


### O texto gerado pelo modelo FLAN-T5 (RAG) foi o seguinte:

_"Total sales for the period was 2655 compared to 1003 in terms of revenue and discount. The average ticket price was 1817607.00 and the average discount was 68.09%."_

### Gráficos Períodos:

<imagem>

## Comparação entre Categorias: “Difference in sales between phone and tv”

### Tabela 2 – Comparação de métricas entre as categorias “Phone” e “TV”

| Categoria | Total de Vendas | Receita Estimada | Ticket Médio | Desconto Médio (%) | Avaliação Média |
|-----------|------------------|------------------|---------------|---------------------|------------------|
| TV        | 14,875           | $27,860,683      | $1,872        | 48.16               | 4.2              |
| Phone     | 11,605           | $10,597,671      | $913.19       | 64.08               | 3.89             |


### A resposta textual RAG foi:
 
 _"Total sales for the category are 14875, revenue is 27860683.00, discount is 48.16%, average rating is 4.20."_

 ### Gráficos Categoria:

<imagem>
