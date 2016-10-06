#Breve descripción del modelo 0 en español

Este modelo trata de entender como aparecen nuevas palabras en un lenguaje. Voy a partir de la idea siguiente:

* Tenemos una red de agentes que van a intercambiar palabras.
* Los agentes a veces pueden actuar como emisor de la palabra y otras veces como receptor.
* Tenemos un lenguaje global que es un conjunto de palabras.
* Tenemos lenguajes locales, que serán el conjunto de palabras que posee cada agente
* Inicialemente todos los lenguajes locales serán iguales al lenguaje global.
* En cada interacción el agente que hace de emisor puede escoger una palabra de su lenguaje e inventarse otra
* En cada interacción el receptor puede aceptar o no la palabra que le da el emisor. Esto dependerá si ya la conoce o no.
* Si la palabra era nueva, es decir que el emisor no la tenía en su lenguaje local y el receptor no la acepta, entonces el emisor no la guarda en su lenguaje local. Si el receptor la acepta entonces la guardan los dos.
* A medida que suceden varias interacciones las nuevas palabras que alcancen a estar en un determinado número de lenguajes locales serán añadidas al lenguaje global.
* Estudiaremos cada cuantas interacciones aparece una nueva palabra en lenguaje global para diferentes estructuras de la red.
* Para eso desarrollaremos, en python, clases para los agentes, el lenguaje, la red y las que necesitemos.
* En resultados generaremos imágenes con gráficas y tablas csv.
