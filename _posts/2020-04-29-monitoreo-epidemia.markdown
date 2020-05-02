---
layout: post
title: 'Una Letra para Monitorear la Epidemia en Bolivia'
date: '2020-04-29T07:32:00.002-08:00'
authors:
- pablocuba
featured: images/Teaser-epidemia.jpg
tags:
- Pandemia
- Covid-19
categories:
- Bolivia
excerpt: Bolivia, al igual que otros países, va preparando planes para levantar las medidas de mitigación empleadas durante varias semanas para frenar la epidemia del coronavirus. ¿Cómo guiar la apertura en términos de alcance y velocidad? La respuesta no es clara, pero el riesgo es evidente. Por un lado, reactivar la actividad económica y social muy pronto aumenta la posibilidad de una segunda ola de infecciones y decesos. Por otro lado, ir muy lento y continuar con cuarentenas generalizadas y estrictas implica un costo elevado en términos de bienestar social y económico.
---

Bolivia, al igual que otros países, va preparando planes para levantar las medidas de mitigación empleadas durante varias semanas para frenar la epidemia del coronavirus. ¿Cómo guiar la apertura en términos de alcance y velocidad? La respuesta no es clara, pero el riesgo es evidente. Por un lado, reactivar la actividad económica y social muy pronto aumenta la posibilidad de una segunda ola de infecciones y decesos. Por otro lado, ir muy lento y continuar con cuarentenas generalizadas y estrictas implica un costo elevado en términos de bienestar social y económico. Para guiar el camino se necesitan datos de la progresión de infecciones junto a modelos matemáticos y estadísticos para analizar la evolución de la epidemia. A continuación, se ilustra un modelo aplicado a Bolivia que podría complementar la información existente y ayudar a la toma de decisiones.

La base del análisis epidemiológico moderno depende de una cantidad conocida como el número de reproducción, abreviado con la letra $$R$$. Este indicador representa el número de contagios derivados a partir de una persona infectada. Cuando se calcula al inicio de una epidemia, se conoce como número de reproducción básico, $$R_o$$, y está asociado a la fuerza inicial de la epidemia cuando toda una población es susceptible de contraer la enfermedad por ausencia de inmunidad natural o la falta de una vacuna.

En términos simples, si $$R$$ es mayor a 1, existe una epidemia en curso y la enfermedad se propaga rápidamente en la población. Mientras que si $$R$$ es menor que 1, la cantidad de nuevos casos disminuye rápidamente. Una vez que la dinámica de la epidemia entra en acción las medidas de mitigación se traducen en reducir R tanto como sea posible y las medidas de contención se traducen en mantener $$R$$ a un nivel menor a 1 de manera sostenida para detener la epidemia. Por tanto, para entender el cambio en la dinámica de contagio y juzgar la efectividad de medidas de mitigación y contención lo que nos interesa es la evolución del número de reproducción efectivo, $$R_t$$, durante el curso de la epidemia.

Por ejemplo, los modelos de Cori et.al. (2013)[^1] y Thompson et.al. (2019)[^2], combinan información sobre la incidencia diaria de una epidemia con un modelo probabilístico de la transmisibilidad de la enfermedad. La transmisibilidad, también conocida como intervalo serial, se resume a través de una distribución probabilística que se estima usando datos del tiempo de contagio entre dos casos relacionados. Si bien, información sobre el intervalo serial no está disponible para Bolivia, se puede usar estimados observados en otros países.[^3]

El siguiente gráfico muestra los resultados de la estimación de $$R_t$$ usando datos diarios de nuevos casos reportados entre el 21 de marzo y el 29 de abril en los tres principales departamentos de Bolivia: Santa Cruz, La Paz y Cochabamba. Los primeros ocho días de la muestra se utilizan para inicializar la estimación y los resultados se reportan a partir del 30 de marzo. Las líneas más oscuras corresponden a la media del valor estimado y las áreas sombrados reflejan la incertidumbre sobre el valor estimado.

# Gráfico 1: Número de Reproducción por Departamento
![Figura1](/assets/images/image003.jpg){:class="img-responsive"}

