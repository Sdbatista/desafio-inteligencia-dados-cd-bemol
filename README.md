# 📦 Desafio Técnico – Inteligência de Dados no CD Bemol  
**Autor:** Mauro Batista de Souza  
**Data de Início:** 19/05/2025  
**Ambiente:** Databricks (PySpark)

---

## 🎯 Objetivo do Projeto

Este projeto tem como finalidade propor uma solução para melhorar a **visibilidade operacional** no Centro de Distribuição da Bemol, com foco nos processos de **separação (picking)** e **expedição** de pedidos.

---

## 🛠️ Stack Utilizada

- **Plataforma:** Databricks
- **Linguagem:** PySpark
- **Visualização:** display(), gráficos interativos (próximas etapas)
- **Armazenamento de arquivos:** DBFS (`dbfs:/FileStore/tables/`)
- **Versionamento:** Git + GitHub

---

## 📁 Estrutura dos Dados

| Arquivo               | Descrição                                        |
|------------------------|--------------------------------------------------|
| `pedidos.csv`          | Identificação dos pedidos e datas de criação     |
| `itens_pedido.csv`     | Itens incluídos em cada pedido                   |
| `log_separacao.csv`    | Registro de início/fim da separação por item     |
| `log_expedicao.csv`    | Registro da preparação e envio dos pedidos       |

---

## ✅ Etapas do Projeto

### 1. Upload e leitura dos arquivos CSV no DBFS
- Upload via notebook do Databricks.
- Leitura com `spark.read.option(...).csv(...)`.

### 2. Cálculo de KPIs – Separação
- **Tempo médio de separação por pedido**
- **Taxa de precisão da separação** (`status = Concluído`)

### 3. Integração com GitHub
- Repositório público criado para versionamento e acompanhamento
- Documentação completa em Markdown

---

## 📈 Próximas Etapas

- Cálculo dos KPIs de **expedição**:
  - Tempo médio até carregamento
  - Taxa de expedição no prazo
- Criação de **dashboard interativo** (Streamlit ou Power BI)
- Implementação de **IA para geração de insights**
- Roadmap estratégico da solução para o CD

---

## 🧠 Insight

> *“A inteligência de dados é o que transforma operações em decisões.”*

---

## 📌 Repositório mantido por [@Sdbatista](https://github.com/Sdbatista)
