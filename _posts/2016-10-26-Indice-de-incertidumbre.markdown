---
layout: post
title: 'Indice de Incertidumbre Económica: Medición e Impacto'
date: '2016-10-26T07:32:00.002-08:00'
authors:
- rodrigocerda
- alvarosilva
- josevalente
featured: images/Teaser-2016-10-26.png
categories:
- Macroeconomía
- Economía Internacional
tags: [Chile]
---
Si a usted le ofrecieran apostar 1000 dólares por el número que saldrá luego de arrojar un dado de seis caras, ¿Por cuál de estos lo haría? Dado que sabemos el universo de resultados posibles - 6 para este ejemplo - usted puede saber exactamente cuál es la probabilidad de acertar. En este caso, esto constituye una situación riesgosa, debido a que la probabilidad de que fallemos (5/6) o que ganemos (1/6), es perfectamente conocida. Si ahora, a usted le ofrecieran apostar 1000 dólares a cuál es el número de dados alguna vez creados por la humanidad, ¿aceptaría? ¿Tiene alguna idea de cuál es la probabilidad de acertar? Difícilmente y es poco probable que quién le esté ofreciendo la apuesta tenga también claridad sobre cuál es el número exacto. Estas situaciones son conocidas como situaciones de incertidumbre en la literatura económica.

Al menos desde Keynes, los economistas han argumentado que la incertidumbre juega un rol crucial en las decisiones de los agentes económicos. Por ejemplo, Bloom (2009) mostró que los episodios de incertidumbre podían tener impactos sobre variables reales como producción e inversión debido a que, enfrentados a un contexto incierto, las empresas y los hogares deciden posponer sus decisiones, lo que lleva a una caída de la actividad en el corto plazo. Una vez que la incertidumbre se ha disipado, estos realizan aquellas decisiones que habían pospuesto generando un alza sobre normal en la actividad, comúnmente llamada “efecto rebote”, recuperando las pérdidas de corto plazo.

Recientemente, [Baker, Bloom y Davis (2016)][BBD2016], en adelante BBD, han ido un paso más allá construyendo medidas de incertidumbre de política económica utilizando la búsqueda de palabras claves en artículos de prensa para diversas economías desarrolladas, con especial énfasis en EEUU. En Cerda, Silva y Valente (2016), usamos esta misma metodología dando un primer paso hacia la medición de la incertidumbre económica en Chile. A diferencia de BBD, nuestro índice tiene como objetivo medir el total de la incertidumbre económica no solo aquella derivada de políticas económicas. En este sentido, este índice puede capturar tanto incertidumbre externa como interna. Otro punto importante, dice relación con qué medidas de incertidumbre para países como Chile, donde los mercados financieros no se encuentran tan desarrollados o llevan poco tiempo en desarrollo, cobra vital relevancia toda vez que estos países emergentes tienden a exhibir al menos un tercio más de volatilidad que los países desarrollados (Bloom, 2014).

En concreto, el índice se basa en la cobertura que le ha dado el diario El Mercurio, principal medio de prensa del país, a los temas de incertidumbre económica a través del tiempo. Para estimar la cobertura, accedimos a los archivos digitales del diario, que contiene todos los artículos publicados por éste desde 1993 hasta 2015. Este archivo digital nos permitió contar el número de artículos que contenían referencias tanto a la economía como a la incertidumbre. En particular, se seleccionaron los artículos que contuvieran la palabra “incertidumbre” o “incierto” y alguna palabra que comenzara con “econ”, de manera de incluir palabras como economía, económico, economista y economistas.

Es importante notar que la cantidad de artículos publicados por el diario en cada mes puede variar, subestimando o sobreestimando la presencia de incertidumbre. Para ello, dividimos la serie mensual de artículos seleccionados por el número total de artículos publicados en cada uno de los meses. Finalmente, la serie resultante se divide por el promedio de ésta entre enero de 1993 y diciembre del 2015 y se multiplica por 100, con el objetivo de que la media de la serie resultante sea 100.

<iframe width="780" height="500" frameborder="0" scrolling="no" src="//plot.ly/~faro/109.embed"></iframe>

El panel A de la figura 1 presenta la evolución del Índice Histórico de Incertidumbre Económica de Chile (IEC Histórico). Como se puede apreciar, el nivel de incertidumbre ha variado considerablemente en las últimas décadas, donde los peaks reflejan la crisis asiática, la crisis financiera y la reciente contracción del mercado accionario chino. Con respecto a los eventos internos, tanto el envío de la reforma laboral impulsada por el gobierno de la Presidenta Bachelet durante el año 2015, como el terremoto del año 2010 fueron eventos donde se evidenció un incremento en la incertidumbre económica.

En el panel B y C de la figura 1 se presentan el comportamiento del índice contra el crecimiento anual del índice mensual de actividad económica (IMACEC) y el crecimiento anual de las importaciones de bienes de capital. Nótese que su correlación es negativa: comúnmente en periodos en que el índice de incertidumbre económica aumenta, tanto la actividad económica, medida por el IMACEC, como las importaciones de bienes de capital disminuyen.

Una pregunta interesante que surge es cuál es el impacto que tendrían los aumentos de la incertidumbre económica sobre variables relevantes como inversión y producción. En la figura 2 se presentan la simulación de la respuesta esperada de la inversión y el PIB ante un shock positivo de incertidumbre económica de una desviación estándar. Notar que dado el comportamiento observado de la serie, este es un shock conservador. Las dos especificaciones presentadas difieren tan solo en las variables ocupadas en el modelo utilizado para estimar ambas funciones. En particular, la especificación base considera un modelo VAR con ajuste por variables, mientras que la otra si toma en consideración ambas variables[^1]. Nótese que en ambos casos la respuesta es negativa: un shock positivo de incertidumbre disminuye tanto la inversión como el PIB. Adicionalmente, el efecto es más pronunciado en el caso de la inversión con una caída máxima de alrededor de un 3% versus una caída máxima del PIB de alrededor de un 1%. Un hecho interesante es que a pesar de mostrar efectos negativos en el corto plazo, no se evidencia la presencia de efecto rebote. Por ejemplo, la función impulso respuesta de la inversión nunca supera la barrera del cero, es decir, su impacto es siempre negativo. En el caso del PIB, a pesar de que muestra un valor positivo hacia el noveno trimestre, esto es solo un efecto leve, indistinguible de cero estadísticamente. El resultado anterior sugiere la no presencia de un efecto rebote, esto es: los efectos negativos de un shock de incertidumbre sobre la economía chilena podrían ser permanentes.

Lo anterior provee evidencia de que las dinámicas de ajuste de los agregados macroeconómicos ante shocks de incertidumbre en países emergentes, utilizando Chile como un punto de partida, podrían ser diferentes a aquellas observadas en países desarrollados. Para corroborar este resultado, se requieren sin embargo esfuerzos en la medición de la incertidumbre económica que nos permita cuantificar cuáles son sus efectos sobre las distintas economías en desarrollo. Con la construcción de este indicador para la economía chilena, esperamos haber dado un primer paso en esta dirección.

Los autores son economistas de Clapes UC de la Pontifica Universidad Católica de Chile

Material extendido disponible en: Clapes UC

# Referencias



[BBD2016]: "Baker, S, N. Bloom, and S. Davis, Measuring Economic Policy Uncertainty." The Quarterly Journal of Economics, Forthcoming.

[^1]: [1] Para más información sobre la construcción de estas funciones impulso-respuesta ver Cerda, Silva y Valente (2016).
