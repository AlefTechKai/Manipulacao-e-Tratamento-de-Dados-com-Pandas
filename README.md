# Data Wrangling & Insights: Análise do Catálogo de Filmes e Séries

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)

## 📌 Objetivo do Projeto
Este projeto demonstra a aplicação de técnicas avançadas de **Data Wrangling** e **Análise Exploratória (EDA)** em um dataset bruto de títulos cinematográficos. O foco principal foi transformar dados não estruturados e sujos em uma base de dados otimizada para Business Intelligence.

## 🛠️ Etapas do Pipeline de Dados

### 1. Extração e Limpeza (Data Cleaning)
* Identificação e tratamento de valores ausentes (**NaN**) para garantir a integridade estatística.
* Normalização do schema: Tradução e padronização dos nomes das colunas para PT-BR, seguindo boas práticas de governança.

### 2. Engenharia de Atributos (Feature Engineering)
* **Conversão de Tipos:** Transformação de dados de objetos (strings) para tipos numéricos e temporais.
* **Criação de Métrica Crítica:** Desenvolvimento da coluna `duracao_min`. Através de técnicas de manipulação de strings (Regex/Replace), extraí os valores numéricos dos tempos de duração, permitindo análises de média, mediana e desvios de tempo.

### 3. Análise Exploratória (EDA)
* Análise de distribuição por gênero e país de origem.
* Verificação de tendências de lançamento ao longo das décadas.

## 🚀 Tecnologias Utilizadas
* **Python 3.x**
* **Pandas:** Manipulação e tratamento de dados.
* **NumPy:** Suporte matemático para conversão de tipos.
* **Matplotlib/Seaborn:** Visualização de padrões ocultos.

## 📊 Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Abra o notebook: `jupyter notebook Python_Pandas.ipynb`

---
**Desenvolvido por Alef Barbosa** *Especialista em Infraestrutura e Analista de Dados em formação.*
