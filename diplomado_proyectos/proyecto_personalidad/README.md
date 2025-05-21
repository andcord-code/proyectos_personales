# Proyecto Análisis y Clasificación de Personalidad Psicológica

Este proyecto tiene como objetivo analizar y clasificar diferentes tipos de personalidad psicológica utilizando técnicas de machine learning sobre respuestas de una encuesta.

## Descripción del Dataset

El dataset contiene respuestas a una encuesta psicológica aplicada para identificar distintos tipos de personalidad, basados en categorías reconocidas en psicología (por ejemplo, MBTI).

### Columnas principales (ejemplos)

1. **Respuesta Id'**
2. **Haces nuevos amigos con regularidad'**
3. **Dedicas gran parte de tu tiempo libre a explorar diversos temas aleatorios que despiertan tu interes'**
4. **Ver a otras personas llorar puede hacer que tu tambien sientas ganas de llorar'**
5. **A menudo haces un plan de respaldo para tu plan de respaldo'**
6. **Por lo general, te mantienes tranquilo, incluso bajo mucha presion'**
7. **En los eventos sociales, rara vez intentas presentarte a nuevas personas y hablas principalmente con quienes ya conoces'**
8. **Prefieres terminar completamente un proyecto antes de comenzar otro'**
9. **Eres muy sentimental'**
10. **Te gusta usar herramientas de organizacion como horarios y listas'**
11. **Incluso un pequeno error puede hacerte dudar de tus habilidades y conocimientos en general'**
12. **Te sientes comodo acercandote a alguien que encuentras interesante e iniciando una conversacion'**
13. **No te interesa demasiado discutir diversas interpretaciones y analisis de obras creativas'**
14. **Tienes mas inclinacion a seguir tu razon que tu corazon'**
15. **Por lo general, prefieres hacer lo que sientes en un momento dado en lugar de planificar una rutina diaria especifica'**
16. **Rara vez te preocupas por la impresion que causas en las personas que conoces'**
17. **Disfrutas participar en actividades grupales'**
18. **Te gustan los libros y peliculas que te hacen crear tu propia interpretacion del final'**
19. **Tu felicidad proviene mas de ayudar a otros a lograr cosas que de tus propios logros'**
20. **Estas interesado en tantas cosas que te resulta dificil elegir que probar a continuacion'**
21. **Eres propenso a preocuparte de que las cosas empeoren'**
22. **Evitas los roles de liderazgo en entornos grupales'**
23. **Definitivamente no eres una persona artistica'**
24. **Crees que el mundo seria un lugar mejor si la gente confiara mas en la racionalidad y menos en sus sentimientos'**
25. **Prefieres hacer tus tareas antes de permitirte relajarte'**
26. **Disfrutas ver a la gente discutir'**
27. **Tienes tendencia a evitar llamar la atencion sobre ti mismo'**
28. **Tu estado de animo puede cambiar muy rapido'**
29. **Pierdes la paciencia con las personas que no son tan eficientes como tu'**
30. **A menudo terminas haciendo las cosas en el ultimo momento posible'**
31. **Siempre te ha fascinado la pregunta de que sucede despues de la muerte, si es que sucede algo'**
32. **Por lo general, prefieres estar rodeado de otras personas en lugar de estar solo'**
33. **Te aburres o pierdes interes cuando la discusion se vuelve demasiado teorica'**
34. **Te resulta facil empatizar con una persona cuyas experiencias son muy diferentes a las tuyas'**
35. **Por lo general, pospones la toma de decisiones finales el mayor tiempo posible'**
36. **Rara vez dudas de las decisiones que has tomado'**
37. **Despues de una semana larga y agotadora, un evento social animado es justo lo que necesitas'**
38. **Disfrutas ir a museos de arte'**
39. **A menudo te cuesta entender los sentimientos de otras personas'**
40. **Te gusta tener una lista de tareas diarias'**
41. **Rara vez te sientes inseguro'**
42. **Evitas hacer llamadas telefonicas'**
43. **A menudo pasas mucho tiempo tratando de entender puntos de vista muy diferentes al tuyo'**
44. **En tu circulo social, a menudo eres quien contacta a los amigos e inicia actividades'**
45. **Si tus planes se ven interrumpidos, tu maxima prioridad es volver a encarrilarte lo antes posible'**
46. **Todavia te molestan errores que cometiste hace mucho tiempo'**
47. **Rara vez contemplas las razones de la existencia humana o el significado de la vida'**
48. **Tus emociones te controlan mas de lo que tu las controlas'**
49. **Te esfuerzas mucho en no hacer quedar mal a las personas, incluso cuando es completamente su culpa'**
50. **Tu estilo de trabajo personal se parece mas a rafagas espontaneas de energia que a esfuerzos organizados y consistentes'**
51. **Cuando alguien piensa muy bien de ti, te preguntas cuanto tiempo tomara antes de que se sienta decepcionado'**
52. **Te encantaria un trabajo que requiera trabajar solo la mayor parte del tiempo'**
53. **Crees que reflexionar sobre cuestiones filosoficas abstractas es una perdida de tiempo'**
54. **Te sientes mas atraido por lugares con atmosferas bulliciosas y llenas de actividad que por lugares tranquilos e intimos'**
55. **Sabes a primera vista como se siente alguien'**
56. **A menudo te sientes abrumado'**
57. **Completas las cosas metodicamente sin omitir ningun paso'**
58. **Te intrigan mucho las cosas etiquetadas como controversiales'**
59. **Dejarias pasar una buena oportunidad si crees que otra persona la necesita mas'**
60. **Te cuesta cumplir con los plazos'**
61. **Te sientes seguro de que las cosas saldran bien para ti'**
62. **Personalidad**

## Tecnologías utilizadas

- **Python**  
- **Pandas** para manipulación de datos  
- **Matplotlib y Seaborn** para visualización  
- **Scikit-learn** para modelado y evaluación de clasificadores  
- **PrettyTable** para presentar resultados tabulados  
- **Jupyter Notebook** como entorno de desarrollo  

## Análisis y Modelado

El proceso realizado incluye:

- Carga y limpieza inicial de datos  
- Análisis exploratorio de las variables y distribuciones de tipos de personalidad  
- División del dataset en conjuntos de entrenamiento y prueba  
- Entrenamiento de modelos de clasificación: Árbol de Decisión y Random Forest  
- Optimización de hiperparámetros para mejorar el desempeño  
- Evaluación mediante métricas de clasificación como precisión, matriz de confusión y reporte detallado  

## Resultados

Los modelos lograron una clasificación con buen desempeño para los tipos de personalidad más comunes en la muestra, destacando la efectividad del modelo de Random Forest para esta tarea.

## Archivos

- **Datos_pr.csv**: Archivo con las respuestas de la encuesta utilizadas para el análisis.  
- **personalidad_psicologia.ipynb**: Notebook con el código y análisis completo.  

## Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.  
2. Asegurarse de tener Python 3 instalado y las librerías necesarias:  
   ```bash
   pip install pandas matplotlib seaborn scikit-learn prettytable
