# 🚀 MLflow Experiments  
Rastreio, versionamento e comparação de experimentos de Machine Learning com MLflow

Este repositório contém um conjunto de **experimentos de Machine Learning** registrados com **MLflow**, demonstrando boas práticas de rastreio, versionamento, organização e comparação de modelos.  
O objetivo é criar uma estrutura clara para execução, logging e avaliação sistemática de modelos durante o ciclo de vida de desenvolvimento em ML.

---

## 🧠 Objetivos do projeto
- Implementar experimentos reproduzíveis de Machine Learning.  
- Registrar métricas, parâmetros, artefatos e modelos utilizando **MLflow Tracking**.  
- Comparar diferentes algoritmos e hiperparâmetros.  
- Demonstrar fluxo completo de experimentação: *data prep → treino → avaliação → tracking*.  
- Estabelecer uma base para futuros pipelines MLOps.

---

## 🏗️ Tecnologias e Ferramentas
- **Python 3.10+**
- **MLflow**
- **scikit-learn**
- **pandas**
- **NumPy**
- **matplotlib / seaborn**

---

## 📁 Estrutura do Repositório
```
mlflow-experiments/
│
├── data/ # Dados utilizados nos experimentos
├── notebooks/ # Análises exploratórias e protótipos
├── scripts/ # Scripts Python para treino e logging
├── mlruns/ # Diretório gerado pelo MLflow com todos os logs
└── README.md
```
