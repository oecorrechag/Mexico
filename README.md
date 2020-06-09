# Proyecto Mexico

# <center> Clasificación de Lengua de señas
Actividad Final Clase Vision  Reconocimiento de patrones
  
**Universidad Nacional de Colombia**

El 26 de septiembre es el día internacional del déficit auditivo a nivel mundial. La lengua de señas o lengua de signos es una lengua natural de expresión y configuración gesto-espacial y percepción visual (o incluso táctil por ciertas personas con sordoceguera), gracias a la cual, los sordos pueden establecer un canal de comunicación con su entorno social, sea este conformado por otros sordos o por cualquier persona que conozca la lengua de señas empleada. Mientras que la lengua oral se basa en la comunicación a través de un canal vocal-auditivo, la lengua de señas lo hace por un canal gesto-viso-espacial. 

Los amerindios de la región de las Grandes Llanuras de América del Norte usaban una lengua de señas para hacerse entender entre etnias que hablaban lenguas muy diferentes con fonologías extremadamente diversas.5​ El sistema estuvo en uso hasta mucho después de la conquista europea.

Mas del 5% de la población mundial padece perdida de audición.

# Diseño de experimento

Se cuenta con 87000 imágenes en total, 29 clases de las cuales 27 son letras y dos adicionales, en promedio 3000 imágenes por clase. Las imágenes son tomadas con diferentes intensidades de luz, con la misma cámara.

El experimento es no balanceado.

El experimento estandarizado

Dimensiones: 200 x 200 pixeles <br>
Peso: 12kb <br>
Formato: jpeg

# Problema

Las personas sordas tienen problemas comunicativos que generan aislamiento, problemas de conducta, exclusión y falta de oportunidades, esto es evidenciado en la universidad, por lo que la universidad ha realizado charlas y cursos de lenguaje de señas para tratar de reducir este problema.

# Objetivo

* Desarrollar un prototipo capaz de identificar las señas para ser clasificadas al alfabeto americano. 
* Contribuir al mejoramiento de las condiciones de vida de las personas con discapacidad auditiva.

# Motivación

* Brindar una herramienta que facilite la comunicación entre personas con discapacidad auditiva y personas sin discapacidad.
* Aportar al proceso de inclusión social de las personas con discapacidad auditiva.

# Metodologia 

* Se analizaron las imágenes y se decidió usar una red neuronal convolucional CNN dada su complejidad y las múltiples clases.
* La evaluación del modelo matriz de confusión.

# Resultados y conclusiones

Figura 1: Modelo.

![alt text](https://github.com/oecorrechag/Proyecto-Sao-Paulo-Cafe/blob/master/modelo.png)

* Se desarrollo un software capaz de detectar señales de manos y clasificarlas según el alfabeto americano, presentando buenas predicciones y cumpliendo con el objetivo deseado.

Figura 2: Evaluacion del modelo con fotos propias.

![alt text](https://github.com/oecorrechag/Proyecto-Sao-Paulo-Cafe/blob/master/manos.png)

* Se valido el modelo con imágenes de nuestras propias manos, si bien el modelo clasifica correctamente, puede generar algunos errores dada la orientación de la mano, fondo de la foto y la iluminación.  

Como proyecto futuro se podria utilizar video y utilizar la funcion VideoCapture de CV2 para capturar en tiempo real y clasificar inmediatamente. 

Figura 3: Matriz de Confusión.

![alt text](https://github.com/oecorrechag/Proyecto-Sao-Paulo-Cafe/blob/master/matriz.png)

### Bibliografia

Akash.(2020). Image data set for alphabets in the American Sign Language. Recuperado de: https://www.kaggle.com/grassknoted/asl-alphabet

Insor.(2020). Diccionario/Repositorio LSC-Español. Recuperado de: http://educativo.insor.gov.co/diccionario/
