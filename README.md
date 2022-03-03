# Portafolio_Sergio

Portafolio de aplicaciones de distintas metodologías de Data Science en problemas del mundo real.

## [Proyecto 1: Redes Neuronales - Predicción de comportamiento de compra de cliente (link al código fuente)](https://github.com/SMolina-H/Proyectos/tree/main/Redes_Neuronales)

Este problema trata sobre predecir si un cliente volverá a realizar una compra en una tienda de audiolibros en base a su comportamiento histórico con la tienda utilizando Redes Neuronales.

Para lo anterior se cuenta con una base de datos que contiene 2 años de recolección de datos de cada cliente, y para ver si un cliente volvió a comprar en la tienda se utilizaron 6 meses adicionales de observación, así, se predecirá si un cliente volverá a realizar una compra dentro de dichos 6 meses.

Se tiene la siguiente informacion de cada cliente:
<ul>
 
<li>Target (1 si compró en los ultimos 6 meses, 0 en caso contrario) ------------> Variable a predecir</li>
    
<li>ID de cliente</li>
    
<li>Suma de duración en minutos de todos sus libros</li>

<li>Duración promedio de cada libro</li>

<li>Suma de dinero total pagada por todos los libros</li>

<li>Precio promedio pagado por cada libro</li>

<li>Review (1 si el cliente dejó review, 0 en caso contrario)</li>

<li>Nota de review promedio de libros (escala de 1 al 10)</li>

<li>Minutos totales escuchados</li>

<li>Porcentaje completado del último libro</li>

<li>Tiempo transcurrido desde la primera compra y última vez que abrió el libro</li>
 
</ul>

![](/img/Precision_modelo.png) ![](/img/red_neuronal.png)

## [Proyecto 2: Regresión Lineal Multivariada - Predicción de precios de automóviles (link al código fuente)](https://github.com/SMolina-H/Proyectos/tree/main/Regresion_lineal_multivariada)

Se utilizó un modelo de Regresión Lineal Múltiple para predecir el valor del precio de distintos automóviles en base a sus distintas características.

Se contó con una base de datos que contiene las siguientes entradas de cada vehículo:

<ul>
    <li>Precio ------------> Variable a predecir</li>
    <li>Marca</li>
    <li>Tipo</li>
    <li>Millas recorridas</li>
    <li>Motor</li>
    <li>Tipo de motor</li>
    <li>Año</li>
    <li>Modelo</li>    
</ul>

![](/img/Regresion.png)

## [Proyecto 3: Regresión Logística - Predicción de admisión de un estudiante a una universidad (link al código fuente)](https://github.com/SMolina-H/Proyectos/tree/main/Regresion_logistica)

Se utiliza el modelo de Regresión Logística para predecir si un alumno es admitido o rechazado en una universidad en base a su sexo y rendimiento en el Examen de Aptitud Académica para ingresar a una universidad.

Se cuenta con una base de datos que contiene las siguientes entradas de cada alumno:

<ul>
    <li>Admitido ------------> Variable a predecir</li>
    <li>Puntaje Examen de Aptitud Académica (SAT)</li>
    <li>Género</li>    
</ul>

![](/img/Matriz_de_confusion_1.png)

## [Proyecto 4: Clustering - Segmentación de especies de plantas Iris con análisis de grupos (link al código fuente)](https://github.com/SMolina-H/Proyectos/tree/main/Clustering)

El dataset de las plantas Irirs es uno de los más populares en Machine Learning. Para este caso se realizó un análisis de grupos para segmentar los distintos tipos de especies de la planta Iris de acuerdo a las medidas de sus pétalos y sépalos.

El conjunto de datos contiene las siguientes entradas para cada planta observada:

<ul>
    <li>Largo del sépalo</li>
    <li>Ancho del sépalo</li>
    <li>Largo del pétalo</li>   
    <li>Ancho del pétalo</li>
</ul>

![](/img/Clustering.png)
