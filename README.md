# 🛒 Superstore Analytics

Projeto de Análise de Dados desenvolvido a partir do dataset Superstore, com o objetivo de explorar vendas, lucro, clientes, produtos, categorias, regiões e comportamento comercial.

O projeto começou como um desafio para realizar uma análise completa utilizando exclusivamente **Excel 2016**. Após a conclusão da análise, a mesma base de dados foi utilizada para reproduzir e aprofundar os estudos utilizando **Python, Pandas, Matplotlib e Seaborn**.

🌐 **Dataset utilizado:** [Superstore — Kaggle](https://www.kaggle.com/datasets)

---

## 📌 Sobre o projeto

O Superstore Analytics foi desenvolvido como um projeto prático de aprendizado em Análise de Dados, utilizando uma base de vendas contendo informações sobre pedidos, produtos, clientes, categorias, regiões, descontos e resultados financeiros.

O projeto teve duas etapas principais:

### 📊 Etapa 1 — Excel 2016

A análise inicial foi realizada utilizando exclusivamente recursos disponíveis no Microsoft Excel 2016, incluindo:

- Tabelas Dinâmicas
- Gráficos Dinâmicos
- Segmentações de Dados
- Fórmulas
- Indicadores
- Análise temporal
- Análise de vendas e lucro
- Dashboard interativo

O objetivo dessa etapa foi entender como realizar uma análise de dados completa sem depender de ferramentas mais avançadas de BI ou programação.

### 🐍 Etapa 2 — Python

Após concluir a análise no Excel, a mesma base foi utilizada para praticar Python aplicado à Análise de Dados.

Nessa etapa foram utilizados:

- Pandas
- Matplotlib
- Seaborn
- Agrupamentos
- Tabelas dinâmicas
- Filtros
- Métricas
- Análise temporal
- Análise por categorias
- Análise de clientes
- Análise geográfica

A segunda etapa também serviu para compreender como problemas analisados manualmente no Excel podem ser solucionados de forma programática.

---

## 🎯 Objetivo

O principal objetivo do projeto é transformar uma base de vendas em informações úteis para tomada de decisão, respondendo perguntas relacionadas ao desempenho comercial e financeiro da empresa.

Entre as principais questões analisadas estão:

- Quanto a empresa vende?
- Quanto a empresa lucra?
- Como as vendas evoluem ao longo dos anos?
- Qual categoria possui maior faturamento?
- Qual categoria possui maior lucro?
- Quais subcategorias apresentam melhor e pior desempenho?
- Quais são os produtos mais vendidos?
- Quais produtos apresentam menor lucratividade?
- Qual região apresenta melhor desempenho?
- Existem estados operando com prejuízo?
- Como os segmentos de clientes se comportam?
- Quais clientes geram maior faturamento?
- Quais clientes geram maior lucro?
- Qual é o ticket médio?
- Existe relação entre descontos e lucratividade?
- Qual categoria apresentou maior crescimento ao longo do período?

---

## 📊 Principais análises

### 💰 Desempenho financeiro

Foram analisados indicadores como:

- Total de vendas
- Total de lucro
- Margem de lucro
- Quantidade de pedidos
- Quantidade de produtos
- Ticket médio

A análise permite compreender não apenas o volume de vendas, mas também a capacidade de transformar esse faturamento em lucro.

### 🗂️ Análise por categoria

As categorias foram comparadas considerando diferentes métricas:

- Sales
- Profit
- Quantity
- Profit Margin

Também foi realizado um detalhamento das categorias através das respectivas *Sub-Categories*.

Isso permite identificar situações como:

> Uma categoria pode apresentar alto volume de vendas, mas não necessariamente possuir a maior margem de lucro.

### 🏆 Top Products

Foi realizada uma análise dos produtos com maior volume de vendas.

Também foram identificados produtos com menor desempenho em relação ao lucro.

Essa comparação permite observar que:

> Produto que vende muito não necessariamente é produto que gera muito lucro.

### 🌎 Análise geográfica

O desempenho foi analisado considerando diferentes níveis geográficos:

- Region
- State

Também foram identificados estados que apresentaram lucro negativo, permitindo investigar quais categorias e subcategorias contribuem para esses resultados.

### 👥 Análise de clientes

Os clientes foram analisados considerando:

- Faturamento
- Lucro
- Quantidade de pedidos
- Ticket médio

Foram identificados:

- Top clientes por vendas
- Top clientes por lucro
- Clientes com resultado negativo
- Clientes com maior ticket médio

### 📦 Segmentos

A base também foi analisada considerando os segmentos:

- Consumer
- Corporate
- Home Office

Foram realizados cruzamentos entre:

**Segment × Category**

permitindo entender quais categorias possuem maior participação em cada segmento.

### 💸 Descontos × Lucro

Uma das análises exploratórias buscou investigar a relação entre os descontos aplicados e o resultado financeiro.

Foram comparados:

- Discount
- Sales
- Profit
- Profit Margin

A análise identifica relações e padrões presentes nos dados, mas não estabelece, por si só, uma relação causal entre desconto e prejuízo.

### 📈 Análise temporal

As vendas e os lucros foram analisados ao longo do tempo.

Foram avaliados:

- Desempenho anual
- Evolução das vendas
- Evolução do lucro
- Crescimento percentual
- Crescimento por categoria

Isso permitiu observar não apenas o resultado de cada período, mas também como o desempenho da empresa evoluiu ao longo dos anos.

---

## 🖼️ Dashboard

A primeira versão do projeto foi desenvolvida no Excel 2016, utilizando recursos nativos da ferramenta.

![Dashboard](imagens/dashboard_1.png)

---

## 🐍 Análise com Python

Após finalizar a análise no Excel, a mesma base foi utilizada para desenvolver uma segunda versão utilizando Python.

O objetivo não foi simplesmente reproduzir o dashboard, mas utilizar a mesma base para praticar programação aplicada à análise de dados.

**Principais ferramentas utilizadas:**

- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### 🔎 Conceitos praticados com Python

Durante a análise foram utilizados diversos conceitos fundamentais de Pandas:

```python
read_csv()
head()
shape
info()
describe()
isnull()
groupby()
agg()
sort_values()
nlargest()
nsmallest()
reset_index()
pivot_table()
loc[]
query()
nunique()
pct_change()
```

Também foram praticadas operações com datas através do:

```python
pd.to_datetime()
```

e:

```python
.dt.year
.dt.month
```

---

## 🛠️ Tecnologias utilizadas

### 📊 Análise
- Microsoft Excel 2016
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### 🗃️ Dados
- CSV
- Dataset Superstore

### 🔧 Ferramentas
- Visual Studio Code
- Jupyter Notebook
- Git
- GitHub

---

## 📂 Estrutura do projeto

```
Superstore-Analytics/
│
├── data/
│   └── Superstore.csv
│
├── excel/
│   └── Superstore_Analytics.xlsx
│
├── python/
│   ├── Superstore_Analysis_1.ipynb
│   └── Superstore_Analysis_2.ipynb
│
├── images/
│   ├── dashboard_1.png
│   ├── dashboard_2.png
│   ├── fundo_1.png
│   ├── fundo_2.png
│   └── ...
│
├── README.md
└── requeriments.txt
```

**Organização:**

- `data/` → dataset utilizado na análise
- `excel/` → arquivo desenvolvido no Excel 2016
- `python/` → notebook contendo a análise desenvolvida em Python
- `images/` → imagens utilizadas no README
- `README.md` → documentação do projeto
- `.gitignore` → arquivos e pastas que não devem ser versionados

---

## 🔄 Fluxo da análise

O projeto seguiu um processo relativamente simples:

```
Dataset Superstore
        │
        ▼
   Exploração dos dados
        │
        ▼
   Limpeza / preparação
        │
        ├───────────────┐
        ▼               ▼
   Excel 2016        Python
        │               │
        ▼               ▼
    Dashboard       Pandas
                        │
                        ▼
                  Análise Exploratória
                        │
                        ▼
                  Visualizações
                        │
                        ▼
                    Insights
```

---

## 🧠 Principais aprendizados

Um dos principais objetivos do projeto foi entender que a ferramenta utilizada não substitui o raciocínio analítico.

A mesma pergunta pode ser respondida utilizando diferentes tecnologias.

Por exemplo:

**Excel**

```
Tabela Dinâmica
      ↓
Categoria
      ↓
Soma de Sales
      ↓
Gráfico
```

**Python**

```python
df.groupby("Category")["Sales"].sum()
```

Apesar de serem ferramentas diferentes, ambas estão resolvendo essencialmente o mesmo problema.

O projeto também permitiu praticar a transição entre uma análise mais manual, realizada no Excel, e uma abordagem programática utilizando Python.

---

## 📌 Conclusões

A análise mostrou diferentes perspectivas sobre o desempenho da Superstore, permitindo avaliar a empresa não apenas pelo volume de vendas, mas também pela lucratividade, comportamento dos clientes, desempenho regional, categorias, produtos e evolução temporal.

Entre os principais pontos analisados estão:

- Diferenças entre volume de vendas e lucratividade
- Categorias e subcategorias com melhor e pior desempenho
- Produtos responsáveis por grandes volumes de vendas
- Estados com resultados negativos
- Diferenças de comportamento entre segmentos
- Relação entre descontos e resultados financeiros
- Evolução das vendas e do lucro ao longo do tempo

Mais do que chegar a um resultado final, o projeto teve como foco aprender diferentes formas de explorar, analisar e visualizar dados.

---

## 🚀 Próximos passos

Possíveis evoluções para o projeto:

- 📊 Criar uma versão do dashboard utilizando Python
- 🌐 Desenvolver um dashboard web com HTML, CSS e JavaScript
- 📈 Criar análises estatísticas mais avançadas
- 🔄 Automatizar a atualização dos dados
- 🗃️ Armazenar os dados em banco de dados
- 📡 Consumir dados através de uma API
- ⚙️ Criar um pipeline ETL automatizado
- 📊 Comparar os resultados obtidos entre Excel, Python e Power BI

---

## 👨‍💻 Autor

**Julio Guimarães**

Projeto desenvolvido para fins de estudo, portfólio e aplicação prática de conhecimentos em Análise de Dados, Excel e Python.

- 💻 GitHub: [jullyoo](https://github.com/jullyoo)
- 💼 LinkedIn: [LinkedIn](https://www.linkedin.com/in/j-guimaraes/)
- 🌐 Portfólio: [Julyo.dev](https://jullyoo.github.io/Julyo.dev/)

---

> ⭐ *"O fracasso é uma contusão, não uma tatuagem"* - Mike Ross (Suits)
