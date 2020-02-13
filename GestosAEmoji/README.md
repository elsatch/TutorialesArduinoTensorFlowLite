# Aprendizaje Máquina en Arduino
## Tutorial sobre cómo entrenar distintos gestos utilizando TensorFlow Lite

En este tutorial vamos a enseñar a una placa a reconocer gestos. Capturaremos datos de movimiento utilizando los sensores integrados en la placa [Arduino Nano 33 BLE Sense](https://store.arduino.cc/arduino-nano-33-ble-sense), importaremos estos datos en Tensorflow para enternar un modelos y desplegaremos el clasificador de gestos directamente en la placa utilizando [TensorFlow Lite for microcontrollers](https://www.tensorflow.org/lite/microcontrollers/overview). 

### Nota del traductor
El tutorial trata sobre el aprendizaje máquina de gestos utilizando la placa Arduino Nano BLE 33. Aunque esta placa dispone de un detector de gestos, este no se utiliza para nada en este ejemplo. Los gestos se van a detectar a partir de los movimientos de la placa, empleando el acelerómetro y girósocopo que vienen incluidos en la propia placa.

### Creditos

Este tutorial es una adaptación del [taller](https://github.com/sandeepmistry/aimldevfest-workshop-2019) que realizaron Sandeep Mistry de Arduino y Don Coleman de Chariot Solutions, durante AI/ML Devfest en Septiembre de 2019. 

La tradución y adaptación de los gestos ha sido realizada por César García, de [La Hora Maker](http://www.lahoramaker.com) para facilitar que más gente pueda inventar nuevas cosas utilizando Machine Learning en Arduino.


## Ejercicios

* [Ejercicio 1: Entorno de desarrollo](exercises/exercise1.md)
* [Ejercicio 2: Conectando con la placa](exercises/exercise2.md)
* [Ejercicio 3: Visualizando los datos de la IMU](exercises/exercise3.md)
* [Ejercicio 4: Recopilando los datos para el entrenamiento](exercises/exercise4.md)
* [Ejercicio 5: Aprendizaje máquina](exercises/exercise5.md)
* [Ejercicio 6: Clasificando los datos de la IMU](exercises/exercise6.md)
* [Ejercicio 7: Teclado de emojis controlado por USB](exercises/exercise7.md)
* [Ejercicio 8: Próximos pasos](exercises/exercise8.md)
