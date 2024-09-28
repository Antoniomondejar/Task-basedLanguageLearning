# Generación de tareas para aprendizaje de inglés a partir de textos 
*Antonio Mondejar y Martín Piloni*

*Universidad Nacional de Córdoba, Facultad de Matemática, Astronomía, Física y Computación*

## Abstract

Se buscará desarrollar una herramienta enfocada en facilitar las tareas de enseñanza de la lengua inglesa para estudiantes de nivel inicial. 

Esta herramienta deberá generar automáticamente distintas tareas a partir de textos mediante el uso de modelos de lenguaje. El principal objetivo es lograr que la herramienta genere preguntas y respuestas de compresión lectora y, eventualmente, se buscará que pueda también generar nuevos tipos de tareas tales como *fill in the blanks* y crucigramas.

Este proyecto busca complementar la labor docente, ayudando a los mismos a crear fácilmente actividades para la práctica del idioma, ahorrandoles tiempo y esfuerzo.


## Hipótesis

Como hipótesis esta herramienta:

* Generará preguntas y respuestas de compresión lectora a partir de un texto en inglés que serán **útiles** para el aprendizaje del idioma.

* Generará tareas de otros tipos con una eficacia menor en comparación con las preguntas y respuestas de comprensión lectora para asistir en el aprendizaje de la lengua.

Respecto al conjunto de datos:

* Debido a la falta de datasets con textos en inglés de nivel inicial, se espera que la herramienta enfrentará problemas a la hora de generar preguntas y respuestas adecuadas para este nivel.

## Objetivos preliminares

* Desarrollar una herramienta de generación de preguntas y respuestas de comprensión lectora en inglés para estudiantes de nivel inicial que pueda adaptarse a distintos textos.

* Conseguir que la herramienta genere otras tareas para el aprendizaje del idioma que tengan cierto nivel de calidad.

* Mejorar la eficiencia y efectividad en la creación de materiales educativos para la enseñanza del inglés.

## Técnicas a utilizar

* Modelos de lenguaje, para la generación de texto que será útil en todas las tareas que abarca la herramienta.

* Fine tuning, para adaptar los modelos de lenguajes preentrenados al conjunto de textos seleccionado.

* Coreference resolution, que ayudará a encontrar todas las expresiones que refieren a la misma entidad dentro de un y reemplazarlas por una única identificación de la misma.

* Semantic Role Labeling, para etiquetar palabras en el texto según su rol semántico, que en la tarea de generación de preguntas y respuestas ayudará a determinar si una palabra es candidata a respuesta.


## Planificación

*

## Referencias


* Martín Morón, Joaquín Scocozza, Luis Chiruzzo, Aiala Rosá. (2021). A tool for automatic question generation for teaching english to beginner students.
* Luis Chiruzzo, Laura Musto, Santiago Góngora, Brian Carpenter, Juan Pablo Filevich, Aiala Rosá. (2022). Using NLP to Support English Teaching in Rural Schools.
* Tatiana Rischewski, Gonzalo Berger, Luis Chiruzzo, Aiala Rosá. (2022). Generación de preguntas y respuestas para comprensión lectora en inglés utilizando modelos neuronales. 
* Alexander Maas, Kazunori D Yamada, Toru Nagahama, Taku Kawada, Tatsuya Horita. (2024). Question Generation for English Reading Comprehension Exercises using Transformers.