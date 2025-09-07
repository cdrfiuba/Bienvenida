# Bienvenida

Hola! Si estas leyendo estas palabras es muy probable que seas un nuevo miembro del club de robotica de FIUBA. La idea de este repositorio es dar un pantallazo general de los distintos proyectos que tenemos para hacer, sugerencias de material recomendado y demas.

## Sobre el club

El Club de Robótica es un espacio propuesto por Ingenieros y estudiantes para la investigacion y el desarrollo de prototipos y actividades en robotica. La filosofía del Club consiste en emplear los conocimientos adquiridos a lo largo de la carrera y combinarlos con la motivación y la participación activa de cada uno de sus integrantes. De ese modo se busca conjugar creatividad, dinamismo y acción que brindan como resultado proyectos reales.

## Informacion general

La mayoria de los proyectos son una combinacion de piezas mecanicas, hardware y software. No es necesario ser un experto en las tres, pero si esta bueno tener una idea basica como para evitar atascarse. A continuacion algunas sugerencias respecto de cada una.

### Piezas mecanicas

Todo proyecto del club vive tiene una parte fisica, tangible, que puede o no moverse, y que se encuentra en mundo de los mortales. Estoy incluye carcasas, ruedas, brazos, pistones, motores, tornillos, tuercas, armaduras, botones, pistolita de silicona (te estoy mirando a vos gusty), etc. 

Una buena forma de articular todo esto es mediante la impresion 3D, que permite diseñar y producir una pieza que se adecua perfectamente a nuestras necesidades. Hay multiples softwares gratuitos que son simples como para disenar una pieza en unos pocos minutos ([onshape, programa online, gratis con cuenta fiuba](https://www.onshape.com/en/), [freecad](https://www.freecad.org/index.php?lang=es_ES), [Fusion360, es mas avanzado, tiene version demo gratuita](https://www.autodesk.com/latam/products/fusion-360/overview)).

En el LABI tenemos acceso a todo tipo de herramientas, por lo que tomar materiales mas tradicionales (como ser chapa o madera) para despues modificarlos es algo que esta dentro de las posibilidades del club.

Otra alternativa es reciclar, que si bien probablemente no se encaje perfectamente a aquello que nos imaginamos en nuestras cabezas, si nos va a permitir con poco esfuerzo tener un prototipo en funcionamiento. 

### Hardware

- <ins>Sobre microcontroladores y placas programables:</ins>
En la inmensa mayoria de los casos un proyecto va a necesitar un cerebro, que en el mundo de la electronica se suele llamar [microcontrolador](https://es.wikipedia.org/wiki/Microcontrolador). 

  - Hoy en dia el boom de la comunidad Arduino ha hecho que su uso sea extremadamente simple (no hay que perder horas y horas leyendo hojas de datos) por lo que las placas de desarrollo de la familia Arduino (Uno, Mega, Nano, Due, Leonardo) son un mas que aceptable punto de arranque para hacer cualquier cosa. 

  - Tambien hay otras opciones mas potentes como los microcontroladores de 32 bits de las lineas ESP32 y Raspberry PI Pico, que pueden incluir opciones de conectividad wifi o bluetooth, ademas de mas memoria y mas perifericos.

  - Por ultimo, hacer una mencion a las microcomputadoras como las raspberry PI o las beaglebone que directamente pueden correr un sistema operativo. Tambien existen las FPGA que son bastante mas complejas pero tienen aplicaciones muy interesantes

- <ins>Sobre electronica general:</ins> Ademas de necesitar un cerebro, nosotros pretendemos que nuestro proyecto haga cosas. Para esto vamos a necesitar sensores, actuadores y una forma de que todo esto se comunique con nuestro microcontrolador. Es decir, vamos a necesitar un circuito electronico. En el vamos a poner nuestras resistencias, capacitores, transistores y demas que nos van a permitir lograr cosas. Para diseñar un circuito electronico y su posterior PCB (placa donde van a estar nuestros componentes) recomiendo la herramienta [Kicad](https://www.kicad.org/). Aca hay dos opciones, diseñar el PCB y fabricarlo (o mandarlo a fabricar) o bien armarlo en una placa experimental. 

### Software

Ademas de lo fisico, nuestro proyecto va a necesitar una logica de funcionamiento, es decir, un programa. Este va a contener las instrucciones que van a ser ejecutadas por nuestro "cerebro". Para diseñar este programa vamos a necesitar un entorno de desarrollo mas comunmente conocido como IDE. Si se trabaja con una placa de desarrollo Arduino, lo mas comun es usar el [IDE de arduino](https://www.arduino.cc/en/software/) usando su lenguaje que es C++ con una serie de agregados para hacerlo mas noob-friendly. Mas o menos cada fabricante de microcontroladores ofrece su propio IDE (por ejemplo ST ofrece el [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)), aunque muchos son compatibles con el de Arduino (ESP32, RPI pico, STM32, etc). Por otro lado, en microcontroladores mas potentes esta la posibilidad de usar micropython o circuitpython con el IDE [Thonny](https://thonny.org/).

## Proyectos iniciados

Aca va un listado de proyectos que se empezaron y les vendria bien una mano. 

- [Picasso](https://github.com/cdrfiuba/picasso) **(Dificultad avanzada)**: La idea es que funcione como un pen plotter, con una logica similar a la impresion 3D pero que en lugar de tener un tercer eje tiene un mecanismo que contrae o extiende un fibron. Actualmente la parte mecanica esta mas o menos funcional, se necesita hacer la parte electronica y de software.

- [Seguidor de linea](https://github.com/cdrfiuba/seguidor_de_linea) **(Dificultad intermedia)**: Cintia y Alan estan trabajando en un seguidor de linea para competencias de la [LNR](https://lnr-argentina.com.ar/).

- Girasol electronico **(Dificultad basica)**: Se quiere hacer un panel solar capaz de seguir el sol. Hay algunas piezas hechas en 3D que quizas haya que reimprimir, se tiene que tomar la decision de mantener los servos o cambiar por motores pap. [Inspiracion](https://www.youtube.com/watch?v=zXX4d5eyvb8)

## Proyectos Jubilados

- [Arion](https://github.com/cdrfiuba/arion)

- [Skil](https://github.com/cdrfiuba/skil)

## Tutoriales utiles

- [Tutoriales de arduino](https://www.arduino.cc/en/Tutorial/HomePage/)
- [Tutorial de soldadura](https://www.youtube.com/watch?v=6rmErwU5E-k&t=256s)
- [Trucos con circuitpython](https://github.com/todbot/circuitpython-tricks)

## Bibliografia interesante

- [The Art of electronics](https://share.google/h4LVe0Fi5mbx0gtgC) basicamente la biblia de la electronica, cubre de todo.

