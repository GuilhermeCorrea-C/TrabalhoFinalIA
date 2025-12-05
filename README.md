# Detecção de Arritmias com IA usando o Dataset Heartbeat (MIT-BIH)

Este repositório contém o código, modelos e análises desenvolvidas para a detecção automática de arritmias cardíacas utilizando técnicas de Machine Learning e Redes Neurais. O objetivo principal é aplicar algoritmos de aprendizado não supervisionado e supervisionado para classificar batimentos cardíacos a partir de dados do famoso banco MIT-BIH Arrhythmia.

## 🩺 Contexto do Problema

O Eletrocardiograma (ECG) registra a atividade elétrica do coração ao longo do tempo, gerando um sinal que pode ser analisado para identificar irregularidades nos batimentos. Tradicionalmente, essa análise é manual e feita por especialistas — um processo demorado, sujeito a erros e à variabilidade entre avaliadores.

A Inteligência Artificial surge como uma ferramenta promissora para automatizar a detecção dessas anomalias. Com dados rotulados, é possível treinar modelos capazes de identificar padrões sutis e anomalias difíceis de observar manualmente.

## 📊 Sobre o Dataset

Utilizamos o dataset **Heartbeat** (disponível no Kaggle), uma versão pré-processada e segmentada do banco MIT-BIH Arrhythmia.

Cada linha representa **um batimento cardíaco**, contendo **187 amostras do sinal**. Os batimentos são classificados em 5 categorias:

1. **Classe 0 (N)** — Batimento Normal
2. **Classe 1 (S)** — Arritmia Supraventricular
3. **Classe 2 (V)** — Arritmia Ventricular
4. **Classe 3 (F)** — Batimento de Fusão
5. **Classe 4 (Q)** — Batimento Desconhecido/Não Classificável

O dataset possui **109.446 amostras**, permitindo treinar modelos robustos e confiáveis.

## 🧠 O que foi desenvolvido

* Pré-processamento dos dados
* Normalização
* Aplicação de **K-Means** para análise exploratória
* Treinamento de uma **Rede Neural Artificial (MLP)** para classificação
* Avaliação com métricas como acurácia, matriz de confusão e relatórios de desempenho

## 👥 Integrantes do Grupo

* **Deivid Ferreira**
* **Guilherme Correa Carlos**
* **Nathalia Barcelos**
---

