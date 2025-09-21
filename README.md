# ClasificacionCNN_CancerEstomago
Proyecto final asignatura Deep Learning MIADS

# Proyecto Final - Deep Learning para Clasificación de Imágenes Médicas

Este repositorio contiene el proyecto final de la **Maestría en Inteligencia Artificial y Ciencia de Datos (MIADS)**, enfocado en el análisis y comparación del desempeño de diferentes arquitecturas de **Deep Learning** aplicadas a la clasificación de imágenes médicas.

👩‍💻 Autor

Miriam Elizabeth López Hernández
Maestría en Inteligencia Artificial y Ciencia de Datos – UP
Líder de Ciencia de Datos en Retail
---

## 🎯 Objetivo

Evaluar y comparar el rendimiento de tres modelos de deep learning en la tarea de **clasificación binaria de tumores (benigno vs maligno)**, considerando precisión, capacidad de generalización y costo computacional.

Modelos analizados:
1. **CNN tradicional (ResNet-50)**
2. **Vision Transformer (ViT)**
3. **Arquitectura Híbrida (CNN + Transformer)**

---
## ⚙️ Requisitos

Este proyecto fue desarrollado en **Google Colab** con **GPU T4**.  

Principales librerías utilizadas

torch, torchvision, torchsummary

scikit-learn

matplotlib, seaborn

pandas, numpy

📊 Metodología

Análisis exploratorio del dataset

Distribución de clases

Balanceo mediante técnicas de oversampling

Preprocesamiento

Redimensionamiento y normalización de imágenes

Aumento de datos (data augmentation)

Entrenamiento de modelos

Definición de backbone y head según arquitectura

Optimización con AdamW, Adam y SGD

Hiperparámetros ajustados: learning rate, batch size, épocas

Evaluación

Curvas de pérdida y precisión

Matriz de confusión

ROC y PR-AUC

Comparación de costo computacional (tiempo y recursos)
