# Prácticos de Ecología de Paisaje (CBIT241)

## Nociones básicas de geoestadística y dependencia espacial
Esta sección revisa principios básicos del proceso espacial. Se revisan los procesos de primer y segundo orden

### Procesos de primer orden

Aqúí la pregunta que se busca resolver es de qué manera están distribuidos los eventos en el espacio. ¿Cuál es su nivel de asociación espacial? Responder esta pregunta sólo requiere, en estricto rigor, la ubicación del proceso: sus coordenadas espaciales (*x,y*).

El estadígrafo usado es el *K*-Ripley que permite identificar si los elementos están:
1. Distribuidos de forma grupada, por algún efecto de contagio
2. Desagrupados, o en repulsión, y
3. Distrtibuidos de forma azarosa. Los procesos son indiferentes a la ubicación de los "vecinos"


### Procesos de segundo orden

en estos casos, lo que interesa es el valor que adquiere el proceso en la locación (*x,y*). Ya no solo interesan procesos de contagio o repulsión, sino que interesa saber si una cantidad *z* se expresa en el locación (*x,y*) como será la cantidad (*z'*) a distancia *h*. Esto es, en la vecindad (*x+h,y+h*).

En este caso usamos 2 métodos para comprender la dependencia espacial de la variable *z*.

**Autocorrelación**


**Semivarianza**
