# 🍕 Pizza Sales Analysis

Este projeto realiza uma análise exploratória dos dados de vendas de pizzas, utilizando **Python**, **SQL (SQLite)** e visualizações gráficas. O objetivo é extrair insights relevantes de negócio, como pizzas mais vendidas, ticket médio, categorias com maior receita e padrões de consumo ao longo do tempo.

---

## Dataset

O arquivo `pizza_sales.csv` contém informações sobre pedidos feitos em uma pizzaria, incluindo nome da pizza, tamanho, categoria, data/hora do pedido, quantidade, preço e total por linha.

### Colunas disponíveis:
- `pizza_id`: identificador da linha de pedido
- `order_id`: código do pedido
- `pizza_name_id`: ID textual da pizza
- `pizza_name`: nome completo da pizza
- `pizza_size`: tamanho (S, M, L, XL, XXL)
- `pizza_category`: categoria (Classic, Chicken, Veggie, etc.)
- `pizza_ingredients`: lista de ingredientes
- `order_date`: data do pedido
- `order_time`: hora do pedido
- `quantity`: número de unidades vendidas
- `unit_price`: preço unitário
- `total_price`: valor total da linha

---

## Perguntas de Negócio Respondidas

Durante a análise exploratória, foram respondidas as seguintes perguntas com SQL:

1. Qual foi o total de receita gerada no período?
2. Qual foi o ticket médio por pedido?
3. Quais são as pizzas mais vendidas em quantidade?
4. Quais pizzas geraram mais receita?
5. Quais datas tiveram os maiores volumes de vendas?
6. Quais tamanhos de pizza foram mais vendidos?
7. Qual categoria de pizza gerou mais receita?
8. Em quais horários do dia ocorrem mais pedidos?
9. Quais são os ingredientes mais comuns nas pizzas mais populares?
10. Qual é a média de pizzas vendidas por pedido?

---

## Tecnologias Utilizadas

- Python 3.x
- Jupyter Notebook
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib / Seaborn *(opcional para gráficos)*

---

## Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/gubrandaods7/pizza-sales-analysis.git
cd pizza-sales-analysis
```
---

## Autor

**Gustavo Brandão**

📧 E-mail: gubrandaods@gmail.com  
🐙 GitHub: [github.com/gubrandaods7](https://github.com/gubrandaods7)  
🔗 LinkedIn: [linkedin.com/in/gustavo-brandao-0b7635197](https://www.linkedin.com/in/gustavo-brandao-0b7635197)

