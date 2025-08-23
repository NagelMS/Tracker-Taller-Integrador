# Tracker-Taller-Integrador
En este repositorio se realiza el desarrollo de *firmware* para un módulo *tracker* con la placa de desarrollo *LilyGo's T-Beam ESP32 LoRa 433MHz SX1276* por los estudiantes Nagel Mejía Segura, Óscar González Cambronero y Wilberth Gutiérrez Montero.

## Fuente de Información
Librerías propias, el archivo `plaformio.ini` y varios fueron obtenidos de:

[Repositorio de LilyGo-LoRa-Series](https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series/tree/master)

## Estructura de Directorios

- `lib`: Contiene librerías propias de LilyGo, obtenido externamente.
- `ejemplos_lilygo`: Contiene código fuente de ejemplos propios de LilyGo, obtenido externamente.

## Construcción

### Ejemplos LilyGo

Se requiere únicamente descomentar el ejemplo correspondiente en `platformio.ini`, construir y programar con las herramientas de *Platformio*.