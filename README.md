# Análise e Agrupamento de Dados com K-Means

Este repositório contém um notebook em Python que demonstra um fluxo de trabalho completo de **pré-processamento de dados** e **clusterização não supervisionada**, utilizando o algoritmo **K-Means**.

## Sobre o Projeto

O objetivo principal é aplicar técnicas de preparação de dados em um dataset real, realizando limpeza, transformação e padronização antes de aplicar o algoritmo de clusterização K-Means. O notebook é estruturado de forma didática, ideal para fins de estudo e demonstração de conceitos fundamentais em ciência de dados e aprendizado de máquina não supervisionado.

## Estrutura do Projeto

Este repositório contém duas versões principais do código, cada uma com um propósito específico:

* **`analise-iris-kmeans.ipynb`**: Um **Jupyter Notebook** que serve como um relatório detalhado da análise. Ele contém o passo a passo com explicações, visualizações e as saídas de cada célula, ideal para estudo e apresentação do processo.  
* **`analise-iris-kmeans.py`**: Um **script Python (.py)** que é a versão refatorada e limpa do notebook. Este arquivo é modular, reutilizável e pode ser executado diretamente pelo terminal, sendo ideal para automação e implementação.

## Como Executar o Notebook

### Usando Git Clone (Recomendado)

1.  **Pré-requisito:** Tenha o [Git](https://git-scm.com/) e Python instalados.

2.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

3.  **Navegue até a pasta e instale as dependências:**
    ```bash
    cd nome-do-repositorio
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

4.  **Execute o script:**
    ```bash
    python analise-iris-kmeans.py
    ```

5.  **Carregue o notebook:**
    * **Se estiver usando o Google Colab:**
        1. Faça o upload do arquivo `analise-iris-kmeans.ipynb`.
        2. Execute as células em ordem.
    * **Se estiver usando Jupyter Notebook (localmente):**
        ```bash
        jupyter notebook analise-iris-kmeans.ipynb
        ```

6.  **Execute o código:** Basta rodar as células em ordem para reproduzir toda a análise.

## Metodologia

O processo abordado no código segue as seguintes etapas:

1. **Análise Exploratória e Entendimento dos Dados:** Carregamento do dataset e investigação inicial das colunas e tipos de dados.  
2. **Pré-processamento de Dados:**  
   * Tratamento de valores faltantes.  
   * Transformação de variáveis categóricas com **One-Hot Encoding**.  
   * Normalização/Padronização das variáveis numéricas para garantir que todas tenham a mesma escala.  
3. **Modelagem com K-Means:**  
   * Definição do número de clusters a partir do **método do cotovelo**.  
   * Treinamento do algoritmo de clusterização **KMeans** da biblioteca Scikit-learn.  
   * Análise e visualização dos grupos formados.  
4. **Avaliação dos Resultados:**  
   * Interpretação dos clusters.  
   * Cálculo de métricas como a **inércia** para avaliar a qualidade do agrupamento.  

## Bibliotecas Utilizadas

* **Pandas:** Para manipulação e análise de dados.  
* **NumPy:** Para operações numéricas.  
* **Scikit-learn:** Para implementação do K-Means, pré-processamento e avaliação de métricas.  
* **Matplotlib:** Para visualizações gráficas.  
* **Seaborn:** Para visualizações estatísticas mais elaboradas.  

