# Workshop6
sixth workshop of automation and control of process class

## Sensor

Sensor digital de presión atmosferica, humedad y temperatura BME280. Este sensor provee interfaces de conexión SPI y I2C, cada una con un maximo de frecuencia de 3.4 MHz y 10 MHz respectivamente. Este sensor tiene un rango de operación para las tres funcionalidades:

- Temperatura: -40 - +85°C.
- Humedad relativa: 0 - 100%.
- Presión atmosferica: 300 - 1100 hPa.

Tiene unos parametros para el sensor de humedad:

- Tiempo de respuesta: 1s.
- Tolerancia de exactitud: ±3% humedad relativa.

También para el sensor de temperatura:

- Exactitud de temperatura absoluta (0-65°C): ±1°C

Para el sensor de presión:

- Exactitud absoluta (0-65°C): ±1.0hPa.
- Exactitud relativa: ±0.12hPa.

En este caso se utiliza la interfaz I2C por medio de los pines GPIO2 y GPIO3 de la placa Raspberry. 

Referencia: [BME280 Datasheet](https://itbrainpower.net/downloadables/BST-BME280-DS002-1509607.pdf) 

## Sistema Embebido

Se utiliza la Raspberry Pi 3 Modelo B, está placa contiene las siguientes espcificaciones:

### Hardware

- CPU de 4 nucleos Broadcom BCM2837 de 64bit con una velocidad de 1.2GHz.
- RAM de 1GB.
- Chip BCM43438 de Bluetooth y LAN inalambrica.
- 100 Base Ethernet.
- GPIO extendido de 40 pines.
- 4 puertos USB 2.
- Salida estéreo de 4 polos y puerto de vídeo compuesto.
- HDMI de tamaño completo.
- Puerto de cámara CSI para conectar una cámara Raspberry Pi.
- Puerto de pantalla DSI para conectar una pantalla táctil Raspberry Pi.
- Puerto Micro SD para cargar su sistema operativo y almacenar datos.
- Fuente de alimentación Micro USB conmutada mejorada de hasta 2,5A.

Referencia: [Raspberry Pi 3 Model B](https://www.raspberrypi.com/products/raspberry-pi-3-model-b/)

### Software

- Sistema operativo Raspberry Pi OS.
- Entorno de ejecución Node.js.
- Aplicación cliente en JavaScript.
- Libreria cliente de protocolo de comunicación MQTT.
- Libreria cliente de dispositivo IoT Azure.
- Libreria sensor BME280.
- Libreria de uso de pines de Raspberry Pi.

Referencia: [Raspberry Pi Web Simulator](https://azure-samples.github.io/raspberry-pi-web-simulator/)

## Conectividad

### Conectividad física

### Protocolo de comunicación

### Protocolo de aplicación

## Analitica de datos
