# Proyecto EDA_banco

Este proyecto está enfocado en la exploración de datos de una campaña de marketing telefónico realizada por una entidad bancaria. El objetivo de la campaña es contactar a posibles clientes y determinar si están interesados en adquirir un certificado de depósito a término con el banco.

## Descripción del Dataset

El dataset utilizado contiene información de 45,215 registros, con las siguientes 17 características:

1. **age**: Edad (numérica)
2. **job**: Tipo de trabajo (categórica: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services")
3. **marital**: Estado civil (categórica: "married", "divorced", "single")
4. **education**: Nivel educativo (categórica: "unknown", "secondary", "primary", "tertiary")
5. **default**: Si dejó de pagar sus obligaciones (categórica: "yes", "no")
6. **balance**: Saldo promedio anual en euros (numérica)
7. **housing**: ¿Tiene o no crédito hipotecario? (categórica: "yes", "no")
8. **loan**: ¿Tiene créditos de consumo? (categórica: "yes", "no")
9. **contact**: Medio a través del cual fue contactado (categórica: "unknown", "telephone", "cellular")
10. **day**: Último día del mes en el que fue contactado (numérica)
11. **month**: Último mes en el que fue contactado (categórica: "jan", "feb", "mar", ..., "nov", "dec")
12. **duration**: Duración (en segundos) del último contacto (numérica)
13. **campaign**: Número total de veces que fue contactado durante la campaña (numérica)
14. **pdays**: Número de días transcurridos después de haber sido contactado antes de la campaña actual (numérica. -1 indica que no fue contactado previamente)
15. **previous**: Número de veces que ha sido contactado antes de esta campaña (numérica)
16. **poutcome**: Resultado de la campaña de marketing anterior (categórica: "unknown", "other", "failure", "success")
17. **y**: ¿El cliente se suscribió a un depósito a término? (categórica: "yes", "no")

## Tecnologías utilizadas

- **Python**
- **Pandas**: Para la manipulación y análisis de datos.
- **Scikit-learn (sklearn)**: Para transformar variables categóricas a numéricas.
- **Matplotlib y Seaborn**: Para la creación de gráficos y visualizaciones.

## Análisis y Visualización

El análisis exploratorio de datos (EDA) se realizó para obtener una visión más profunda sobre los patrones en los datos. Los resultados de las gráficas generadas están disponibles en el notebook, incluyendo:

- Distribución de edades y saldo promedio.
- Relación entre la variable de interés "y" (suscripción a un depósito a término) y otras variables categóricas como "job", "education", "marital", "default", "housing", "loan" y "poutcome".
- Gráficos de barras, histogramas y diagramas de dispersión.

## Archivos

- **dataset_banco.csv**: El archivo de datos utilizado en este proyecto.
- **eda_banco.ipynb**: El notebook con el código y análisis realizado.

## Cómo ejecutar el proyecto

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener Python instalado en tu entorno local.
3. Instala las dependencias necesarias:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
