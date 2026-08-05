# 💰 Dashboard de Salários da Área de Dados

Este projeto é uma aplicação web interativa desenvolvida em **Python** utilizando **Streamlit**, **Pandas** e **Plotly**. O objetivo principal é analisar a distribuição salarial na área de dados com base em fatores como ano, nível de senioridade, tipo de contrato e tamanho da empresa.

O projeto foi desenvolvido originalmente durante a **Imersão Dados com Python da Alura**.

---

## 📌 Visão Geral do Projeto

A aplicação consome uma base de dados remota contendo informações globais sobre remuneração na área de dados e apresenta:
1. **Filtros Dinâmicos Interativos**: Filtre os dados por ano, nível de experiência (senioridade), modelo de contrato e porte da organização.
2. **Métricas Principais (KPIs)**: Média salarial (USD), maior salário registrado, total de registros analisados e cargo mais frequente.
3. **Visualizações Gráficas**:
   * **Top 10 Cargos**: Ranking dos cargos com as maiores médias salariais.
   * **Histograma Salarial**: Distribuição da frequência dos salários anuais.
   * **Modelo de Trabalho**: Gráfico de rosca exibindo a proporção entre trabalho remoto, presencial e híbrido.
   * **Mapa Coroplético (Choropleth)**: Média salarial de Cientistas de Dados (`Data Scientist`) ao redor do mundo por país de residência.
4. **Tabela de Dados**: Exibição detalhada e filtrável dos dados brutos.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **[Streamlit](https://streamlit.io/):** Framework para criação de interfaces web e dashboards interativos.
* **[Pandas](https://pandas.pydata.org/):** Manipulação, tratamento e filtragem dos dados.
* **[Plotly Express](https://plotly.com/python/plotly-express/):** Criação de gráficos interativos e mapas.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o **Python 3+** e o `pip` instalados no seu computador.

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/dashboard-salarios-dados.git
   cd dashboard-salarios-dados
   ```

2. **(Opcional) Criar e ativar um ambiente virtual:**
   * **Linux/macOS:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   * **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Instalar as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Executar a aplicação Streamlit:**
   ```bash
   streamlit run app.py
   ```

5. **Acessar o Dashboard:**
   O Streamlit abrirá automaticamente uma aba no seu navegador padrão no endereço `http://localhost:8501`.
