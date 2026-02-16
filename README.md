# 📊 Comparación de Algoritmos de Clasificación

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🎯 Descripción del Proyecto

Este proyecto realiza un **análisis comparativo exhaustivo** de tres algoritmos de clasificación de Machine Learning utilizando el dataset real **Breast Cancer Wisconsin**. El objetivo es evaluar y comparar el rendimiento de diferentes modelos para la detección de tumores malignos y benignos.

### 📚 Algoritmos Evaluados

1. **K-Nearest Neighbors (KNN)** - Clasificador basado en proximidad
2. **Support Vector Machine (SVM)** con kernel RBF - Separación mediante hiperplanos óptimos
3. **Random Forest** - Ensemble de árboles de decisión

## 🔬 Dataset

**Breast Cancer Wisconsin (Diagnostic Dataset)**
- 🔢 **569 muestras** de tumores de mama
- 📊 **30 características numéricas** extraídas de imágenes digitalizadas
- 🎯 **Clasificación binaria:**
  - `0` = Maligno (canceroso)
  - `1` = Benigno (no canceroso)

## 🚀 Características del Análisis

### ✨ Preprocesamiento
- Estandarización de características con `StandardScaler`
- Reducción dimensional con PCA (2 componentes) para visualización
- División estratificada: 75% entrenamiento / 25% prueba

### 📈 Métricas de Evaluación
- **Accuracy** - Precisión general del modelo
- **Precision** - Exactitud de predicciones positivas
- **Recall** - Sensibilidad del modelo
- **F1-Score** - Media armónica entre precision y recall
- **AUC-ROC** - Capacidad de discriminación del modelo

### 📊 Visualizaciones
- ✅ Fronteras de decisión en espacio 2D (PCA)
- ✅ Curvas ROC comparativas
- ✅ Matrices de confusión detalladas
- ✅ Reportes de clasificación completos

## 🛠️ Instalación y Uso

### Requisitos Previos

```bash
Python 3.8 o superior
```

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/comparacion-algoritmos.git
cd comparacion-algoritmos
```

### 2. Instalar dependencias

```bash
pip install -r requirements.txt
```

O instalar manualmente:

```bash
pip install scikit-learn pandas matplotlib seaborn jupyter
```

### 3. Ejecutar el notebook

```bash
jupyter notebook Comparación_de_Algoritmos.ipynb
```

O usar JupyterLab:

```bash
jupyter lab Comparación_de_Algoritmos.ipynb
```

## 📂 Estructura del Proyecto

```
comparacion-algoritmos/
│
├── Comparación_de_Algoritmos.ipynb  # Notebook principal con todo el análisis
├── README.md                         # Documentación del proyecto
├── requirements.txt                  # Dependencias del proyecto
└── .gitignore                        # Archivos ignorados por Git
```

## 🎓 Secciones del Notebook

El notebook está organizado en **11 secciones** profesionales:

1. **Instalación de Dependencias e Importaciones**
2. **Carga y Exploración del Dataset**
3. **Preprocesamiento y Reducción Dimensional**
4. **División de Datos: Entrenamiento y Prueba**
5. **Definición de Modelos**
6. **Entrenamiento y Evaluación de Modelos**
7. **Comparación de Métricas**
8. **Visualización de Fronteras de Decisión**
9. **Curvas ROC**
10. **Matrices de Confusión y Reportes Detallados**
11. **Conclusiones y Recomendaciones**

Cada sección incluye:
- 📝 Celdas Markdown explicativas con contexto y teoría
- 💻 Código Python limpio y bien documentado
- 📊 Visualizaciones profesionales
- ✅ Salidas interpretadas

## 🏆 Resultados Esperados

El notebook genera automáticamente:

- **Tabla comparativa** con todas las métricas de rendimiento
- **Identificación del mejor modelo** según AUC
- **Visualizaciones interactivas** de fronteras de decisión
- **Análisis detallado** con matrices de confusión
- **Recomendaciones** para mejoras futuras

## ⚠️ Limitaciones y Consideraciones

- La reducción a 2 componentes PCA se realiza únicamente para **visualización**
- No se incluye ajuste de hiperparámetros (Grid Search)
- Para producción, se recomienda entrenar con las 30 características originales
- Los falsos negativos son críticos en aplicaciones médicas

## 🔮 Mejoras Futuras

- [ ] Implementar validación cruzada (K-Fold Cross-Validation)
- [ ] Optimización de hiperparámetros con GridSearch/RandomSearch
- [ ] Evaluar modelos adicionales (XGBoost, Neural Networks)
- [ ] Análisis de importancia de características
- [ ] Implementar técnicas de balanceo de clases
- [ ] Despliegue del mejor modelo con Flask/FastAPI

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📚 Referencias

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

## 🙏 Agradecimientos

- Dataset proporcionado por UCI Machine Learning Repository
- Comunidad de scikit-learn
- Recursos educativos de Machine Learning

---

⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub!

**Desarrollado con ❤️ para la comunidad de Machine Learning**

