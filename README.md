# Detecção de Câncer de Mama com Machine Learning

Projeto desenvolvido no módulo Machine Learning Aplicado II da Pós-Graduação Lato Sensu em Ciência de Dados da Universidade do Estado do Amazonas (UEA).

O objetivo é avaliar o desempenho de algoritmos de aprendizado de máquina na identificação do câncer de mama, com foco no impacto da seleção de features e da estratégia de validação.

## Contexto

O câncer de mama é uma das principais causas de mortalidade entre mulheres;

Estimativa de 74 mil novos casos no Brasil entre 2023 e 2025;

O diagnóstico precoce é decisivo para o sucesso do tratamento;

Machine Learning como ferramenta de apoio à decisão clínica.

## Objetivos

Avaliar o impacto da seleção de variáveis (features) no desempenho dos modelos;

Comparar o desempenho dos modelos antes e depois da seleção de features, bem como contrastar dois protocolos de avaliação:
- Experimento A: Validação cruzada estratificada 10-fold aplicada em todo o dataset.
- Experimento B: Divisão 80/20 (train/test) com GridSearchCV aplicado apenas ao treino.

Identificar os modelos com maior capacidade de generalização em dados biomédicos.

## Equipe

Anna Alicia Milani

Cleidiana Manoel Alves

Thayanne da Silva Ramires

## Base de Dados

Breast Cancer Coimbra Dataset – UCI Machine Learning Repository.
Disponível em: https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra

## Execução

1. preprocess.ipynb

Carrega dataset

Aplica limpeza

Calcula variância/desvio-padrão

Executa feature selection

Exporta arquivos processados

2. train.ipynb

Roda o Experimento A (10-fold)

Roda o Experimento B (train/test + GridSearchCV)

Salva métricas e modelos

3. graphics.ipynb

Gera gráficos comparativos

Cria figuras usadas no artigo/relatório
