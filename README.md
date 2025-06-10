# **Análise Estratégica de Vendas para Otimização de Rede de Lojas**

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.5-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-882255?style=for-the-badge&logo=seaborn&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-0.14-31A251?style=for-the-badge&logo=leaflet&logoColor=white)

Este projeto apresenta uma análise de dados completa de uma rede de varejo fictícia, com o objetivo de fornecer uma recomendação de negócios baseada em evidências para otimizar as operações da empresa.

---

## **Índice**

1.  [Descrição do Projeto](#descrição-do-projeto)
2.  [Objetivos da Análise](#objetivos-da-análise)
3.  [Ferramentas e Bibliotecas](#ferramentas-e-bibliotecas)
4.  [Estrutura do Repositório](#estrutura-do-repositório)
5.  [Instruções de Instalação e Execução](#instruções-de-instalação-e-execução)
6.  [Resumo da Análise e Conclusão](#resumo-da-análise-e-conclusão)
7.  [Autor](#autor)

---

## **Descrição do Projeto**

Este projeto consiste em uma análise exploratória de dados de vendas de uma rede de quatro lojas fictícias, **desenvolvido como parte do Challenge para o curso de Cientista de Dados da [Alura](https://www.alura.com.br)**. O objetivo é aplicar conceitos de análise de dados para realizar um diagnóstico completo do desempenho de cada unidade de negócio, utilizando dados de vendas, produtos, clientes e geolocalização. A análise culmina em um relatório estratégico que fornece uma recomendação de negócios, baseada em dados, sobre qual loja deveria ser considerada para desinvestimento (venda), a fim de otimizar os recursos da empresa.

## **Objetivos da Análise**

-   **Diagnóstico Financeiro:** Comparar o faturamento total e o custo médio de frete entre as lojas.
-   **Diagnóstico de Mercado:** Identificar as categorias de produtos mais relevantes e os produtos específicos mais e menos vendidos.
-   **Diagnóstico de Cliente:** Medir e comparar a média de satisfação dos clientes por loja.
-   **Diagnóstico Geoespacial:** Mapear a distribuição das vendas em um cenário realista na cidade de São Paulo para entender a dinâmica de mercado de cada loja.
-   **Recomendação de Negócio:** Sintetizar todas as análises para fornecer uma recomendação clara e justificada sobre qual unidade de negócio vender.

## **Ferramentas e Bibliotecas**

-   **Python 3.11**
-   **Pandas**: Para toda a manipulação e estruturação de dados.
-   **NumPy**: Para operações numéricas, especialmente na simulação de coordenadas.
-   **Matplotlib & Seaborn**: Para a geração de visualizações de dados estáticas (gráficos de barras, pizza, heatmaps).
-   **Folium**: Para a criação do mapa interativo com geolocalização.

## **Estrutura do Repositório**

/
│
├── 📜 Base de dados  # Fonte dados utilizado no projeto.
├── 📜 analise_de_vendas.ipynb   # Notebook Jupyter contendo todo o código, análises e conclusões.
├── 📄 README.md                 # Documentação do projeto (este arquivo).
└── 📋 requirements.txt          # Lista de dependências para execução em ambiente local.

## **Instruções de Instalação e Execução**

### **Ambiente Recomendado: Google Colab**

1.  Acesse o [Google Colab](https://colab.research.google.com/).
2.  Faça o upload do notebook (`analise_de_vendas.ipynb`) através do menu `Arquivo > Fazer upload de notebook`.
3.  Execute as células em ordem sequencial. As fontes de dados são carregadas via URL, não sendo necessário o download de arquivos adicionais.

### **Ambiente Local**

1.  **Clone o repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    cd [NOME_DO_SEU_REPOSITORIO]
    ```
2.  **Crie e ative um ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Em Linux/macOS
    # venv\Scripts\activate   # Em Windows
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Inicie o Jupyter:**
    ```bash
    jupyter notebook
    ```
5.  Abra o arquivo `analise_de_vendas.ipynb` e execute as células.

---

## **Resumo da Análise e Conclusão**

A análise multifatorial demonstrou uma clara disparidade de desempenho entre as quatro lojas. A **Loja 4**, designada para a Zona Leste em nossa simulação, apresentou consistentemente os piores indicadores:

* **Menor Faturamento:** Contribuição significativamente inferior para a receita total.
* **Maior Custo Operacional:** Custo médio de frete mais elevado, pressionando as margens.
* **Menor Satisfação do Cliente:** Avaliações médias mais baixas, indicando risco à reputação.
* **Baixa Performance de Vendas:** Dificuldade em vender os produtos-chave da rede.

A análise geoespacial com `folium` enriqueceu o estudo, mostrando que a fraca performance da Loja 4 não se devia a uma sobreposição de mercado, mas a desafios intrínsecos à sua operação naquela zona específica.

**Recomendação Final:** Com base nas evidências, foi recomendado o **desinvestimento da Loja 4**. A venda da unidade permitiria à empresa concentrar seus esforços e capital nas lojas mais lucrativas, otimizando a operação e fortalecendo o crescimento sustentável do negócio.

---

## **Autor**

**[Jhonatan Willian Santos de Santana]**

* **LinkedIn:** `https://www.linkedin.com/in/jhonatan-willian-santana-5808ab172/`
* **GitHub:** `https://github.com/jhonatanwsds`
