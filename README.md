# Proyecto de Control de Motor y Sensor con C++

Este proyecto está diseñado para controlar un motor y obtener lecturas de un sensor utilizando un microcontrolador como Arduino, Bluepill o STM32. El sistema utiliza la siguiente electrónica:

- **Motor Pololu 3000 rpm**: Motor de corriente continua con una velocidad de hasta 3000 revoluciones por minuto.
- **SparkFun Motor Driver - Dual TB6612FNG**: Controlador de motor para controlar la dirección y velocidad del motor DC.
- **Sensor QTR 8RC**: Sensor de reflexión para detectar objetos o superficies, útil para aplicaciones como seguimiento de línea o detección de obstáculos.
- **Microcontrolador**: Puede utilizarse un Arduino, Bluepill, o STM32 para controlar el motor y el sensor.

## Descripción del Proyecto

Este proyecto tiene como objetivo implementar un sistema de seguimiento de línea utilizando los componentes mencionados. El motor Pololu se controla mediante el SparkFun Motor Driver, que permite ajustar su velocidad y dirección. El sensor QTR 8RC se utilizará para detectar el contraste de la línea y proporcionar la retroalimentación necesaria para mantener el motor en movimiento a lo largo de la ruta.

## Componentes

1. **SparkFun Motor Driver - Dual TB6612FNG**
   - Controla dos motores de corriente continua.
   - Proporciona control de dirección y velocidad.
   
2. **Motor Pololu 3000 rpm**
   - Motor de alto rendimiento para aplicaciones de robótica.

3. **Sensor QTR 8RC**
   - Sensor de reflexión infrarroja con 8 canales, ideal para detección de líneas y seguimiento de rutas.

4. **Microcontrolador**
   - Arduino, STM32 o Bluepill para la implementación del código y control de los componentes.

## Requisitos

- Un entorno de desarrollo C++.
- Librerías de control para el motor y el sensor.
- Conexiones adecuadas entre el microcontrolador y los componentes.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/proyecto.git
