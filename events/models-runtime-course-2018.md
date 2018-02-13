---
title: Curso "La computación autónoma desde la perspectiva de los Modelos en tiempo de Ejecución" - Red MDE
---

# Curso "La computación autónoma desde la perspectiva de los Modelos en tiempo de Ejecución"

## Presentación 

![Una fotografía del curso](https://mde-network.github.io/img/ModelsRuntime-Feb6.jpg "Fotografía del curso")

El curso *"La computación autónoma desde la perspectiva de los Modelos en tiempo de Ejecución"* fue organizado por la red MDE y fue impartido por Joan Fons (UPV) en Barcelona el 6 de febrero de 2018.

## Materiales del curso
1. [Parte 1 - Los modelos en tiempo de ejecución](https://mde-network.github.io/docs/courses/models-runtime/Parte1-Modelos_Tiempo_Ejecucion.pdf)
2. [Parte 2 - La Computación Autónoma](https://mde-network.github.io/docs/courses/models-runtime/Parte2-Computacion_Autonoma.pdf)
3. [Parte 3 - Ejemplos y Ámbitos de Aplicación](https://mde-network.github.io/docs/courses/models-runtime/Parte3-Ejemplos-Aplicaciones.pdf)

## Resumen 
Tradicionalmente, los enfoques de desarrollo de software dirigidos por modelos (DSDM) utilizan los modelos como los artefactos principales con los que diseñar, probar e implementar sistemas software. Una vez desarrollada la solución (típicamente a través de generación de código/transformaciones M2T), el software satisface un modelo concreto, inmutable y del que no es 'consciente'.

Existe una línea de trabajo desde hace más de 10 años que propone el uso de estos modelos también en tiempo de ejecución (Models@run-time ó M@rt). El hecho de usar estos modelos en tiempo de ejecución aporta beneficios interesantes al software al dotarlo del conocimiento con el que fue construído y tener una visión conceptual de sí mismo (introspección). Se le dota al software de la posibilidad de, a través de esta nueva capacidad de introspección y la realización de operaciones con estos modelos, entender, verificar, decidir, etc. por sí mismo y en tiempo de ejecución, cómo debe reaccionar frente a situaciones concretas. Esto abre la posibilidad de desarrollar software con capacidades adaptación dinámicas y de computación autónoma. En estos sistemas, tanto el sistema como los modelos que los representan cambian a la par (en tiempo de ejecución) de manera coordinada. 

En este curso se aplicarán estos principios para desarrollar software auto-adaptativo. Este tipo de sistemas se caracteriza por ser capaces de cambiar/mutar en función de su entorno, de su contexto de operación. Siguiendo una aproximación basada en bucles de control (que mostraremos en el curso), se mostrará cómo diseñar y desplegar este tipo de soluciones adaptativas usando M@rt. Haremos uso de la herramienta PROTeus Tool desarrollada por el grupo TaTami en el Centro PROS de la Universitat Politècnica de València. Esta herramienta sigue un enfoque DSDM en el que: 1) propone un DSL para describir sistemas auto-adaptativos, 2) implementa operaciones de manipulación y validación de modelos de sistemas adaptativos, y 3) permite desarrollar (mediante generación de código) soluciones funcionales sobre el framework de adaptación PROTEus FW haciendo uso de técnicas M@rt. Desarrollaremos varios ejemplos prácticos/aplicados en el ámbito de la Internet de las Cosas y las Ciudades Inteligentes, y realizaremos operaciones sobre los M@rt usando la herramienta.

## Ponente

![Joan Fons](https://mde-network.github.io/img/JoanFons.png "Joan Fons"){ float: left; }
[Joan Fons](http://www.pros.webs.upv.es/members/joan-fons/) es profesor Contratado Doctor en la [Universidad Politécnica de Valencia](http://www.upv.es/) desde el 2001. Alcanzó el grado de Doctor en el 2008, en el ámbito del desarrollo MDD y la Ingeniería Web.

Es miembro del [Centro PROS](http://www.pros.webs.upv.es/), en el que trabaja en temas relacionados con la Inteligencia Ambiental y Computación Ubicua, la Internet de las Cosas y la Computación Autónoma, la Ingeniería Web y el Desarrollo Dirigido por Modelos. Ha publicado más de 60 artículos, incluyendo artículos en revistas como Computer, IEEE Pervasive Computing o Personal and Ubiquitous Computing, además de las conferencias más relevantes en su área de trabajo.

Ha participado activamente en proyectos Europeos tanto FP7 y como ITEA durante más de 10 años. Desde el 2006, trabaja y lidera proyectos de transferencia a empresa con empresas locales y organizaciones públicas.
