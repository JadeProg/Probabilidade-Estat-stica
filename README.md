# Análise Estatística com Dados da PNAD

Este projeto realiza uma análise estatística descritiva e exploratória utilizando um conjunto de dados inspirado na Pesquisa Nacional por Amostra de Domicílios (PNAD). O objetivo é aplicar conceitos fundamentais de probabilidade e estatística para extrair insights sobre características demográficas e socioeconômicas da amostra.

O código foi desenvolvido em um notebook Jupyter (`.ipynb`) e utiliza bibliotecas como Pandas, Matplotlib e Seaborn para manipulação, análise e visualização dos dados.

## 📂 Estrutura do Projet

-   `Probabilidade_Estatistica.ipynb`: Notebook principal contendo todo o código da análise.
-   `Collab/`: Pasta que pode conter arquivos auxiliares ou versões do notebook (conforme a imagem do repositório).
-   `arquivo.csv.xls`: Fonte de dados utilizada na análise (nome inferido do código).

## 🛠️ Tecnologias Utilizadas

-   **Linguagem:** Python 3
-   **Bibliotecas:**
    -   `pandas`: Para manipulação e análise de dados.
    -   `numpy`: Para operações numéricas.
    -   `matplotlib` e `seaborn`: Para visualização de dados e criação de gráficos.
    -   `scipy`: Para cálculos estatísticos avançados, como o teste Qui-quadrado.

## 📖 Etapas da Análise

O notebook está estruturado nas seguintes seções:

1.  **Classificação de Variáveis**: Identificação das variáveis como qualitativas (nominais e ordinais) e quantitativas (discretas e contínuas).
2.  **Distribuição de Frequência**: Análise da frequência absoluta e percentual para variáveis categóricas como `UF`, `Sexo`, `Cor` e `Anos de Estudo`.
3.  **Visualização de Dados**: Criação de gráficos de barras e histogramas para entender a distribuição das variáveis.
4.  **Medidas de Posição**: Cálculo de média, mediana e moda para as variáveis quantitativas (`Idade`, `Renda`, `Altura`) para identificar a tendência central dos dados.
5.  **Medidas de Dispersão**: Análise de variância, desvio padrão, amplitude e coeficiente de variação para entender o grau de espalhamento dos dados.
6.  **Análise de Quantis**: Uso de quartis para dividir os dados e entender melhor sua distribuição.
7.  **Box Plots**: Visualização gráfica dos quantis e detecção de *outliers*.
8.  **Associação entre Variáveis Qualitativas**: Aplicação do teste Qui-quadrado para verificar a existência de associação estatística entre `Sexo` e `Cor`.
9.  **Associação entre Variáveis Quantitativas**: Cálculo da correlação de Pearson e criação de um gráfico de dispersão para analisar a relação entre `Idade` e `Renda`.
10. **Conclusão**: Resumo dos principais insights obtidos durante a análise.

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/JadeProg/Probabilidade-Estat-stica.git
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd Probabilidade-Estat-stica
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib seaborn scipy
    ```
4.  **Execute o Jupyter Notebook:**
    Abra o arquivo `Probabilidade_Estatistica.ipynb` em um ambiente Jupyter (como Jupyter Lab, Jupyter Notebook ou Google Colab ) e execute as células.

    **Observação:** Certifique-se de que o arquivo de dados (`arquivo.csv.xls`) esteja no mesmo diretório do notebook.

## ✍️ Autor

-   **Jade Pereira da Paz**
-   **GitHub:** [JadeProg](https://github.com/JadeProg )

