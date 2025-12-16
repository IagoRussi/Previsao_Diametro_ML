## Descrição do Projeto

Este projeto é um exemplo simples de Machine Learning com Regressão Linear, desenvolvido em Python, utilizando Scikit-learn para o treinamento do modelo e Streamlit para a interface web.

O objetivo é prever o preço de uma pizza com base no seu diâmetro, a partir de um conjunto de dados previamente definido.

## Conjunto de Dados Utilizado

O modelo é treinado utilizando um dataset simples, que relaciona o diâmetro da pizza (em centímetros) com o preço correspondente:

diametro,preco
20,50
22,55
24,60
26,65
28,70
30,75
32,80
34,85
36,90
38,95
40,100

Esses dados representam exemplos reais que o modelo utiliza para aprender a relação linear entre o tamanho da pizza e o seu preço.

## Durante a execução da aplicação:

-Esses valores são carregados
-O modelo de Regressão Linear é treinado em tempo de execução
-A partir desse treinamento, o modelo passa a estimar preços para novos diâmetros informados pelo usuário

## Como funciona o Machine Learning no projeto

-O sistema lê o conjunto de dados (diâmetro × preço)
-O algoritmo de Regressão Linear aprende o padrão existente entre essas variáveis
-Quando o usuário informa um novo diâmetro no Streamlit:
-O valor é enviado ao modelo treinado
-O modelo realiza a previsão
-O preço estimado é exibido na tela

---

## 🧠 Tecnologias utilizadas

- Python 3.12+
- Pandas
- Scikit-learn
- Streamlit
- Matplotlib
- Poetry (gerenciamento de dependências)

---

## 🚀 Como executar o projeto (passo a passo)

### 1. Clone o repositório

### 2. Instale o Poetry
pip install poetry

### 3. Instale as dependências do projeto e ative o ambiente virtual
poetry install
poetry env activate

### 4. Execute a aplicação
poetry run streamlit run "Caminho-da-aplicação.py"

---

Ao abrir o Streamlit no navegador, o usuário deverá informar o diâmetro da pizza, digitar o valor e pressionar Enter. Em seguida, o sistema processará os dados e exibirá o resultado automaticamente.
