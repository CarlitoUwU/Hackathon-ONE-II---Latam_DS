<h1 align="center">Sentiment API Google Colaboratory</h1>

---

## Índice

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Google Colaboratory](#google-colaboratory)
3. [EDA](#eda)
4. [TF-IDF](#tf-idf)
5. [Modelo de Aprendizaje](#modelo-de-aprendizaje)
6. [Joblib](#joblib)
7. [Conclusiones](#conclusiones)

---

## Descripción del Proyecto

Este proyecto implica trabajar con un conjunto de datos de respuestas a encuestas de satisfacción de clientes bancarios. El objetivo general es predecir el sentimiento en una serie de comentarios hechos por clientes y saber el sentimiento de estos, es decir, predecir si el comentarios es positivo, negativo o neutro.
Todo esto para dar una respuesta mas rapida y eficaz a todos lo malos comentarios y asi poder medir la satisfacción a lo largo del tiempo.

---

## Google Colaboratory

Para este proyecto hemos escogido la herramienta Google Colaboratory por su facilidad de uso y eficiencia.
Google Colab (Colaboratory) es un servicio gratuito de Google que permite escribir y ejecutar código Python en el navegador, funcionando como un cuaderno interactivo tipo Jupyter, ideal para aprendizaje automático y ciencia de datos, al ofrecer acceso a recursos computacionales potentes como GPUs y TPUs sin necesidad de instalación, solo con una cuenta de Google.

---

## EDA

El Análisis Exploratorio de Datos (EDA) es la fase inicial y crucial en ciencia de datos que usa gráficos y estadísticas para entender un conjunto de datos, revelando patrones, detectando anomalías, manejando datos faltantes y relaciones entre variables, antes de aplicar modelos complejos; su objetivo es descubrir información y guiar el análisis, no probar hipótesis.

---

## TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) es una medida estadística que evalúa la importancia de una palabra dentro de un documento en relación con una colección (corpus). Multiplica la frecuencia del término (TF) por la inversa de su frecuencia en los documentos (IDF) para resaltar palabras relevantes y descartar términos comunes. 
Componentes Principales:
TF (Term Frequency - Frecuencia de Término): Mide cuántas veces aparece una palabra en un documento específico. A mayor frecuencia, mayor relevancia en ese texto.
IDF (Inverse Document Frequency - Frecuencia Inversa de Documento): Mide qué tan rara o común es una palabra en todo el corpus. Palabras como "y", "el", "la" tienen un IDF bajo (baja importancia), mientras que palabras específicas tienen un IDF alto. 

---

## Modelo de Aprendizaje

Para este proyecto hemos decidio usar un modelo supervisado llamado Regresión Lógistica.
Este es un método de clasificación estadística que predice la probabilidad de un resultado binario (sí/no, 0/1) usando una función logística (sigmoidea) para mapear los resultados entre 0 y 1, independientemente de las variables predictoras, creando una curva en forma de 'S'. Se usa para modelar eventos donde la variable dependiente es categórica (ej. ¿el cliente pagará el préstamo? o ¿es spam el correo?) 

---

## Joblib

Joblib es un conjunto de herramientas de Python diseñado para hacer el procesamiento de datos más rápido y eficiente, especialmente en tareas de aprendizaje automático (machine learning) y computación científica. Su principal objetivo es simplificar la ejecución de tareas en paralelo y facilitar la persistencia (guardado) de objetos de Python grandes. 

---

## Conclusiones

Este fue el proceso utilizado por el equipo de Data Science encargado de realizar el modelo de aprendizaje.
Dentro del Colab se explica a detalle como fue el proceso paso a paso juntos con todos los temas que se expusieron arriba, en donde veremos desde como se escogieron y filtraron
las bases de datos hasta la prueba del modelo junto con los resultados.





