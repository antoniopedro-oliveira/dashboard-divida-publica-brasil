# 📊 Dashboard - Dívida Pública e Indicadores Econômicos do Brasil

> **Projeto para fins de aprendizado e portfólio.** Análise e visualização de dados econômicos utilizando o Power BI e consumo direto de APIs públicas.

---

## 🔗 Acesse o Relatório Interativo

👉 **[Clique aqui para acessar o Dashboard ao vivo no Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiNmZlZWFmODEtZDU4Yi00M2E4LWIwOGMtMGMwZjVjN2Q4M2QyIiwidCI6IjNlMjllMDhjLTMwODUtNDM2My1hYTkxLTE3MTNkZGE5NDM4YSJ9)**

---

## 📌 Sobre o Projeto
Este painel interativo foi desenvolvido com o objetivo de analisar a evolução da dívida pública e indicadores econômicos (como o PIB) no Brasil. 

A solução se conecta diretamente às fontes oficiais do governo, realizando a extração, transformação e carga (ETL) automatizada sem a necessidade de arquivos intermediários estáticos (Excel ou CSV).

---

## 🌐 APIs e Fontes de Dados Utilizadas
* **Banco Central do Brasil (BACEN):** Consumo via API OData/SGS para obtenção de séries temporais financeiras e econômicas.
* **IBGE:** Consumo via API pública para dados demográficos e regionais de apoio.

---

## 🛠️ Tecnologias
* **Power BI Desktop:** Modelagem de dados, medidas em DAX e construção visual.
* **Power Query (Linguagem M):** Requisições HTTP às APIs REST, tratamento de payloads JSON e limpeza de dados.
* **Power BI Service:** Publicação e disponibilização em nuvem.

---

## 🖥️ Visualização Incorporada

<iframe title="DIVIDA PUBLICA BII" width="100%" height="541.25" src="https://app.powerbi.com/view?r=eyJrIjoiNmZlZWFmODEtZDU4Yi00M2E4LWIwOGMtMGMwZjVjN2Q4M2QyIiwidCI6IjNlMjllMDhjLTMwODUtNDM2My1hYTkxLTE3MTNkZGE5NDM4YSJ9" frameborder="0" allowFullScreen="true"></iframe>

---

## 📁 Estrutura do Repositório
* `DIVIDA PÚBLICA BII.pbix`: Arquivo fonte do Power BI contendo o modelo de dados, rotinas de ETL em Power Query e os relatórios.
* `README.md`: Documentação completa do projeto.