Los resultados se pueden resumir de la siguiente manera. Primero, el número de reproducción estimado al inicio de la muestra es aproximadamente igual a 2 en los tres departamentos. Consistente con el inicio de la dinámica exponencial de la epidemia y con un rango entre 1.25-3.5, un rango similar al estimado en el inicio del brote de coronavirus en otros países. Segundo, se observa una reducción en el número de reproducción efectivo a lo largo de la muestra, lo que es consistente con las medidas de aislamiento y la limitación al flujo interno y externo de personas que se impuso desde la segunda mitad de marzo. Si bien existe incertidumbre en la estimación, los resultados sugieren que las medidas de mitigación funcionan en la dirección esperada. Tercero, si bien se observa progreso en los tres departamentos, los resultados también muestran que la epidemia no está del todo contenida. Recordemos que lo que se necesita es mantener $$R_t$$ menor a 1. En dicho aspecto, se observan diferencias marcadas en la experiencia de los diferentes departamentos y un incremento en el numero de reproducción hacia el final de la muestra.


Vale la pena comparar la evolución del número de reproducción a nivel nacional con el de otros países para tratar de inferir algunas lecciones de su experiencia. El siguiente gráfico muestra los resultados de la estimación usando datos para Corea del Sur, Chile y Bolivia asumiendo la misma distribución para el intervalo serial. Se puede observar que, los primeros dos países, el número de reproducción se logró suprimir de manera bastante rápida. En el caso de Corea del Sur, el número de reproducción se mantiene menor a 1 y en el caso de Chile esta muy cerca de dicho umbral. Tanto Corea del Sur como Chile, han implementado una gran cantidad de pruebas de detección y desplegado muchos recursos para hacer seguimiento a las nuevas infecciones. Al tener mejor seguimiento de los casos, es posible que la información de monitoreo epidemiológico se reflejé en una menor incertidumbre alrededor de la estimación del número de reproducción. En contraste, la incertidumbre de las estimaciones para Bolivia puede reflejar una menor calidad de los datos reportados, limitaciones en el sistema de monitoreo y la falta de pruebas para poder identificar nuevos casos.  Adicionalmente, el acceso a pruebas no solo ayuda con la calidad del monitoreo desde el punto de vista epidemiológico, sino que también modifica el comportamiento de las personas. Aquellos que saben que están enfermos actúan de una manera diferente comparada con los que tienen duda de estar infectados. 


# Gráfico 2: Comparación Internacional

 ![Figura2](/assets/images/image004.jpg){:class="img-responsive"}

En síntesis, las medidas para mitigar la epidemia funcionan. Sin embargo, la falta de acceso a pruebas y la calidad de la información sugieren que Bolivia enfrenta mayor incertidumbre para guiar el camino a la apertura.  El análisis acá presentado solo pretende ser ilustrativo y debe tomarse con precaución. El dictamen sobre los modelos apropiados y la efectividad de las medidas recae en manos de los expertos en el campo de la epidemiologia y la salud pública. La experiencia de otros países muestra que mayor conocimiento sobre el progreso y el alcance de la epidemia son una herramienta vital para reducir la incertidumbre en la toma de decisiones. Finalmente, saber quien está infectado genera una externalidad positiva que necesitamos utilizar para ganar la batalla al coronavirus.


__Liberación de responsabilidad__: Las opiniones acá presentadas son totalmente personales y no implican ni representan ninguna de las instituciones con las que estoy o estuve afiliado.

__Referencias:__

[^1]: [1] Anne Cori, Neil M. Ferguson, Christophe Fraser and Simon Cauchemez, (2013). __"A New Framework and Software to Estimate Time-Varying Reproduction Numbers During Epidemics"__. American Journal of Epidemiology, Volume 178, Issue 9.

[^2]: [2] R.N. Thompson, J.E. Stockwin, R.D. van Gaalen, J.A. Polonsky, Z.N. Kamvar, P.A. Demarsh, E. Dahlqwist, S. Li, E. Miguel, T. Jombart, J. Lessler, S. Cauchemez, A. Cori, (2019).__"Improved inference of time-varying reproduction numbers during infectious disease outbreaks"__. Epidemics (29) 2019.

[^3]: [3] Hiroshi Nishiura, Natalie M. Linton, Andrei R. Akhmetzhanov, (2020).__"Serial interval of novel coronavirus (COVID-19) infections"__. International Journal of Infectious Diseases, Volume 93.


