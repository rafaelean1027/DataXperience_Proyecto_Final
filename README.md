# Localización de dispositivos mediante señales Wi-Fi

Proyecto final del curso Dataxperience de la Universidad EAN.

## Descripción

Este proyecto analiza mediciones de intensidad de señal recibida (RSSI) desde siete puntos de acceso Wi-Fi. El objetivo es identificar patrones en las señales y construir un modelo capaz de estimar en cuál de cuatro habitaciones se encuentra un dispositivo.

## Pregunta de análisis

¿Es posible determinar la ubicación de un dispositivo dentro de un espacio cerrado utilizando la intensidad de las señales recibidas desde diferentes puntos de acceso Wi-Fi?

## Dataset

Se utilizó el dataset **Wireless Indoor Localization** del repositorio UCI Machine Learning Repository.

El conjunto contiene:

- 2.000 observaciones.
- Siete mediciones RSSI: AP1 a AP7.
- Cuatro habitaciones.
- 500 observaciones por habitación.
- Sin valores faltantes ni registros duplicados.

Fuente:  
https://archive.ics.uci.edu/dataset/422/wireless+indoor+localization

## Herramientas utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Proceso realizado

1. Carga e inspección de los datos.
2. Revisión de valores faltantes y duplicados.
3. Cálculo de estadísticas descriptivas.
4. Análisis de valores atípicos.
5. Comparación de señales por habitación.
6. Análisis de correlaciones.
7. Entrenamiento de un árbol de decisión.
8. Evaluación mediante exactitud y matriz de confusión.

## Resultados principales

- AP1 y AP5 fueron las señales más importantes para el modelo.
- El modelo fue evaluado con 400 observaciones.
- Se obtuvieron 390 predicciones correctas y 10 incorrectas.
- La exactitud alcanzada fue del 97,50 %.

## Aplicación

Este enfoque puede servir como base para sistemas de localización de activos, análisis de cobertura inalámbrica, automatización de espacios y navegación dentro de edificios.

## Ejecución

1. Abrir el notebook en Google Colab.
2. Cargar el archivo `data/wifi_localization.txt` en el almacenamiento de la sesión.
3. Ejecutar las celdas en orden.

## Video de presentación

El video final del proyecto puede consultarse en el siguiente enlace:
https://universidadeaneduco-my.sharepoint.com/:f:/g/personal/rhernan23683_universidadean_edu_co/IgAlQUfgDDkbS5d3T1cbDZwsAREE-KqIPb4GtyZAgfWmSSw?e=6wJxzB

## Autor

Rafael Alejandro Hernandez Falla  
Estudiante de Ingeniería de Sistemas
