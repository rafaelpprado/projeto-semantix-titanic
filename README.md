<div align="center">

# 🚢 Projeto Semantix — Titanic

Machine Learning aplicado ao dataset Titanic (Kaggle)  
**Modelagem preditiva • Visualizações • Documentação**

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

</div>

---

## 📘 Sobre
Projeto final desenvolvido para a parceria Semantix.  
O objetivo é prever a sobrevivência dos passageiros do Titanic usando técnicas de Machine Learning.  

Inclui:
- Feature engineering (título, família, cabine, ticket, etc.).
- Pré-processamento com imputação, padronização e one-hot encoding.
- Modelagem com Random Forest, SVM, XGBoost e Stacking Ensemble.
- Avaliação com validação cruzada, holdout e métricas diversas.
- Visualizações para interpretação dos resultados.

---

## 📦 Conteúdo
- `Projeto_Semantix_Titanic.ipynb` → notebook principal com o pipeline.
- `README.md` → documentação do projeto.

---

## ▶️ Como rodar
```bash
pip install -r requirements.txt
jupyter lab  # ou jupyter notebook
```

## 📊 Resultados
- **Cross Validation (10-fold)** → Accuracy média ~0.837  
- **Holdout (20%)** → Accuracy 0.810, F1 0.757, Precision 0.746, Recall 0.768, AUC 0.858  
- **Validação Repetida (5x3)** → Accuracy 0.8279 ±0.025, F1 0.772 ±0.033, AUC 0.878 ±0.020  

O ensemble se mostrou estável e apresentou bom equilíbrio entre métricas.

---

## 📈 Visualizações
- **Curva ROC** → qualidade das previsões probabilísticas.  
- **Matriz de Confusão** → acertos e erros por classe.  
- **PCA + K-Means** → análise exploratória dos perfis de passageiros.  

As figuras são geradas automaticamente ao rodar o notebook.

---

## 📋 Requirements
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- imbalanced-learn  
- xgboost  

---

## ✍️ Autor
Rafael Prado
