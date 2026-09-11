
<img width="1183" height="670" alt="DASHBOARD DIVIDA PUBLICA POWER BI" src="https://github.com/user-attachments/assets/4729e714-1900-41e6-815b-5cce5c44f604" />


---

# 📊 Dashboard - Dívida Pública e Indicadores Econômicos do Brasil

> **Projeto para fins de aprendizado e portfólio.** Análise e visualização de dados econômicos utilizando o Power BI e consumo direto de APIs públicas do Banco Central (BACEN) e IBGE.

---

## 🔗 Acesse o Relatório Interativo

👉 **[Clique aqui para acessar o Dashboard ao vivo no Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiNmZlZWFmODEtZDU4Yi00M2E4LWIwOGMtMGMwZjVjN2Q4M2QyIiwidCI6IjNlMjllMDhjLTMwODUtNDM2My1hYTkxLTE3MTNkZGE5NDM4YSJ9)**

---

## 📌 Sobre o Projeto
Este painel interativo foi desenvolvido com o objetivo de analisar a evolução da dívida pública e indicadores econômicos (como o PIB) no Brasil. 

A solução se conecta diretamente às fontes oficiais do governo, realizando a extração, transformação e carga (ETL) automatizada sem a necessidade de arquivos intermediários estáticos (Excel ou CSV).

---

## 🌐 APIs e Fontes de Dados Utilizadas
* **Banco Central do Brasil (BACEN):** Consumo via API OData/SGS para obtenção de séries temporais financeiras e econômicas da dívida pública.
* **IBGE:** Consumo via API pública para dados econômicos e demográficos de apoio.

---

## 🛠️ Tecnologias
* **Power BI Desktop:** Modelagem de dados, medidas em DAX e construção do painel visual.
* **Power Query (Linguagem M):** Requisições HTTP às APIs REST, tratamento de payloads JSON e limpeza de dados.
* **Power BI Service:** Publicação e disponibilização em nuvem.

---

## 📁 Estrutura do Repositório
* `DIVIDA PÚBLICA BII.pbix`: Arquivo fonte do Power BI contendo o modelo de dados, rotinas de ETL em Power Query e os relatórios.
* `README.md`: Documentação completa do projeto.
