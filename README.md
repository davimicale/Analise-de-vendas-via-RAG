# Geração Aumentada por Recuperação Aplicada à Análise de Vendas: Comparação de Categorias de Produtos e Períodos
Com o crescimento do comércio eletrônico e a necessidade de tomadas de decisão
 baseadas em dados, torna-se essencial o desenvolvimento de ferramentas inteligentes
 para análise de vendas. Neste trabalho, propõe-se uma proposta que combina técnicas
 de Processamento de Linguagem Natural (PLN), busca vetorial e geração automática
 de textos para interpretar e comparar o desempenho das vendas de produtos em dife
rentes períodos ou categorias. A proposta utiliza um conjunto de dados da Amazon,
 enriquecido manualmente com colunas de data e quantidade de vendas, permitindo o
 cálculo de métricas comerciais relevantes como receita estimada, ticket médio, avaliação
 média e percentual de desconto. Para encontrar produtos semelhantes, são gerados
 embeddings com o modelo all-MiniLM-L6-v2 e indexados com o banco vetorial FAISS.
 A partir disso, é aplicado o paradigma RAG (Retrieval-Augmented Generation), onde
 um modelo FLAN-T5 gera respostas textuais interpretativas com base em dados re
cuperados. Complementarmente, gráficos do tipo barras e pizza são utilizados para
 visualizar os resultados. Os testes realizados demonstram que a proposta é capaz de
 lidar com diferentes tipos de consultas, gerando respostas informativas e acessíveis.
 Como contribuição, a proposta se destaca por integrar componentes avançados de
 inteligêncial artificial em um fluxo coeso, demonstrando o potencial de modelos grandes
 de linguagem aplicados a contextos de vendas.
