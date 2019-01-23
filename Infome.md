---
bibliography: ['bibtex.bib']
---

# Introducción

El Humor es un campo multi-disciplinario de estudio, en el que se ha trabajado
desde muchos campos como: psicología, filosofía, lingüística, sociología
y literatura. Para las Ciencias de la Computación 
(especialmente para la Inteligencia Artificial) el estudio del humor está encaminado a
modelar el humor de una manera computacionalmente representable.

Tener un modelo computacional de humor permitiría a los diseñadores de interfaces
poder hacer que la computadora genere e interprete humor(chistes) cuando interactúa
con un usuario. Hay muchas situaciones en las interacciones humano-humano donde el humor
juega un rol importante en mantener la conversación. Haciendo uso del paradigma **CASA**
(Computers Are Social Actors) se espera que un rol similar pueda ocupar en la interacción
humano-computadora.

En este trabajo nos referiremos a las diferentes teorías sobre el humor, sus aspectos
computacionales y algunas aplicaciones.

# Teorías Convencionales del Humor

En la literatura sobre teoría del humor existe una división en 3 teorías básicas:
* Teoría de la Superioridad
* Teoría de la Relevancia
* Teoría de la Incongruencia

En este tema discutiremos brevemente estas tres teorías.

## Teoría de la Superioridad

La teoría de la Superioridad asume que nos reímos de la desgracia de otros; esto refleja
nuestra superioridad. Esta teoría puede encontrarse en la obra de Platón, Arístoteles y
Hobbes [@sorell1951dance]. A pesar de que esta teoría pueda parecer fuera de moda en el siglo
XXI Charles Gruner reformuló esta *Teoría de la Superioridad del Humor* [@gruner2017game].
Su teoría consta de una tesis de 3 partes:
* Todas las situaciones humorísticas contienen a un ganador y un perdedor
* La incongruencia siempre está presente en las situaciones humorísticas
* El Humor requiere del elemento sorpresa

## Teoría del Alivio

La Teoría del Alivio tiene su origen en la psicología [@rutter1997stand]. Esta teoría tiene su origen
cuando Freud propuso su teoría de que la risa podía liberar la tensión y "la energía psicológica".
Esta energía se construye continuamente dentro del ser humano, y no tiene otra función que
expresarse utilizando la risa. Esta teoría realmente no da una explicación de donde encontrar el
humor, puede ser visto como una teoría de la risa.

## Teoría de la Incongruencia

Esta es la teoría más influyente en el estudio del humor y la risa.
Kant, en el siglo 18 fue el primero en dar un concepto de la incongruencia.
Una buena descripción de la teoría de la incongruencia pueden ser encontradas
en estas palabras de Schopenhauer [@schopenhauer2016arthur]:
"La causa de la risa en todos los casos es simplemente la repentina percepción de la
incongruencia entre un concepto y los objetos reales que han sido enseñados en
algún tipo de relación y la risa en si es solo una expresión de su incongruencia."

Cuando los chistes son examinados utilizando la teoría de la incongruencia, 2 objetos
en la broma son presentados dentro de un solo concepto (marco). Este concepto se aplica
a ambos objetos y estos objetos se vuelven similares. Mientras la broma progresa, se convierte
aparentemente ese concepto solo se aplica a uno de los 2 objetos y la diferencia entre
los objetos o sus conceptos se vuelve aparente. Esto es llamado incongruencia [@rutter1997stand].
La teoría de la resolución-incongruencia es más o menos una teoría lingüística, porque esta
explica como las bromas son construidas y no presta atención a los factores. Pero no puede explicar
porque cuando oímos una broma más de una vez sigue siendo graciosa y porque todas las
incongruencias no son graciosas.

# Modelación Computacional del Humor

Uno de los esquemas propuestos, el humor es interpretado como un mal funcionamiento durante
el procesamiento de información procesada condicionalmente por la necesidad de borrar 
información trasmitida a la conciencia. La función biológica del sentido del humor consiste
en acelerar la trasmisión de información procesada al consciente y el uso más efectivo de los recursos
del cerebro. En el modelo propuesto por algunos autores toma en cuenta la susceptibilidad
de las personas al humor, el rol del tiempo, y las emociones. En el trabajo se formula
un algoritmo genera para el sentido del humor de las computadoras y su implementación en redes
neuronales [@mulder2002humour].

El trabajo anteriormente descrito llega a la conclusión de que el sentido del humor está
condicionado a una necesidad biológica de acelerar información al consciente de una
manera más eficiente de usar los recursos del cerebro. Entonces, el placer obtenido de
la riza no es un factor esencial; de formar similar a estornudar y tocer existen
separado del alivio del primero y la molestia del segundo, están definidos por la necesidad
biológica de limpiar el sistema respiratorio. 

La autores refieren que es posible crear un programa que "ría" en las mismas situaciones que un
humano si se simplifican el tipo de bromas de tal forma de que fueran más sencillo
de tal forma que sea fácil traducirlo. Para hacer que comprendan bromas más complejas
es necesario computadoras más complejas y más estudio por parte de los psicólogos.

# Generación de Chistes

