1. Funções de Combinação e Mesclagem no Power BI:
   
a) Mesclar Tabelas (Merge):
•	Objetivo: Combinar duas tabelas com base em uma coluna comum.
•	Quando usar: Quando você precisa combinar dados de duas tabelas que têm uma relação um-para-um ou um-para-muitos (uma coluna compartilhada identifica os registros relacionados nas duas tabelas).
•	Exemplo: Você tem uma tabela de clientes e uma tabela de pedidos. Ambas as tabelas têm uma coluna "ID do Cliente". Ao usar a mesclagem, você pode juntar os dados dos clientes e dos pedidos correspondentes em uma única tabela.
•	Tipos de Mesclagem:
o	Inner Join: Retorna apenas as linhas que têm correspondência nas duas tabelas (interseção).
o	Left Outer Join: Retorna todas as linhas da tabela da esquerda (a primeira na mesclagem) e as correspondentes da tabela da direita. Linhas sem correspondência na tabela da direita serão incluídas com valores nulos.
o	Right Outer Join: Retorna todas as linhas da tabela da direita (a segunda na mesclagem) e as correspondentes da tabela da esquerda. Linhas sem correspondência na tabela da esquerda serão incluídas com valores nulos.
o	Full Outer Join: Retorna todas as linhas de ambas as tabelas, incluindo linhas que não têm correspondência na outra tabela.

b) Combinar Tabelas (Append):
•	Objetivo: Adicionar linhas de uma tabela ao final de outra tabela.
•	Quando usar: Quando você tem duas tabelas com a mesma estrutura (mesmas colunas) e deseja combiná-las em uma única tabela.
•	Exemplo: Você tem duas tabelas com dados de vendas para diferentes períodos (Janeiro e Fevereiro). Ao usar a combinação, você pode unir esses dados em uma única tabela para analisar as vendas do primeiro trimestre.

