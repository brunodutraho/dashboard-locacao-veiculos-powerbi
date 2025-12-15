# 🚗 Dashboard de Locação de Veículos – Power BI

Este projeto apresenta um dashboard completo desenvolvido em **Power BI** para análise e acompanhamento de uma empresa de **locação de veículos**.  
O objetivo é fornecer uma visão clara e estratégica dos principais indicadores do negócio, facilitando a tomada de decisão com base em dados reais.

---

## 🖼️ Visualizações do Dashboard

Abaixo estão as principais páginas do dashboard, organizadas na ordem correta:

---

### 📌 1. Capa do Projeto
![Capa do Dashboard](./imagens/capa.png)

---

### 🚗 2. Dashboard – Locação de Veículos
![Dashboard Locação de Veículos](./imagens/locacao-veiculos.png)

---

### 👥 3. Dashboard – Clientes
![Dashboard Clientes](./imagens/clientes.png)

---

### 📊 4. Dashboard – Visão Geral
![Dashboard Geral](./imagens/geral.png)

---

## 🎯 Objetivo do Dashboard

O dashboard foi construído para responder perguntas essenciais do negócio, como:

- Qual é o **faturamento total** dos últimos anos?
- Qual é a **média de KM percorrido por veículo**?
- Quais são as **placas que mais consumiram o serviço**?
- Quantos **clientes ativos** a empresa possui?
- Qual foi o **maior faturamento por ano**?
- Qual é o **ticket médio por cliente**?
- Como o faturamento se distribui por **dia da semana, modelo, marca e situação cadastral**?

---

## 📊 Principais Indicadores

- **Total de Clientes:** 30  
- **Faturamento Total:** R$ 81.434,00  
- **Ticket Médio:** R$ 5.189,27  
- **Média de KM percorridos:** 1.357,23  
- **Top 3 placas com maior consumo**  
- **Faturamento por ano**  
- **% de faturamento por ano**  
- **Faturamento por dia da semana**  
- **Clientes cadastrados x não cadastrados**  
- **Resumo de consumo por cliente, placa, marca, ano e situação cadastral**

---

## 🧱 Estrutura dos Dados

### **CLIENTES.xlsx**
- ID  
- Nome  
- Cargo  
- Salário  
- Cidade  

### **LOCAÇÃO DE VEICULOS.xlsx (Rastreador)**
- ID_CLIENTE  
- Marca  
- Modelo  
- Placa  
- KM Percorrido  
- Ano  
- Valor por KM  
- Situação cadastral  
- Campos auxiliares e linhas com erro tratadas no Power Query  

---

## 🧮 Modelagem e Lógica de Negócio

A modelagem foi construída conectando:

- **Tabela de Clientes**
- **Tabela de Rastreamento de Locação**

Principais cálculos:

- **Faturamento:**  
  `Faturamento = KILOMETRO_PERCORRIDO * VALOR POR KM`

- **Ticket Médio:**  
  `Ticket Médio = Faturamento Total / Total de Clientes`

- **Média de KM:**  
  média de `KILOMETRO_PERCORRIDO` por veículo

Segmentações utilizadas:

- Ano  
- Modelo  
- Marca  
- Situação cadastral  
- Dia da semana  

---

## 📈 Visuais do Dashboard

### ✅ **Visão Gerencial**
- Cards com indicadores principais  
- Faturamento por ano  
- % de participação por ano  
- Faturamento por dia da semana  

### ✅ **Controle de Cadastro**
- Clientes cadastrados x não cadastrados  
- Tabela com nome, placa, marca e faturamento  
- Indicadores de status (ativo/inativo)  

### ✅ **Previsão**
- Gráfico de linha com evolução histórica  
- Projeção de faturamento para período futuro  

---

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop**  
- **Power Query** (tratamento e limpeza de dados)  
- **DAX** (medidas e cálculos)  
- **Excel** (fonte de dados)

---

## 🔗 Visualização Online

Acesse o dashboard diretamente pela web:

👉 **https://l1nq.com/dashboard-locacao-veiculos-brunoanalytics**

---

## 🚀 Como Abrir o Projeto

1. Baixe o arquivo `.pbix` deste repositório  
2. Abra no **Power BI Desktop**  
3. Ajuste os caminhos das fontes de dados, se necessário  
4. Atualize o modelo para carregar todos os indicadores  

---

## 💡 Aprendizados e Destaques

- Tratamento de dados com erros e inconsistências  
- Criação de indicadores de negócio  
- Modelagem simples e eficiente  
- Construção de visuais claros e orientados à gestão  
- Projeção de faturamento com base no histórico  

---

## 👨‍💻 Autor

**Bruno Dutra**  
Analista de Dados | Power BI, SQL, Excel e Python  
Portfólio: *[adicione seu link aqui]*
