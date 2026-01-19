# 🚗 Dashboard de Locação de Veículos — Power BI  
### Análise de Dados com foco em indicadores de negócio

Este projeto foi desenvolvido para demonstrar, de forma prática, minha atuação como **Analista de Dados**, aplicando **tratamento de dados, modelagem, criação de métricas e construção de dashboards em Power BI**.

A proposta é simples: transformar dados operacionais de uma empresa de **locação de veículos** em informações claras, úteis e acionáveis para apoiar decisões do dia a dia e análises estratégicas.

---

## 🖼️ Visualizações do Dashboard

### 📌 Capa do Projeto
![Capa do Dashboard](https://i.postimg.cc/htZGgpDc/capa-locacao-veiulos.png)

### 🚗 Locação de Veículos
![Dashboard Locação de Veículos](https://i.postimg.cc/3NZKqZSV/locacao-veiulos.png)

### 👥 Clientes
![Dashboard Clientes](https://i.postimg.cc/8CrTGGX6/clientes-locacao-veiulos.png)

### 📊 Visão Geral
![Dashboard Geral](https://i.postimg.cc/2yTDGS3z/geral-locacao-veiulos.png)

---

## 🎯 Objetivo do Projeto

Este dashboard foi criado para evidenciar:

- Capacidade de **transformar dados brutos em insights acionáveis**
- Domínio prático de **Power BI, Power Query, DAX e modelagem de dados**
- Entendimento de **indicadores de negócio** relevantes para a gestão
- Construção de **dashboards claros, intuitivos e profissionais**

O foco não está apenas no visual, mas na **leitura correta dos dados e no suporte à tomada de decisão**.

---

## 📊 Principais Indicadores

- **Faturamento Total:** R$ 81.434,00  
- **Total de Clientes:** 30  
- **Ticket Médio:** R$ 5.189,27  
- **Média de KM Percorrido:** 1.357,23  
- **Top 3 veículos com maior consumo**  
- **Faturamento por ano**  
- **Participação percentual por período**  
- **Faturamento por dia da semana**  
- **Clientes cadastrados x não cadastrados**  
- **Resumo de consumo por cliente, veículo, marca e situação cadastral**

Esses indicadores foram definidos com foco em **análises operacionais e estratégicas**.

---

## 🧱 Estrutura dos Dados

### CLIENTES.xlsx
Base com informações de identificação, cargo, salário e cidade.

### LOCACAO_DE_VEICULOS.xlsx
Base com dados de consumo, quilometragem, marca, modelo, placa, ano e situação cadastral.

Durante o processo foram aplicados:
- Limpeza de inconsistências  
- Padronização de tipos de dados  
- Criação de colunas calculadas  
- Remoção de registros inválidos  

---

## 🧮 Modelagem e Regras de Negócio

A modelagem conecta:
- **Tabela de Clientes**
- **Tabela de Locação de Veículos**

Principais métricas criadas:

- **Faturamento**  
  `KM Percorrido × Valor por KM`

- **Ticket Médio**  
  `Faturamento Total ÷ Total de Clientes`

- **Média de KM Percorrido**  
  Cálculo médio por veículo e cliente

Segmentações disponíveis:
- Ano  
- Marca  
- Modelo  
- Situação cadastral  
- Dia da semana  

---

## 🛠️ Tecnologias Utilizadas

- Power BI Desktop  
- Power Query (M)  
- DAX  
- Microsoft Excel  

---

## 🔗 Visualização Online

👉 https://app.powerbi.com/view?r=eyJrIjoiNWY1NzBkN2QtOTJjZC00MDEwLWE2ZjUtNTQwYmY3ZDkxM2FiIiwidCI6ImJkYjUwNDk5LWIyNmMtNDNjNS1iM2E1LTFiYTMxZDA4NmQzYiJ9

---

## 👤 Autor

**Bruno Dutra**  
Analista de Dados | Business Intelligence | Power BI | SQL  

- GitHub: https://github.com/brunodutraho  
- LinkedIn: https://www.linkedin.com/in/brunodutraho  
- Portfólio: https://bruno-dutra-portfolio.vercel.app  
