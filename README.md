# Robótica en el CEIP Sierra Nevada


Estas son las piezas del robot que vamos a montar

![3](./imagenes/IMG_20160506_171835_.jpg)

Tendrá dos ruedas, cada una con su motor, lo que permitirá que haga giros complejos.

Le añadiremos sensores de obstáculos y lo programaremos para que los evite y ¡para que no se caiga de la mesa!

## Día 6-5-2016

Hoy, para empezar haremos montajes y programas sencillos.

### Componentes de un robot

Hemos empezado la clase hablando de los componentes que tiene un robot y los que tendrá el que montaremos. Hemos identificado estas piezas con las que hay en la caja:

![1](./imagenes/IMG_20160506_171738_.jpg)

### Haciendo parpadear un led

A continuación preparamos el primer montaje dónde ya identificamos algunos de los componentes que vamos a usar como el microprocesador (Arduino)

Primero diseñándolo en el ordenador


Para luego montarlo con los componentes

![4](./imagenes/IMG_20160506_163047_.jpg)

Pasamos ahora a la programación. Para ellos usamos un software gratuito que se llama [bitBloq](http://bitbloq.bq.com)

Empezamos haciendo un programa simple en el que hacemos que un led parpadee.

![ProgramaParpadeo](./imagenes/ProgramaParpadeo.png)

Aunque el programa es sencillo ya se han utilizado los conceptos de secuencia, espera, y han entendido velocidad a la que funciona el procesador.

Se han hecho con el interface del programa y han convertido valores entre unidades de tiempo.

Una vez terminado el programa lo han pasado  a la placa Arduino donde se ha ejecutado.

### Utilizando sensores

Luego hemos  utilizado un sensor de luz infrarroja, capaz de detectar obstáculos.

El montaje es sencillo, pero ya añade más componentes.

![MontajeSensor](./imagenes/MontajeSensor.png)

Hemos hecho un programa sencillo que nos avisa cuando detecta un obstáculo encendiendo un led

![ProgramaSensor](./imagenes/ProgramaSensor.png)

Para ello leemos el valor del sensor y hacemos una  comparación entre este valor y el esperado

![2](./imagenes/IMG_20160506_171822_.jpg)
