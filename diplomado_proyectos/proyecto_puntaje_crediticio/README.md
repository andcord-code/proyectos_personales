# Proyecto Predicción de Puntaje Crediticio

Este proyecto tiene como objetivo construir modelos de deep learning y de machine learning para predecir el puntaje crediticio de clientes en instituciones bancarias.

## Descripción del Dataset

El dataset utilizado contiene información de clientes, sus características financieras, personales y de crédito, con el fin de predecir su puntaje crediticio.

### Columnas principales

1. **age**
2. **annual_income**
3. **monthly_inhand_salary**
4. **total_emi_per_month**
5. **num_bank_accounts**
6. **num_credit_card**
7. **interest_rate**
8. **num_of_loan**
9. **num_of_delayed_payment**
10. **outstanding_debt**
11. **credit_utilization_ratio**
12. **amount_invested_monthly**
13. **monthly_balance**
14. **credit_score**

## Tecnologías utilizadas

- **Python**  
- **Pandas** para manipulación de datos  
- **Matplotlib y Seaborn** para visualización  
- **Keras** para el modelado de redes neuronales y su evaluación
- **Scikit-learn** para modelado y evaluación  
- **Jupyter Notebook** como entorno de desarrollo  

## Análisis y Modelado

Se realizó un pre procesamiento de los datos, seguido por:

- Selección de caracteristicas relevantes y el target  
- Transformacion del target a valores numéricos
- Limpieza de datos  
- División de los datos en conjuntos de entrenamiento y prueba  
- Entrenamiento de redes neuronales con Keras y entrenamiento de modelos supervisados como SVM y KNN   
- Evaluación de modelos con métricas como accuracy

## Resultados

El modelo K-Nearest Neighbors KNN fue el más efectivo para predecir el puntaje crediticio de las personas.

## Archivos

- **dataset**: https://raw.githubusercontent.com/delveeducation/datasets/refs/heads/main/credit_score.csv.  
- **puntaje_crediticio_proyecto.ipynb**: Notebook con el análisis completo y modelado.  

## Cómo ejecutar el proyecto

1. Clonar o descargar el repositorio.  
2. Instalar las dependencias necesarias:  
   ```bash
   pip install pandas scikit-learn tensorflow matplotlib seaborn
