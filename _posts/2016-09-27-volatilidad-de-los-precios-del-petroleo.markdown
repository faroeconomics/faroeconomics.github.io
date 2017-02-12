---
layout: post
title: 'Volatilidad de los precios del petróleo y crisis globales: Una relación causal bidireccional'
date: '2016-09-27T07:32:00.002-08:00'
authors:
- juanzuleta
featured: images/Teaser-2016-09-27.png
tags:
- Economía Internacional
- Macroeconomía
categories:
- Internacional
---
De acuerdo con un reciente análisis del Fondo Monetario Internacional (FMI), “la considerable incertidumbre acerca de la trayectoria de los precios del petróleo en el futuro y los determinantes subyacentes de la disminución de los precios han añadido una nueva dimensión de riesgo para las perspectivas de crecimiento global”. En la Figura 1 se presentan datos de volatilidad de los precios West Texas Intermediate (WTI) del petróleo (medida por su coeficiente de variación, en porcentaje)[^1] y crecimiento de la economía mundial (aproximado por el crecimiento del producto interno bruto real de Estados Unidos, en porcentaje) para el período comprendido entre el primer trimestre de 1986  y el segundo trimestre de 2016, donde se puede apreciar una relación negativa entre ambas variables.


En este estudio hago seguimiento a dos contribuciones anteriores con respecto a esta conexión, que se pueden encontrar en este enlace y en este otro. A diferencia de tales intentos, aquí uso datos trimestrales (en lugar de anuales) para volver a estimar una relación de causalidad de Granger entre coeficientes de variación del precio del petróleo, según la cotización WTI, (CDV_WTI) y el crecimiento del producto interno bruto real de Estados Unidos (CR_PIBR_EU). Los datos trimestrales están dirigidos a capturar los efectos estacionales no visualizados en la información anual. De acuerdo con prácticas econométricas estándar, esto requiere realizar: (1) pruebas de estacionariedad de las dos variables para encontrar su orden de integración; (2) una comprobación de cointegración para ver si las variables son integradas de orden uno; y (3) pruebas de causalidad de Granger.

<div class="frame-container">
<iframe frameborder="0" scrolling="no" src="//plot.ly/~faro/101.embed"></iframe>
</div>

Como se ve en la Tabla 1, las dos variables son esencialmente estacionarias (o integradas de orden 0). En consecuencia, no hay necesidad de diferenciación de las variables y, debido a que no comparten una tendencia común, tampoco pueden estar cointegradas. Así, para la prueba de causalidad de Granger se puede proceder de tres maneras: (A) utilizar las variables tal como son en las ecuaciones de causalidad; (B) incluir una variable de tendencia temporal en las regresiones; y (C) extraer la tendencia temporal de las variables realizando una regresión de cada una de ellas (si corresponde) con respecto al tiempo y usar sus residuos respectivos en las regresiones[^2]. Por último, en cada regresión de causalidad, necesitamos llevar a cabo las pruebas de Wald correspondientes para rechazar o aceptar la hipótesis nula de no causalidad.

![Figura1](/assets/images/Fig-2016-09-27-table1.png){:class="img-responsive"}

En la Tabla 2 se resumen los resultados del mejor ajuste de regresión (con un trimestre rezagado) de las ecuaciones 1 y 2 en función de las tres posibilidades mencionadas. Éstos se obtuvieron en base al tamaño de la muestra de nuestras variables (Q1 1986 - 2016 2Q) usando el CIS después de probar un máximo de 12 rezagos. En general, se confirma la existencia de causalidad en sentido Granger de doble vía entre ambas variables. Por tanto, parece que no sólo los coeficientes de variación de los precios del petróleo (según la cotización WTI) constituyen una causa en sentido Granger de las tasas de crecimiento del PIB real, sino también a la inversa.

![Figura2](/assets/images/Fig-2016-09-27-table1.png){:class="img-responsive"}

# Relación y limitaciones con la evidencia internacional


Estos resultados marcan una diferencia respecto de aquellos alcanzados con datos anuales en que ahora también se puede percibir  una causalidad reversa (aunque algo más débil), yendo desde US_RGDP_GR a WTI_COV, lo que dirige nuestra atención a los determinantes de la incertidumbre de los precios del petróleo. En un reciente artículo[^3], se han sugerido los siguientes factores que contribuyen a las fluctuaciones del precio del petróleo: 1) las perturbaciones a la producción mundial de petróleo crudo; 2) las perturbaciones a la demanda de crudo asociadas a cambios inesperados en el ciclo económico mundial, y 3) las perturbaciones a la demanda de inventarios de petróleo extraído.

