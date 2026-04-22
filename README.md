# Análise de Dados Aplicada ao Contexto de Apostas no Futebol

Este projeto apresenta um pipeline completo de ciência de dados — desde a coleta bruta até a análise avançada de clusters — focado no mercado de odds (probabilidades) de futebol. O objetivo principal é identificar padrões de comportamento em diferentes ligas e temporadas, utilizando técnicas de aprendizado de máquina e análise de redes.

## 👥 Integrantes
* **Bruno Basckeira Chinaglia**
* **Douglas da Fontoura Pereyra**

## 🎯 Objetivos do Projeto
* **Web Scraping:** Automatizar a coleta de dados históricos de partidas e odds do site 'Oddspedia'.
* **Processamento de Dados:** Limpeza, normalização e engenharia de atributos para preparar o dataset para modelos estatísticos.
* **Análise de Clusterização:** Agrupar ligas e partidas com características semelhantes para identificar perfis de apostas.
* **Detecção de Anomalias:** Identificar outliers e comportamentos inesperados nas odds que fujam do padrão histórico da liga.
* **Visualização de Redes:** Mapear a "distância" entre diferentes ligas mundiais com base na semelhança de suas estatísticas de jogo e apostas.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Automação de Scraping:** Selenium WebDriver
* **Manipulação de Dados:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Clustering, PCA)
* **Visualização:** Matplotlib, Seaborn, NetworkX
* **Ambiente:** Jupyter Notebook / Google Colab

## 📂 Estrutura do Notebook
1. **Coleta de Dados:** Implementação do scraper para a Bundesliga e outras ligas, cobrindo as últimas 10 temporadas.
2. **Pré-processamento:** Tratamento de valores ausentes e formatação de datas e indicadores de odds.
3. **Análise Exploratória (EDA):** Visualização da distribuição de resultados (Home/Draw/Away) e evolução das odds.
4. **Clusterização e Distâncias:** Cálculo de matrizes de distância entre ligas e geração de grafos de similaridade.
5. **Resultados e Outliers:** Identificação das top 5 ligas mais semelhantes e das ligas mais distintas em termos de comportamento de mercado.

## 🚀 Como Executar
1. Clone este repositório ou baixe o arquivo `.ipynb`.
2. Certifique-se de ter o Python 3.8+ instalado.
3. Instale as dependências necessárias.
