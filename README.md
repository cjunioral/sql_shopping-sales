# 🛒 Análise de Dados com SQL + Pandas + Python – Shopping Sales Dataset
Este projeto tem como objetivo realizar uma análise completa de um conjunto de dados de vendas no varejo, utilizando SQL, Pandas, SQLite em memória, e visualização de dados com Matplotlib.
A proposta é demonstrar como integrar consultas SQL diretas a um DataFrame carregado no banco usando SQLAlchemy, combinando o melhor de ambos os mundos: linguagem SQL para análise tabular e Python para visualização e pós-processamento.

## 🚀 Tecnologias utilizadas

Python

Pandas

SQLAlchemy

SQLite (banco em memória)

Matplotlib

## 📦 Objetivos do projeto

Converter um DataFrame para uma tabela SQL usando df.to_sql()

Realizar consultas SQL reais diretamente no Python

Combinar resultados de SQL com gráficos em Matplotlib

Explorar padrões de comportamento dos clientes e itens vendidos

Criar visualizações claras para insights rápidos

## 📊 Análises realizadas
### ✔ 1. Estatísticas gerais dos clientes

Consulta SQL para obter:

Idade média

Gasto médio (USD)

Avaliação média dos produtos

### ✔ 2. Total de assinaturas (Subscription Status)

Contagem dos clientes com e sem assinatura, agrupando por status.

### ✔ 3. Itens únicos e mais vendidos

Listagem de todos os itens existentes no dataset

Contagem das vendas por item, ordenando do menor para o maior

Gráfico horizontal mostrando a quantidade de vendas por item

### ✔ 4. Faturamento total por categoria

Soma total do valor vendido para cada categoria

Ranking das categorias que mais faturam

Gráfico de barras mostrando o valor total em USD

### ✔ 5. Maiores compras dentro da categoria "Clothing"

Consulta SQL com MAX() para identificar a compra de maior valor nessa categoria.

### ✔ 6. Vendas por categoria e estação do ano

Agrupamento duplo (Category × Season) mostrando o total vendido — útil para entender sazonalidade.

### ✔ 7. Produtos com avaliação máxima (5 estrelas)

Filtro SQL para identificar os itens com melhor avaliação.

### ✔ 8. Média de gasto por gênero

Cálculo do ticket médio dos clientes por gênero

Gráfico comparativo (bar chart)

### ✔ 9. Total de compras por tamanho (Size)

Contagem dos tamanhos vendidos

Gráfico horizontal mostrando o total por tamanho

## 📈 Visualizações geradas

Gráficos de barras e barras horizontais (bar / barh)

Títulos claros para cada gráfico

Cores personalizadas para melhor leitura

Integração do resultado das queries SQL com Matplotlib