En dos contribuciones anteriores publicadas en 2014 and 2015, he planteado argumentos similares sobre los dos primeros factores. Cabe aclarar, sin embargo, que en el citado artículo se hace hincapié en que "el determinante más importante de la demanda de petróleo han sido los cambios en el flujo de la demanda  (o consumo) de petróleo asociado al ciclo económico global" de donde se puede extrapolar la idea de que a medida que se contrae la economía global, sucede lo mismo con la demanda de materias primas industriales, incluido el crudo, impulsando una presión a la baja del precio del petróleo. Por tanto, se produciría un efecto causal inverso que va desde CR_PIBR_EU a CDV_WTI.

Esto nos lleva al tercer argumento del mencionado estudio correspondiente al rol de los desplazamientos inesperados en la demanda de inventario debido a "cambios no anticipados en la percepción acerca de la futura escasez de petróleo". Siguiendo este análisis, tanto las crisis políticas como las económicas influyen en la evolución de este tipo de percepciones, ya que podrían tender a generar mucha incertidumbre. Es posible que esta falta de conocimiento sobre el futuro se refleje en una especie de demanda preventiva que podría influir en los precios del petróleo y explicar por qué las caídas de precios del petróleo están precedidas por un crecimiento económico inusualmente bajo y viceversa.

Se puede confirmar entonces que la volatilidad de los precios del petróleo sería causa (en el sentido de Granger) de una crisis económica/financiera global.  Se comprobaría también una causalidad reversa que va desde el crecimiento económico real a la incertidumbre del precio del petróleo a través tanto de los choques a la demanda como los cambios inesperados en la demanda de inventario. En este sentido, dependiendo de la extensión y/o magnitud de una crisis, la causalidad inversa podría convertirse en un efecto desencadenante, ya sea para su agravamiento o para su  alivio relativos. Pero, esta conclusión aún debe ser objeto de un escrutinio adicional.

En el cierre, resulta importante anotar que este artículo constituye un ejercicio de equilibrio parcial que podría ser complementado en el marco de un modelo de equilibrio general donde se incorpore a las fluctuaciones del precio del petróleo como un factor fundamental.    

Esta contribución es una nueva versión en español de mi artículo (en inglés) publicado en agosto de este año en Seeking Alpha, bajo el título: “Oil Price Uncertainty Causes a Global Crisis – How About the Other Way Around?”. Agradezco a Luis E. Gonzales C. por sus comentarios y sugerencias en una anterior versión de este documento.
**  Economista.

[^1]: [1]  El coeficiente de variación de los precios WTI del petróleo se mide en términos de la desviación estándar dividida por el promedio, todo esto multiplicado por 100.  Tanto las desviaciones estándar como los promedios para cada trimestre de la muestra de datos fueron calculados a partir de información de precios diarios. Por la construcción de los datos, no fue posible obtener coeficientes de variación deflactados. Sin embargo, al deflactar los precios WTI promedio usando el deflactor trimestral del PIB de Estados Unidos, se encontró que ambas variables siguen un patrón similar, lo que se ratifica por un coeficiente de correlación entre las mismas muy cercano a la unidad (0,99164682).

[^2]: [2] Las dos ecuaciones de causalidad para las variables involucradas en este análisis son:

Donde CR_PIBR_EUt es la tasa de crecimiento del PIB real de Estados Unidos, CDV_WTIt es el Coeficiente de Variación de los precios WTI del petróleo; α, β, γ, δ son los parámetros de los coeficientes; p es la amplitud óptima de rezagos seleccionada con base en el Criterio de Información de Schwarz (CIS); μ t and ω t son los términos de error de ruido blanco.

[^3]: [3]  Véase: Christiane Baumeister y Lutz Kilian, “Forty Years of Oil Price Fluctuations: Why the Price of Oil May Still Surprise Us”, Journal of Economic Perspectives, Vol. 30, No. 1, Winter 2016 (pp.139-60), disponible en línea en este enlace.
