# Actividad 5 — Convertir: el error de las comillas

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: h) Se ha comprobado el funcionamiento de las conversiones de tipo explícitas e implícitas.

## Contexto

`"3"` y `3` no son lo mismo: el primero es texto, el segundo es un número. Sumarlos peta. Ese error es el más habitual del curso y también el más fácil de arreglar.

## Objetivo

Reproducir un error de tipos, entenderlo y arreglarlo con conversiones.

## Lo que debes hacer

1. Crea `solucion/conversiones.py`.
2. Escribe estas cuatro líneas **tal cual** y ejecuta el programa:
   ```python
   print("Resultado:", "3" + 3)
   ```
   Guarda una captura o copia el error que aparece.
3. Arregla el programa con conversiones **explícitas** (`int()`, `float()`, `str()`) para que imprita `Resultado: 6`.
4. Haz lo mismo con la división: `"10" / 2` primero falla, después funciona con el tipo correcto.
5. Demuestra también una conversión **implícita**: explica con un comentario por qué `1 + 2.0` funciona sin escribir ningún `float()`.

## Entregable

- `solucion/conversiones.py` con las cuatro versiones (la que falla, la que funciona y las dos conversiones explícitas).
- En el mensaje del commit, pega el error original y explica en dos líneas qué lo causaba.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Se reproduce el error y se documenta | 20 % |
| Las conversiones explícitas funcionan | 40 % |
| Se demuestra y explica la conversión implícita | 30 % |
| Comentarios claros | 10 % |

## Pista de cara al futuro
Este mismo error aparecerá el día que el robot pida datos por consola: todo lo que entra por `input()` es texto. Entrar un número por teclado y sumarlo sin convertir es el `TypeError` más caro del curso.
