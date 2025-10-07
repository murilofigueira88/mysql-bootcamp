# 🧠 Bootcamp Dio — Queries e Modelagem de Banco de Dados

Este repositório contém os scripts SQL e o modelo lógico desenvolvidos durante o **Bootcamp Dio**, abordando desde a criação das tabelas até consultas complexas com `JOIN`, `GROUP BY` e `HAVING`.

---

## 🗂️ Estrutura do Projeto

- **EER Diagram** → Modelo visual do banco de dados (MySQL Workbench)  
- **queries.txt** → Contém os principais comandos SQL:
  - Criação de tabelas com chaves primárias e estrangeiras  
  - Inserts de dados de exemplo  
  - Consultas `SELECT` com filtros e ordenações  
  - Junções entre múltiplas tabelas  
  - Uso de funções agregadas e cláusulas `HAVING`

---

## 🧩 Tabelas Principais

- **clients** — Cadastro de clientes (PF e PJ)  
- **orders** — Registro de pedidos com status e código de rastreio  
- **payments** — Formas de pagamento associadas aos clientes  
- **product** — Catálogo de produtos  
- **supplier** — Fornecedores e seus produtos  
- **productorder / productsupplier / productseller** — Relações entre entidades  
- **storagelocation** — Controle de estoque e local de armazenamento  

SELECT * FROM clients;

