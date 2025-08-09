# Dashboard de Análise de Salários na Área de Dados 🎲

Este é um dashboard interativo construído com Streamlit para analisar e visualizar dados de salários no setor de dados. A aplicação permite que os usuários filtrem os dados por ano, senioridade, tipo de contrato e tamanho da empresa para obter insights personalizados.

---

## 🚀 Acessar o Dashboard

Você pode acessar a versão ao vivo do dashboard clicando no link abaixo:

**[➡️ Clique aqui para abrir o dashboard](https://imersao-alura-082025.streamlit.app/)**

---

## ✨ Funcionalidades

* **Dashboard Interativo:** Interface amigável para explorar os dados.
* **Filtros Dinâmicos:** Filtre os dados por:
    * Ano (`ano`)
    * Senioridade (`senioridade`)
    * Tipo de Contrato (`contrato`)
    * Tamanho da Empresa (`tamanho_empresa`)
* **Métricas Chave (KPIs):** Visualização rápida do salário médio, salário máximo, total de registros e o cargo mais frequente com base nos filtros.
* **Visualizações de Dados:** Gráficos gerados com Plotly para melhor compreensão:
    * **Gráfico de Barras:** Top 10 cargos por salário médio.
    * **Histograma:** Distribuição de salários anuais.
    * **Gráfico de Pizza:** Proporção dos tipos de trabalho (remoto, presencial, híbrido).
    * **Mapa (Choropleth):** Salário médio para Cientistas de Dados por país.
* **Tabela de Dados:** Veja os dados brutos filtrados em uma tabela interativa.

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Streamlit:** Framework para a criação do dashboard web.
* **Pandas:** Para manipulação e análise dos dados.
* **Plotly Express:** Para a criação dos gráficos interativos.

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para executar o dashboard em sua máquina local.

### Pré-requisitos

* Ter o [Python 3.8+](https://www.python.org/downloads/) instalado.
* Ter o `pip` (gerenciador de pacotes do Python) instalado.

### Passos

1.  **Clone este repositório:**
    ```bash
    # Substitua pela URL do seu repositório
    git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd NOME_DA_PASTA_DO_PROJETO
    ```

3.  **(Recomendado) Crie e ative um ambiente virtual:**
    * **Windows:**
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```
    * **macOS / Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

4.  **Instale as dependências necessárias:**
    ```bash
    pip install streamlit pandas plotly
    ```

5.  **Execute a aplicação Streamlit:**
    ```bash
    streamlit run app.py
    ```

Após executar o último comando, uma nova aba será aberta em seu navegador com o dashboard em execução!

---

## 📊 Fonte dos Dados

Os dados utilizados neste projeto são de uma versão tratada e consolidada sobre salários na área de dados. O script carrega os dados diretamente de um repositório no GitHub para garantir que estejam sempre atualizados.

---

Desenvolvido por **Fernando Andrade**.
