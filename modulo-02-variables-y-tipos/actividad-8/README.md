# Actividad 8 — Depura tu propio código

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 3*: f) Se han probado y depurado los programas. g) Se ha comentado y documentado el código.

## Contexto

Nadie escribe código bien a la primera. La diferencia entre un programador y el resto es que sabe encontrar por qué algo no hace lo que quiere.

## Objetivo

Romper un programa a propósito, encontrar el fallo con herramientas y documentar el proceso.

## Lo que debes hacer

1. Crea `solucion/depuracion.py` con un programa que **no funcione**: invéntate tres errores (por ejemplo, usar una variable antes de crearla, sumar texto con número, y equivocarte al escribir el nombre de una variable).
2. Ejecuta el programa y **copia los tres errores** que aparecen en un fichero `errores.txt` dentro de `solucion/`.
3. Arregla el programa usando el depurador de tu editor (puntos de interrupción y inspección de variables) o `print()` de control.
4. Documenta cada fallo en un `README.md` dentro de `solucion/` con tres líneas: **qué esperaba**, **qué pasó** y **por qué**.
5. El programa final tiene que hacer lo que se suponía al principio y tener al menos tres comentarios explicando las decisiones.

## Entregable

- `solucion/depuracion.py` (funcionando).
- `solucion/errores.txt` con los errores originales.
- `solucion/README.md` con la documentación de los tres fallos.
- Al menos tres commits: uno por cada error corregido.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Los tres fallos están documentados con el mensaje real del error | 30 % |
| El programa final funciona | 30 % |
| El proceso se ve en el historial de commits | 20 % |
| Comentarios y documentación | 20 % |

## Pista de cara al futuro
Cuando programéis el robot, los sensores fallarán, los cables se soltarán y el códigoFormatted tendrá que robusterse. Depurar bien es una habilidad de primer orden, no un extra.
