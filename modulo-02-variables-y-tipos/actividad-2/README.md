# Actividad 2 — La ficha del robot

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: d) Se han identificado los distintos tipos de variables y la utilidad específica de cada uno. e) Se ha modificado el código de un programa para crear y utilizar variables.

## Contexto

Todo lo que un robot sabe de sí mismo (su nombre, cuántas ruedas tiene, cuánto pesa la batería, si está encendido) acaba guardado en variables. Antes de poder tomar decisiones necesita poder nombrar esas cosas.

## Objetivo

Crear las variables que describen un robot e imprimirlas con su tipo.

## Lo que debes hacer

1. Crea `solucion/ficha.py` con las siguientes variables:
   - `nombre` (texto): el nombre de tu robot.
   - `ruedas` (entero): cuántas ruedas tiene.
   - `diametro_rueda` (decimal): el diámetro en centímetros.
   - `bateria` (entero): los minutos de autonomía que le quedan.
   - `encendido` (booleano): si está encendido o no.
2. Muestra el valor de cada variable **en su propia línea**.
3. Muestra también el **tipo** de cada variable (`type`) en la misma línea, del estilo `nombre: robot = Titán (str)`.
4. Ejecuta el programa y comprueba que los 5 tipos son los que esperabas.

## Entregable

- `solucion/ficha.py`.
- La salida de la consola.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Las 5 variables existen con el tipo correcto | 40 % |
| Se muestra valor y tipo de cada una | 30 % |
| Nombres de variables claros y sin acentos ni espacios | 20 % |
| Comentario explicando qué es la ficha del robot | 10 % |

## Pista de cara al futuro

Estas variables las usarán todas: cuando el robot tenga que decidir si avanza, comparará la batería. Fíjate en cuáles son números y cuáles son texto.
