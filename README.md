# Challenge Telecom X Análisis de evasión de clientes - Parte 2
# 📊 Análisis de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) y desarrollar modelos predictivos que permitan identificar clientes con alto riesgo de abandono.

Se realizó un análisis exploratorio de datos, balanceo de clases y la implementación de dos modelos de Machine Learning para comparar su desempeño.

---

## 🧠 Objetivos

- Identificar las variables que más influyen en la cancelación de clientes.
- Construir modelos predictivos para anticipar el abandono.
- Comparar el desempeño de distintos modelos.
- Proponer estrategias de retención basadas en los resultados obtenidos.

---

## 🔍 Metodología

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Exploración y limpieza de datos.
2. Análisis de la proporción de cancelación.
3. Balanceo de clases mediante SMOTE.
4. Análisis de correlación.
5. Análisis dirigido:
   - Tiempo de contrato vs Cancelación.
   - Gasto total vs Cancelación.
6. Separación del conjunto de datos (70% entrenamiento / 30% prueba).
7. Creación y entrenamiento de modelos.
8. Evaluación de desempeño.
9. Análisis de importancia de variables.
10. Conclusión y recomendaciones estratégicas.

---

## 🤖 Modelos Implementados

### 🔹 Regresión Logística
- Requirió normalización de los datos.
- Presentó mejor recall en la clase de cancelación.
- Permite interpretar la influencia de cada variable mediante sus coeficientes.

### 🔹 Random Forest
- No requiere normalización.
- Mostró desempeño similar en exactitud.
- Permite analizar la importancia de las variables a través de la reducción de impureza.

---

## 📈 Resultados

- Exactitud aproximada: 77–78%.
- La Regresión Logística obtuvo mejor recall para clientes que cancelan.
- No se observaron indicios claros de overfitting.
- El desempeño general fue consistente entre ambos modelos.

---

## 📊 Principales Factores Asociados a la Cancelación

Las variables más relevantes identificadas fueron:

- ⏳ Tiempo de permanencia (Tenure)
- 📄 Tipo de contrato
- 💳 Cargos mensuales
- 💰 Gasto total acumulado

Se observó que clientes con menor antigüedad y contratos mensuales presentan mayor probabilidad de cancelación.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📌 Conclusión

El análisis permitió identificar patrones relevantes asociados al abandono de clientes y validar su impacto mediante modelos predictivos. La Regresión Logística resultó ser el modelo más adecuado en este contexto debido a su mejor desempeño en la detección de clientes en riesgo de cancelación.
