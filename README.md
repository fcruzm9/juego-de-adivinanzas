# Adivina el Número

Práctica del módulo Programación Python:  Universidad Complutense de Madrid  
Autor: Felipe Cruz

## Descripción

Juego de adivinanza en Python. El jugador tiene que adivinar un número entre 1 y 1000 con diferentes cantidades de intentos.
Al terminar cada partida se guarda el resultado en un fichero Excel y se pueden ver las estadísticas desde el menú principal.

## Modos de juego

**Modo solitario:** el computador elige el número aleatoriamente y el mismo jugador intenta adivinarlo.

**Modo 2 jugadores:** el Jugador 1 escribe el número y el Jugador 2 intenta adivinarlo.

En ambos modos se puede elegir la dificultad:
- Fácil: 20 intentos
- Medio: 12 intentos
- Difícil: 5 intentos

## Requisitos

Antes de ejecutar el programa hay que instalar estos paquetes:

pip install openpyxl matplotlib

Los paquetes `random` y `os` ya vienen incluidos en Python.


## Ejecución

python adivina_el_numero.py

## Fichero de estadísticas

El programa guarda los resultados automáticamente en:
- Windows: `C:\EjerciciosPython\Estadisticas.xlsx`
- Mac/Linux: `~/EjerciciosPython/Estadisticas.xlsx`