# 🌺 Clasificación de Especies de Iris: Proyecto MLP con CRISP-DM

Este repositorio contiene la implementación completa de un modelo de **Perceptrón Multicapa (MLP)** para clasificar las especies de flores de Iris, siguiendo el estándar metodológico **CRISP-DM** (Cross-Industry Standard Process for Data Mining).

El objetivo es demostrar la capacidad de una red neuronal simple para resolver un problema clásico de clasificación multiclase.

---

## 🚀 Estructura del Proyecto y Ciclo CRISP-DM

| Fase | Descripción | Archivos Relevantes |
| :--- | :--- | :--- |
| **1. Comprensión del Negocio** | Definición del objetivo (clasificación precisa > 95%). | README.md |
| **2. Comprensión de Datos** | Carga y exploración del dataset de Iris (150 muestras, 4 features). | `script_completo.py` (Sección 1) |
| **3. Preparación de Datos** | Escalado de features (StandardScaler) y codificación de etiquetas (One-Hot Encoding). | `script_completo.py` (Sección 2) |
| **4. Modelado** | Definición y entrenamiento del MLP con hiperparámetros ajustables. | `script_completo.py` (Sección 3) |
| **5. Evaluación** | Cálculo y visualización de la Matriz de Confusión y F1-Score. | **Gráficos Generados** |
| **6. Despliegue** | Exportación del modelo, escalador y etiquetas para producción. | **`iris_mlp_model.h5`, `iris_scaler.pkl`** |

---

## 🛠️ Requisitos e Instalación

Este proyecto requiere Python y las siguientes librerías de ciencia de datos y aprendizaje profundo:

1.  **Python 3.8+**
2.  **TensorFlow / Keras**
3.  **Scikit-learn**
4.  **Pandas, NumPy, Matplotlib, Seaborn**
5.  **Joblib** (para guardar el scaler)

Puedes instalar todas las dependencias usando `pip`:

```bash
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn joblib
