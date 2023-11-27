# Fundamentos del Procesamiento de Lenguaje Natural
<img src="Banner_CEEE.jpeg">

## **Introducción**


El lenguaje natural representa uno de los ingredientes claves en el desarrollo de los seres humanos. La capacidad de interactuar con otra personas ha permitido la interacción y cooperación en función de la expresión de pensamientos y sentimientos por medio de la palabra.

Este hecho, ha sido fundamental en nuestra evolución como especie, y por lo tanto, no es de extrañar que tenga bondades similares para la interacción entre seres humanos y máquinas. En este curso se abordará el procesamiento de lenguaje natural con algoritmos reproducidos por máquinas (NLP), esta característica otorga mejoras en la capacidad de procesamiento de dichas máquinas, y facilita enormemente la interacción con las personas.

La inteligencia artificial esta abriendo un sin número de posibilidades en el campo del procesamiento de información. En años anteriores, eran propias de esta área del conocimiento tareas de clasificación, regresión y clasificación, sin embargo, recientemente se han añadido otras posibilidades como la generación (más conocida como generativa IA). 

Este nueva habilidad computacional abre posibilidades para que máquinas ejecuten programas y generen información contenida por ejemplo en señales de voz, imágenes modificadas, textos para diferentes fines, videos, presentaciones,  correos electrónicos, entre otras tantas posibilidades. 

Es de esperar que la generación de información utilizando máquinas genere incertidumbre en las personas, no estamos acostumbrados a escuchar noticias creadas por un algoritmo, leer un correo electrónicos escrito por un computador, o leer una guion hecho sin la intervención del libretista; es una nueva realidad pero también representa un espectro amplio de posibles nuevas aplicaciones.

Las tareas de la inteligencia artificial inicialmente fueron de clasificación, regresión y agrupamiento. Desde hace más de 40 años se han propuesto varios modelos para hacer estas tareas, entre estos se encuentran vecinos cercanos, arboles de decisión, Naive-Bayes, regresión logística, máquinas de soporte vectorial y perceptrón multicapa. Es precisamente este último clasificador, el que dio inicio a las redes neuronales que hoy conocemos dentro de lo que se llama Deep Learning. 

---
**¿Y de los sistema de Procesamiento de Lenguaje Natural?**


Dentro del grupo de aplicaciones  del Procesamiento de Lenguaje Natural NLP son:

* Análisis de sentimiento en texto (películas, poesías, guiones, etc.).
* Análisis de contenido de correo y detección de spam.
* Categorización de contenido.
* Conversión de habla a texto y texto a habla.
* Resumen de documentos.
* Traducción entre idiomas.
* ...
Esta es un pequeña lista de un amplio espectro de posibilidades. De otro lado, para la creación de una solución con NLP se debe tener en cuenta el flujo de trabajo que aparece en la siguiente figura.
Flujo de trabajo
<img src="FlowwarodNLP.png">


Las tareas se pueden resumir asi:
La primera tarea es tener el texto que se utilizará para entrenar el sistema inteligente. Generalmente se constituye lo que se conoce como un Dataset.
El paso siguiente es la caracterización del mismo y para ello existen varias alternativas de embedding (puede ser por letras, palabras o frases).  La creación del modelo es un proceso algo artístico donde se pueden proponer varias arquitecturas de redes neuronales con el  mismo fin; generar texto a partir del texto del dataset. 
Cuando se tiene un modelo propuesto y los datos de entrenamiento es hora de ajustar sus parámetros. También existen diferentes alternativas para hacer este entrenamiento y son recogidas en lo que se conoce como hiperparámetros. Finalmente la implementación del modelo puede ir desde el mismo computador hasta una board de prestaciones reducida como por ejemplo Raspberry Pi, Nvidia.


Todas la etapas del flujo de trabajo explicado en el párrafo anterior se pueden llevar a cabo en un entorno integrado de desarrollo (IDE). Existen diferentes opciones sin embrago la más práctica, y que utilizaremos en este curso, es la de Colabority de Google (Colab-Google). En las siguientes secciones hablaremos tanto del lenguaje de programación utilizado en el diseño de las redes neuronales (Python) y del entorno de desarrollo a utilizar en este curso

[texto del enlace](https://www.youtube.com/watch?v=PLdecwVnewc)

Esta es una prueba


