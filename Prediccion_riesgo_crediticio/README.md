# Proyecto Predicción de Riesgo Crediticio

Este proyecto tiene como objetivo desarrollar un modelo de machine learning para predecir el riesgo crediticio de clientes, ayudando a instituciones financieras a evaluar la probabilidad de incumplimiento de pagos.

## Descripción del Dataset

El dataset contiene información detallada de clientes y sus préstamos, con variables que describen características personales, financieras y crediticias, utilizadas para clasificar el riesgo de incumplimiento.

### Columnas del dataset

| Nombre de la Característica    | Descripción                                     |
| ------------------------------ | ---------------------------------------------- |
| **person_age**                 | Edad                                           |
| **person_income**              | Ingreso anual                                  |
| **person_home_ownership**      | Propiedad de vivienda                          |
| **person_emp_length**          | Años de empleo (duración del empleo)           |
| **loan_intent**               | Propósito del préstamo                         |
| **loan_grade**                | Calificación del préstamo                      |
| **loan_amnt**                 | Monto del préstamo                             |
| **loan_int_rate**             | Tasa de interés                               |
| **loan_status**               | Estado del préstamo (0: no impago, 1: impago) |
| **loan_percent_income**       | Porcentaje del ingreso destinado al préstamo  |
| **cb_person_default_on_file** | Historial de impago                            |
| **cb_person_cred_hist_length**| Duración del historial crediticio              |

## Tecnologías utilizadas

- **Python**  
- **Pandas** para manipulación de datos  
- **Matplotlib y Seaborn** para visualización  
- **Scikit-learn** para modelado y evaluación  
- **Jupyter Notebook** como entorno de desarrollo  

## Análisis y Modelado

Se realizó un análisis exploratorio para entender la distribución y las relaciones entre variables, seguido de:

- Limpieza y preprocesamiento de datos  
- Transformación de variables categóricas  
- División de datos en conjuntos de entrenamiento y prueba  
- Entrenamiento de modelos de clasificación como  regresión logística, árbol de decisión (Decision Tree Classifier), bosque aleatorio (Random Forest) y K-Nearest Neighbors  
- Evaluación mediante métricas: accuracy, precision, recall y F1-score  

## Resultados

El modelo Random Forest mostró el mejor desempeño, logrando un equilibrio adecuado entre precisión y recuperación, lo que es crucial para la predicción de riesgo crediticio.

## Archivos

- **dataset_credito.csv**: Datos utilizados en el proyecto.  
- **pred_riesg_crediticio.ipynb**: Notebook con todo el análisis y modelado.  

## Cómo ejecutar el proyecto

1. Clonar o descargar el repositorio.  
2. Instalar las dependencias necesarias:  
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
