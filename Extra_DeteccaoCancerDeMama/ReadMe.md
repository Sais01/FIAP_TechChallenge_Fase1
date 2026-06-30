'

# Tech Challenge - Fase 1: Suporte ao Diagnóstico Médico

Projeto de Machine Learning que utiliza Visão Computacional para detecção da presença de câncer de mama em radiografias.

## Objetivo

Criar um modelo de Rede Neural baseado em um dataset de imagens para apoiar equipes clínicas na análise de radiografias de pacientes.

## Estrutura do Projeto

-`notebook.ipynb`: Código-fonte completo contendo a Análise Exploratória, pré-processamento, treinamento dos modelos (Regressão Logística e Random Forest), avaliação de métricas e explicabilidade (SHAP).
-`Dockerfile`: Configuração do ambiente para execução.

## Como Executar (via Docker)

Para garantir a compatibilidade e execução sem erros de dependências, utilize o Docker:

1. Abra o terminal na pasta do projeto e construa a imagem:
2. ```bash
   docker build -t tech-challenge-fase1-extra .
   ```
3. Executar o container
   ```bash
   docker run -p 8888:8888 tech-challenge-fase1-extra
   ```
4. Acesse o link gerado no terminal (ex: http://127.0.0.1:8888/lab?token=...) no seu navegador e abra o arquivo *notebook.ipynb*

## Vídeo do Projeto

[youtu.be/lAvrpq78rk0](https://youtu.be/lAvrpq78rk0)