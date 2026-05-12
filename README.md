# NLP Intent Classifier - Data Science 3

Este proyecto implementa una **Red Neuronal Profunda (MLP)** para la clasificación de intenciones en lenguaje natural, basada en un dataset de interacciones reales con IA.

## 🚀 Pipeline del Proyecto
1. **ETL:** Limpieza de texto con Regex y remoción de ruido de sistema.
2. **Label Engineering:** Categorización en 7 ejes estratégicos (DS, Marketing, Social, etc.).
3. **NLP Preprocessing:** Tokenización de 10k palabras y Padding de secuencias.
4. **Deep Learning:** Arquitectura con capas de **Embedding**, **GlobalAveragePooling** y **Dropout**.

## 📊 Resultados
* **Accuracy Global:** 83%
* **F1-Score (Taeko Marketing):** 0.71
* **F1-Score (Data Science):** 0.67

> **Nota:** El dataset incluido en `/data` es sintético para preservar la privacidad de la información original.