Hasta esta fecha, ha habido un número limitado de contribuciones hacia la contracción de sistemas computacionales generadoras de humor.
Uno de los primeros intentos fue JAPE [@ritchie2003jape].
JAPE usó un algoritmo para generar acertijos divertidos o, más específicamente, fonogramas fonológicamente ambiguos.
HAHAcronym generator [@stock2006laughing] fue otro intento de generación de humor computacional, cuyo objetivo era generar automáticamente nuevas versiones de acrónimos existentes, que se aseguraron de ser humorísticas utilizando la teoría de la incongruencia. Además, Taylor y Mazlack [@yang2015humor] trabajaron en la comprensión del humor en una Dominio restringido de las bromas "knock-knock". Si bien el enfoque heurístico fue capaz de identificar eficazmente las instancias de juegos de palabras, pero tuvo dificultad para identificar la bromas de "knock-knock".
Recientemente, [@valitutti2016computational], intenta generar textos cómicos mediante la sustitución de una sola palabra en un texto breve, dentro de algunas restricciones. Los resultados mostraron que las palabras tabú hicieron reconocible el texto como humorístico.
Petrovi'c and Matthews [@petrovic2013unsupervised] intentaron construir un sistema de generación de humor sin supervisión que genera una forma específica de chistes utilizando big data.
Este es un primer intento de generación de bromas sin supervisión que dio resultados prometedores.
La lingüística computacional se explora ampliamente en estos días, y la traducción, el resumen y la comprensión son algunas de las muchas áreas de interés.
Debido a su complejidad y una gran cantidad de variaciones, el humor verbal se ha explorado ligeramente en el procesamiento computacional del lenguaje.

# Detección de Humor

La mayoría de los estudios existentes sobre el reconocimiento del humor se formulan como un problema de clasificación binaria y tratan de reconocer bromas a través de un conjunto de características lingüísticas [@purandare2006humor, @kiddon2011s]. 
Por ejemplo, Mihalcea y Strapparava [@mihalcea2005computational] definieron tres tipos de características estilísticas específicas del humor: Aliteración, Antónimos y Jerga de adultos, y entrenaron un clasificador basado en estas representaciones de características.
De manera similar, Zhang y Liu [@zhang2014recognizing] diseñaron varias categorías de características relacionadas con el humor, derivadas de teorías influyentes del humor, normas lingüísticas y dimensiones afectivas, e incorporaron aproximadamente cincuenta características en el modelo de un Gradient Boosting Regression Tree para el reconocimiento del humor.
Taylor y Mazlack [@taylor2004computationally] reconocieron chistes de juegos de palabras basados ​​en técnicas de reconocimiento estadístico del lenguaje, en donde aprendieron patrones estadísticos de texto en N-gramas y brindaron un enfoque heurístico para una ubicación donde el juego de palabras puede o no ocurrir.
También se puede encontrar un trabajo similar [@taylor2009computational], que describió el proceso de detección del humor a través de la semántica ontológica al transponer automáticamente el texto a la Representación formateada de texto-significado para detectar humor.
Además de las características del lenguaje, algunos otros estudios también utilizan señales habladas o multimodales.
Por ejemplo, Purandare y Litman [@purandare2006humor] analizaron características lingüísticas y acústicas-prosódicas para reconocer automáticamente el humor durante las conversaciones habladas.
Sin embargo, las características relacionadas con el humor en la mayoría de esas obras no se derivan o explican sistemáticamente.
Un componente esencial en el reconocimiento del humor es la construcción de instancias de datos negativos.
Los clasificadores basados ​​en muestras negativas que se encuentran en un dominio diferente al humor, las instancias positivas tendrán un alto rendimiento de clasificación, pero no son necesariamente buenos clasificadores.
Existen pocos conjuntos de datos de referencia para el reconocimiento del humor y la mayoría de los estudios seleccionan instancias negativas específicamente. 
Por ejemplo, Mihalcea y Strapparava [@mihalcea2005computational] construyeron el conjunto de ejemplos negativos utilizando títulos de noticias de Reuters news, proverbs y British National Corpus. 
Zhang [@zhang2014recognizing] probó aleatoriamente 1500 tweets y luego pidió a los anotadores que filtraran los tweets humorísticos.
En comparación con el reconocimiento de humor, la generación de humor ha recibido mucha atención en las últimas décadas [@binsted2006computational, @ritchie2005frame].
La mayoría del trabajo de generación se basa en teorías del humor para explicar los factores del humor, como la Teoría del humor semántica basada en scripts [@raskin2012semantic, @labutov2013re]  y emplea plantillas para generar chistes.
Por ejemplo, Ozbal y Strapparava (2012) crearon un neologismo humorístico utilizando WordNet y ConceptNet.
En detalle, su sistema combinó varios recursos lingüísticos para generar nombres creativos, más específicamente neologismos basados ​​en juegos de palabras y metáforas homófonas.
En contraste con la investigación sobre el reconocimiento del humor y la generación, hay pocos estudios que identifican las anclas del humor que desencadenan efectos humorísticos en oraciones generales.
Un cierto tipo de chistes puede tener estructuras o características específicas que proporcionan indicadores para anclar el humor.
Por ejemplo, en el problema de "That’s What She Said: Double Entendre Identification" [@kiddon2011s], las características que involucran el uso de sustantivos que son eufemismos para sustantivos sexualmente explícitos o estructuras comunes en el dominio erótico probablemente brinden pistas sobre posibles anclas de humor. 
De manera similar, en los chistes de "Knock-Knock" [@taylor2004computationally], el juego de palabras es lo que lleva al humor. Sin embargo, el juego de palabras por sí solo no es suficiente para desencadenar el efecto cómico, por lo que no es equivalente a los anclajes del humor para una broma.
