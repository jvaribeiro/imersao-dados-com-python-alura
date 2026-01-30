# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é uma aplicação interativa desenvolvida durante a **Imersão Dados com Python da Alura (Edição 2026)**. O objetivo é explorar e visualizar tendências salariais globais no setor de tecnologia, permitindo que profissionais e empresas entendam melhor o panorama financeiro da área de dados.

---

## 🔗 Links do Projeto
* **Guia de Referência:** [Imersão Dados 2026 - Alura](https://grupoalura.notion.site/Imers-o-Dados-com-Python-2026-Guia-de-Mergulho-2d9379bdd09b81fe89f8ff4b3f3f4aee)

---

## 🚀 Sobre a Aplicação

A dashboard foi construída utilizando **Python** e o framework **Streamlit**. Ela processa um conjunto de dados real com mais de 133 mil registros, abrangendo o período de 2020 a 2025. 

### 🛠️ Tecnologias Utilizadas
* **Python 3.13.7**: Linguagem principal.
* **Pandas**: Manipulação, limpeza e tratamento dos dados.
* **Streamlit**: Criação da interface web e componentes interativos.
* **Plotly**: Geração de gráficos dinâmicos (Histogramas, Gráficos de Pizza e Mapas).

---

## 📊 Funcionalidades Principais

O projeto permite uma análise profunda através de:

1.  **Métricas em Tempo Real (KPIs):**
    * Exibição do salário médio global ($157,619).
    * Identificação do teto salarial ($800,000).
    * Contagem total de registros filtrados.
    * Destaque para o cargo com maior volume de contratações (**Data Scientist**).

2.  **Visualizações Gráficas:**
    * **Top 10 Cargos:** Ranking dos cargos com as maiores médias salariais.
    * **Distribuição Salarial:** Histograma para entender a concentração de salários por faixas de valores.
    * **Modelos de Trabalho:** Proporção entre vagas presenciais (79%), remotas (20.8%) e híbridas.
    * **Mapa de Calor Global:** Visualização geográfica da média salarial por país.

3.  **Sistema de Filtros Inteligentes:**
    * Filtro por **Ano** (2020 a 2025).
    * Filtro por **Senioridade** (Junior, Pleno, Senior e Executivo).
    * Filtro por **Tipo de Contrato** (Freelancer, Integral, Parcial, Contrato).
    * Filtro por **Tamanho da Empresa** (Pequena, Média e Grande).

---

## 📂 Dados Detalhados

Além dos gráficos, a aplicação disponibiliza uma seção de **Dados Detalhados** que exibe a tabela bruta processada, permitindo a verificação individual de registros, moedas locais, e residência dos colaboradores.

---

## 📸 Demonstração

### Visão Geral do Dashboard
<img width="2558" height="1282" alt="Captura de tela de 2026-01-30 19-54-23" src="https://github.com/user-attachments/assets/7d03473e-bc2c-4a6c-bf4e-0e288efef17e" />

<img width="2558" height="1282" alt="Captura de tela de 2026-01-30 19-54-33" src="https://github.com/user-attachments/assets/81aa33b5-517f-4de9-8771-f0bc15fb71a0" />

---

## ⚙️ Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/jvaribeiro/imersao-dados-com-python-alura.git
   ```

2. Entre na pasta do projeto:
   ```bash
   cd imersao-dados-com-python-alura
   ```

3. Crie um ambiente virtual (opcional, recomendado)
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux / macOS
    venv\Scripts\activate     # Windows
    ```
   
4. Instale as dependências necessárias:
   ```bash
    pip install -r requirements.txt
   ```
     
5. Execute o dashboard:
   ```bash
   streamlit run app.py
   ```
