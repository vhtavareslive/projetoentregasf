
# 📦 Projeto de Análise de Dados - Empresa de Delivery Center

Este projeto realiza uma análise exploratória e estatística de dados da empresa **Delivery Center**, uma plataforma de logística focada em shoppings centers de grandes capitais do Brasil. O objetivo é gerar insights úteis para os times de **Marketing**, **Pricing** e **Financeiro** da empresa.

## 📊 Objetivos

1. **Marketing**: Identificar os 20 entregadores com maior distância percorrida para aplicação de bônus, com base em tipo de profissional e modelo de locomoção.
2. **Pricing**: Analisar a distribuição da distância média percorrida por entregadores que usam moto, separados por estado.
3. **Financeiro (CFO)**: Calcular:
   - Receita média e total por tipo de pedido (Food vs Good)
   - Receita média e total por estado
4. **Bônus Funcionários**: Estimar o valor de bônus por funcionário, considerando:
   - Gasto fixo de R$ 5 por entrega
   - Receita de 15% sobre cada entrega
   - 20% do lucro distribuído entre os 2.000 funcionários

## 📁 Dados Utilizados

Os dados foram obtidos do [Kaggle - Brazilian Delivery Center](https://www.kaggle.com/datasets/nosbielcs/brazilian-delivery-center/), compostos por 7 datasets:

- `channels.csv` – Canais de venda
- `deliveries.csv` – Detalhes das entregas
- `drivers.csv` – Entregadores cadastrados
- `hubs.csv` – Hubs logísticos
- `orders.csv` – Pedidos realizados
- `payments.csv` – Pagamentos feitos
- `stores.csv` – Lojistas parceiros

## 🛠️ Ferramentas Utilizadas

- Python
- Jupyter Notebook
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
