# 📊 Análise de Risco de Crédito Inteligente na AWS com SageMaker Canvas
Bem-vindo ao meu projeto de "Análise de Risco de Crédito Inteligente na AWS com SageMaker Canvas". Neste projeto, utilizei o SageMaker Canvas para criar previsões de risco de crédito baseadas em Machine Learning (ML). Abaixo, descrevo os passos que segui para completar este desafio.

## 📋 Pré-requisitos
Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira este repositório AWS Cloud Quickstart.

## 🎯 Objetivos Deste Projeto
O objetivo deste projeto é aplicar técnicas de Machine Learning no SageMaker Canvas para realizar uma análise de risco de crédito. Compartilho aqui a metodologia e as etapas que segui para atingir esse objetivo.

## 🚀 Passo a Passo
### 1. Seleção do Dataset
Naveguei até a pasta datasets deste repositório para explorar os dados disponíveis.
Decidi utilizar um dataset de histórico de crédito contendo informações sobre clientes e suas respectivas classificações de risco.
Fiz o upload do dataset no SageMaker Canvas para iniciar a análise.

### 2. Preparação dos Dados
No SageMaker Canvas, importei o dataset que selecionei.
Analisei as variáveis disponíveis e configurei as variáveis de entrada (como histórico de pagamentos, renda, idade, etc.) e a variável de saída (risco de crédito).
Realizei uma limpeza inicial dos dados para remover entradas duplicadas e preencher valores faltantes.

### 3. Construção e Treinamento do Modelo
Configurei o SageMaker Canvas para iniciar o treinamento do modelo de Machine Learning.
Ajustei os parâmetros de treinamento conforme necessário para otimizar o desempenho do modelo.
O treinamento do modelo levou algum tempo, devido ao tamanho do dataset e à complexidade do problema.

### 4. Análise do Modelo
Após o treinamento, examinei as métricas de performance do modelo, como acurácia, precisão e recall.
Identifiquei as principais características que influenciam as previsões de risco de crédito.
Realizei ajustes no modelo e re-treinei até obter um desempenho satisfatório.

### 5. Realização de Previsões
Com o modelo treinado, utilizei-o para fazer previsões de risco de crédito em novos dados de clientes.
Exportei os resultados das previsões para análise posterior.
Documentei as conclusões obtidas e insights relevantes sobre os dados e as previsões de risco.

## Conclusões
Este projeto proporcionou uma excelente oportunidade para aplicar técnicas de Machine Learning na análise de risco de crédito utilizando uma abordagem no-code com o SageMaker Canvas. Aprendi sobre a importância da preparação de dados, da configuração correta das variáveis e da análise crítica das métricas de performance do modelo.
