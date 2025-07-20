# 📊 Telemarketing Analysis App

Uma aplicação interativa desenvolvida com **Streamlit** para analisar dados de campanhas de marketing bancário. Permite o upload de arquivos, filtragem dinâmica, visualizações gráficas e exportação de resultados.

---

## 📌 Objetivo

O projeto visa fornecer uma ferramenta visual e interativa para análise de dados de campanhas de telemarketing bancário. Ele permite:

- Filtrar os dados com base em múltiplas características do cliente.
- Analisar a taxa de aceitação de propostas de marketing.
- Comparar a distribuição de respostas antes e depois dos filtros.
- Baixar os dados filtrados em formato Excel.

---

## 🧰 Tecnologias Utilizadas

- Python
- Streamlit
- Pandas
- Seaborn
- Matplotlib
- Pillow
- XlsxWriter

---

## 📁 Funcionalidades da Aplicação

### ✅ Upload de Arquivos

- Suporta arquivos `.csv` e `.xlsx`.
- Carrega os dados automaticamente na aplicação para visualização e análise.

### 🔎 Filtros Interativos

Os filtros disponíveis na barra lateral incluem:

- Faixa etária (via slider)
- Profissão
- Estado civil
- Situação de crédito ("default")
- Financiamento imobiliário
- Empréstimo pessoal
- Meio de contato (telefone, celular, etc.)
- Mês da campanha
- Dia da semana

Você pode aplicar múltiplos filtros simultaneamente.

### 📉 Tipos de Gráficos

- **Gráfico de Barras** ou **Gráfico de Pizza**, com seleção dinâmica
- Comparação da proporção de aceitação (`y`) antes e depois dos filtros aplicados

### 📥 Exportação de Dados

- Exporta os dados filtrados em **Excel**
- Exporta também as proporções de aceitação (`y`) para os dados brutos e filtrados

---

## 📷 Capturas de Tela

<img width="1905" height="895" alt="Captura de tela 2025-07-20 123316" src="https://github.com/user-attachments/assets/2be473cb-923b-4159-8a32-a17a2391665f" />


---

## 📊 Dataset Esperado

O app espera um dataset estruturado como o [conjunto de dados do UCI Bank Marketing](https://archive.ics.uci.edu/ml/datasets/bank+marketing), contendo colunas como:

* `age`
* `job`
* `marital`
* `default`
* `housing`
* `loan`
* `contact`
* `month`
* `day_of_week`
* `y` (resposta final da campanha)

---

## 📝 Observações

* Os dados brutos e os dados filtrados são comparados em tempo real.
* A interface é responsiva e intuitiva.
* O app foi projetado para permitir análises rápidas por equipes de marketing, ciência de dados ou gestão.`


## Acesso à aplicação

Acesse a aplicação [aqui](https://telemarketing-3cf0.onrender.com/)

