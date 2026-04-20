# Dataset Splits - Teen Mental Health

Este repositorio contiene la división (*splits*) de un dataset de salud mental en adolescentes, utilizada para prácticas de entrenamiento y evaluación de modelos de inteligencia artificial.

---

## ¿Qué son los splits?

Los *splits* son divisiones de un dataset en subconjuntos, normalmente:

* **Entrenamiento (train)** → para que el modelo aprenda
* **Prueba (test)** → para evaluar el desempeño

Esto permite medir qué tan bien generaliza el modelo y evita el sobreajuste (*overfitting*).

---

## Estructura del proyecto

```
📁 splits
 ├── X_train.csv
 ├── X_test.csv
 ├── y_train.csv
 └── y_test.csv
```

---

## Configuración usada

* **Proporción:** 80% entrenamiento / 20% prueba
* **Semilla:** 42
* **Método:** División aleatoria con `train_test_split`
* **Estrategia:** Estratificada (mantiene proporción de clases)

---

## Dataset utilizado

* **Nombre:** Teen Mental Health Dataset
* **Autor:** Muhammad Shahzad
* **Fuente:** Kaggle

---

## Créditos

El dataset original fue obtenido de:

Shahzad, M. (2026). *Teen Mental Health Dataset* [Conjunto de datos]. Kaggle.

Este repositorio **no es el creador del dataset**, solo utiliza los datos con fines educativos.

---

## Nota

Si deseas utilizar el dataset completo, se recomienda descargarlo directamente desde la fuente original en Kaggle.

---
