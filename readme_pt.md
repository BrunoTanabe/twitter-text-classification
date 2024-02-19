# 🐦 Twitter Text Classification 🐦
Este projeto foca na análise de sentimento de tweets em português utilizando técnicas de aprendizado de máquina. O principal objetivo é classificar os tweets como positivos ou negativos com base em seu conteúdo. Abaixo está uma explicação detalhada dos componentes do projeto, desde a pré-processamento dos dados até a avaliação do modelo.

## 🎯 Objetivos do Projeto 🎯
O principal objetivo deste projeto é classificar tweets em sentimentos positivos e negativos usando técnicas de processamento de linguagem natural (PLN). Especificamente, o projeto visa alcançar os seguintes objetivos:
- Desenvolver um modelo de classificação de texto capaz de categorizar com precisão tweets com base em sentimentos.
- Utilizar técnicas de pré-processamento para limpar e preparar os dados de texto para análise.
- Avaliar o desempenho do modelo de classificação em conjuntos de dados de treinamento e teste.

## ℹ️ Principais Recursos ℹ️
- Importação de bibliotecas necessárias para manipulação de dados, visualização e aprendizado de máquina.
- Carregamento de bancos de dados de treinamento e teste contendo tweets para análise de sentimentos.
- Etapas de pré-processamento de texto incluindo conversão para minúsculas, tratamento de nomes de usuário, URLs, emoticons, remoção de palavras irrelevantes, lematização e remoção de pontuação.
- Criação de um modelo de classificação de texto usando o componente `textcat` do spaCy.
- Treinamento do modelo usando o conjunto de dados de treinamento e avaliação de seu desempenho.
- Teste do modelo treinado em frases de exemplo e avaliação de suas previsões.
- Avaliação do modelo usando pontuação de precisão e matriz de confusão.

## 💻 Tecnologias Utilizadas 💻
O projeto utiliza as seguintes tecnologias e bibliotecas:
- Python 🐍
- spaCy 🧠
- NumPy 🔢
- pandas 🐼
- scikit-learn 🧮
- Matplotlib 📊
- Seaborn 🌊

## 📋 Requisitos 📋
Para executar o projeto, certifique-se de ter o seguinte instalado:
- Python 3.x
- Jupyter Notebook ou outro ambiente Python
- Bibliotecas Python necessárias: spaCy, NumPy, pandas, scikit-learn, Matplotlib, Seaborn

## ▶️ Configurando o Projeto ▶️
### Configurando o ambiente no Linux
1. Clone este repositório utilizando o comando `git clone https://github.com/BrunoTanabe/twitter-text-classification`.
2. Navegue até a pasta faq-recommendations utilizando o comando `cd twitter-text-classification`.
3. Crie um ambiente virtual utilizando o comando `python3 -m venv venv`.
4. Ative o ambiente virtual utilizando o comando `source venv/bin/activate`.
5. Instale os requisitos utilizando o comando `pip install -r requirements.txt`.
6. Execute o comando `python -m spacy download pt_core_news_lg` para baixar o modelo NLP para processamento de texto.

### Configurando o ambiente no Windows
1. Clone este repositório utilizando o comando `git clone https://github.com/BrunoTanabe/twitter-text-classification`.
2. Navegue até a pasta faq-recommendations utilizando o comando `cd twitter-text-classification`.
3. Crie um ambiente virtual utilizando o comando `python -m venv venv`.
4. Ative o ambiente virtual utilizando o comando `./venv/scripts/activate`.
5. instale os requisitos utilizando o comando `pip install -r requirements.txt`.
6. Execute o comando `python -m spacy download pt_core_news_lg` para baixar o modelo NLP para processamento de texto.

## ⚠️ Nota Importante ⚠️
Certifique-se de que os caminhos dos arquivos para carregar e salvar dados/modelos estão configurados corretamente com base na estrutura do seu diretório local.

## ✍️ Autores ✍️
Este projeto foi criado por Bruno Tanabe. Para quaisquer dúvidas ou feedback, entre em contato com tanabebruno@gmail.com.
