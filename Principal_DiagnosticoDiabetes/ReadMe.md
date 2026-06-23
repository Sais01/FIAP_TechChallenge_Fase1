
# Tech Challenge - Fase 1: Suporte ao Diagnóstico Médico

Projeto de Machine Learning para classificação de **diagnóstico de diabetes**.

## Objetivo

Criar um modelo preditivo baseado em dados tabulares para apoiar equipes clínicas na análise inicial de exames e triagem de pacientes.

## Estrutura do Projeto

-`notebook.ipynb`: Código-fonte completo contendo a Análise Exploratória, pré-processamento, treinamento dos modelos (Regressão Logística e Random Forest), avaliação de métricas e explicabilidade (SHAP).
-`Dockerfile`: Configuração do ambiente para execução.
-`diabetes.csv`: Base de dados utilizada (obrigatório para execução) [Diabetes Data Set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set/data).

## Como Executar (via Docker)

Para garantir a compatibilidade e execução sem erros de dependências, utilize o Docker:

1. Abra o terminal na pasta do projeto e construa a imagem:
2. ```bash
   docker build -t tech-challenge-fase1 .
   ```
3. Executar o container
   ```bash
   docker run -p 8888:8888 tech-challenge-fase1
   ```
4. Acesse o link gerado no terminal (ex: http://127.0.0.1:8888/lab?token=...) no seu navegador e abra o arquivo *notebook.ipynb*

## Estrutura do Projeto

Vídeo: Inserir link quando eu fizer o vídeo
