# 📊 Xbox Game Pass Subscriptions — Sales Dashboard

> Projeto desenvolvido durante o Bootcamp **TOTVS — Fundamentos de Engenharia de Dados e Machine Learning** na plataforma [DIO](https://www.dio.me/).

---

## 🎯 Objetivo

O objetivo deste desafio é criar um **dashboard de vendas**, com foco na organização e visualização de dados. A proposta é transformar dados brutos em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões baseadas em dados.

---

## 📁 Estrutura do Arquivo

O projeto é composto por uma planilha Excel (`.xlsx`) com quatro abas organizadas da seguinte forma:

| Aba | Descrição |
|---|---|
| `Assets` | Paleta de cores, logotipos e ícones utilizados no dashboard |
| `Bases` | Base de dados bruta com informações dos assinantes |
| `Cálculos` | Análises e perguntas de negócio respondidas via fórmulas |
| `Dashboard` | Visualização final com os principais indicadores de vendas |

---

## 🗂️ Sobre os Dados

A base de dados (`Bases`) contém informações de assinantes do Xbox Game Pass, com os seguintes campos:

- **Subscriber ID** — Identificador único do assinante
- **Name** — Nome do assinante
- **Plan** — Plano contratado (`Core`, `Standard` ou `Ultimate`)
- **Start Date** — Data de início da assinatura
- **Auto Renewal** — Indica se a renovação automática está ativa (`Yes` / `No`)
- **Subscription Price** — Preço base da assinatura
- **Subscription Type** — Tipo de periodicidade (`Monthly`, `Quarterly` ou `Annual`)
- **EA Play Season Pass** — Indica se o assinante possui o EA Play Season Pass
- **EA Play Season Pass Price** — Valor do EA Play Season Pass
- **Minecraft Season Pass** — Indica se o assinante possui o Minecraft Season Pass
- **Minecraft Season Pass Price** — Valor do Minecraft Season Pass
- **Coupon Value** — Valor de desconto aplicado via cupom
- **Total Value** — Valor total da assinatura com todos os agregados

---

## 💡 Perguntas de Negócio

A aba `Cálculos` responde às seguintes perguntas de negócio:

1. **Qual o faturamento total de vendas de planos anuais** (contendo todas as assinaturas agregadas)?
2. **Qual o faturamento total de vendas de planos anuais**, separado por **com** e **sem** renovação automática?

---

## 📈 Dashboard

O dashboard final (`Dashboard`) apresenta uma visão consolidada das vendas de assinaturas do **Xbox Game Pass**, com indicadores visuais baseados nas análises realizadas na aba de cálculos.

A identidade visual segue a paleta de cores oficial do Xbox:

| Cor | Uso |
|---|---|
| `#9BC848` / `#22C55E` | Cores principais (Xbox Green) |
| `#2AE6B1` / `#5BF6A8` | Menus e destaques |
| `#E8E6E9` | Zona de valores negativos / neutros |

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel** — Construção da base de dados, cálculos e dashboard
- **Fórmulas Excel** — Para responder às perguntas de negócio (SOMASE, SOMASES, etc.)
- **Gráficos e Formatação Condicional** — Para visualização dos dados no dashboard

---

## 🚀 Como Utilizar

1. Faça o download do arquivo `DIO_Project.xlsx`
2. Abra no **Microsoft Excel** (recomendado) ou Google Sheets
3. Navegue pelas abas na seguinte ordem:
   - `Bases` → para explorar os dados brutos
   - `Cálculos` → para entender as análises realizadas
   - `Dashboard` → para visualizar os resultados finais
4. A aba `Assets` contém os recursos visuais utilizados na construção do dashboard

---

## 📚 Bootcamp

| | |
|---|---|
| **Plataforma** | [DIO — Digital Innovation One](https://www.dio.me/) |
| **Bootcamp** | TOTVS — Fundamentos de Engenharia de Dados e Machine Learning |
| **Desafio** | Criação de Dashboard de Vendas no Excel |
