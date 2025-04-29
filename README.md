# YIAuto-MPG-Dataset.
# 🚗 Predicción de Eficiencia de Autos usando Redes Neuronales

Este proyecto desarrolla un modelo de red neuronal capaz de predecir la eficiencia de automóviles (expresada en millas por galón, **MPG**) basado en características técnicas como:

- Número de cilindros
- Desplazamiento
- Caballos de fuerza (horsepower)
- Peso
- Aceleración
- Año del modelo
- Origen

Se utilizó el **conjunto de datos Auto MPG** proporcionado por el repositorio UCI Machine Learning.

---

## 📚 Contenido

- **Carga y limpieza de datos**:  
  Reemplazo de valores faltantes y creación de variables dummy para las variables categóricas.

- **Preparación de datos**:  
  Normalización de los datos con `MinMaxScaler` y división en conjuntos de entrenamiento y validación.

- **Construcción del modelo**:  
  Una red neuronal de tipo `Sequential` con varias capas densas.

- **Entrenamiento**:  
  Se compararon distintos optimizadores: `Adam`, `SGD`, `RMSprop`.

- **Evaluación**:  
  Uso de métricas como:
  - Error Absoluto Medio (**MAE**)
  - Error cuadrático medio (**MSE**)
  - Coeficiente de determinación (**R²**)

- **Visualización de resultados**:  
  Gráficas del comportamiento de pérdida y error durante el entrenamiento.

---

## 🚀 Tecnologías utilizadas

- Python 3
- Pandas
- Scikit-learn
- TensorFlow/Keras
- Matplotlib

---

## 📂 Organización del proyecto

```plaintext
miniproyecto_RNADL.ipynb   # Notebook principal del proyecto

