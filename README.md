# Control de Carrito ESP32 + L298N vía Servidor Web (MicroPython)

Este proyecto implementa un sistema de control de un carro robótico usando un **ESP32** programado con **MicroPython** y el controlador de motores **L298N**. El vehículo es controlado mediante una **página web** alojada directamente en el ESP32, sin necesidad de internet.  
El usuario se conecta al punto de acceso WiFi generado por el ESP32 y controla el movimiento del carrito mediante botones y un control deslizante para ajustar la velocidad.

---

## Características principales

- Creación de un **Punto de Acceso (AP)** WiFi:  
  - SSID: `equipo 2`  
  - Contraseña: `123456789`  
  - Acceso desde navegador en: `http://192.168.4.1`

- **Interfaz web interactiva** con:
  - Botón Adelante  
  - Izquierda  
  - Derecha  
  - Atrás  
  - Detener  
  - Control deslizante para ajustar velocidad (0–1023)

- **Control de motores DC** mediante:
  - L298N (IN1, IN2, IN3, IN4)
  - PWM opcional para control de velocidad (ENA, ENB)

- Servidor web simple usando sockets para recibir comandos del navegador.

---

## Hardware utilizado

- ESP32 (MicroPython)
- Módulo L298N
- 2 Motores DC (tracción)
- Fuente de alimentación adecuada
- Cableado Dupont
- Carrito robótico básico

---

## Estructura del proyecto


---

## ¿Cómo usar?

1. Encender el ESP32.
2. Buscar la red WiFi: **equipo 2**
3. Conectarse con la contraseña: **123456789**
4. Abrir el navegador y entrar a:
5. Usar los botones para mover el carrito y el control deslizante para ajustar la velocidad.

---

## Licencia

Proyecto educativo con fines de entrenamiento y práctica con microcontroladores.
