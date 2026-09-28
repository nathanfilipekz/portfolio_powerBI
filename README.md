# 📊 Portfólio Power BI — Dashboard de Vendas

Projeto de Business Intelligence desenvolvido no **Power BI Desktop**, com foco em análise de vendas e desempenho de equipe. O objetivo é mostrar a construção completa de um relatório: modelagem de dados, criação de medidas em DAX e visualização interativa.

> ⚠️ Todos os dados utilizados neste projeto são **fictícios**, criados apenas para fins de estudo e portfólio.

---

## 🖼️ Visão geral do dashboard

![Dashboard principal](dashboard.png)

---

## 🧩 Modelagem de dados

O modelo segue o padrão **Star Schema (esquema estrela)**, com uma tabela fato central ligada às tabelas de dimensão:

| Tabela | Tipo | Descrição |
|---|---|---|
| **Vendas** | Fato | Registros de vendas (valores, quantidades, datas) |
| **Calendário** | Dimensão | Tabela de datas para análises temporais |
| **Equipe** | Dimensão | Dados dos vendedores / equipe comercial |

![Modelo de dados](modelo.png)

---

## 📐 Medidas DAX

As métricas do relatório foram criadas com **medidas DAX**, organizadas no modelo para reaproveitamento em todos os visuais.

![Medidas DAX](medidas.png)

---

## 🔎 Drill-through

O relatório conta com páginas de **drill-through**, permitindo sair da visão geral e detalhar a análise por item específico (por exemplo, por vendedor), mantendo os filtros aplicados.

![Drill-through](drillthrough.png)

---

## 🛠️ Tecnologias e conceitos

- Power BI Desktop
- Power Query (tratamento e transformação de dados)
- Modelagem dimensional (Star Schema)
- DAX (medidas e cálculos)
- Tabela Calendário para inteligência de tempo
- Drill-through e interatividade entre visuais

---

## 👤 Autor

**Nathan Filipe Rosa de Souza**
Analista de Dados | SQL · Python · Power BI · Databricks
