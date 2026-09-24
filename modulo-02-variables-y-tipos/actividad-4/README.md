# Actividad 4 — Verdadero o falso

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: d) Se han identificado los distintos tipos de variables y la utilidad específica de cada uno.

## Contexto

El tipo `bool` solo tiene dos valores: `True` y `False`. Son las respuestas a las preguntas que se le hacen a un robot: ¿hay batería? ¿ve la pared? ¿está la carga lista?

## Objetivo

Trabajar con booleanos y entender cómo se imprimen.

## Lo que debes hacer

1. Crea `solucion/booleanos.py` con cuatro booleanos con sentido de robot:
   - `bateria_ok` (¿queda más del 20 %?)
   - `hay_pared` (respuesta inventada por ti)
   - `cargando`
   - `modo_autonomo`
2. Imprime cada booleano con su valor.
3. Imprime además, para cada uno, una frase con su **significado** usando condiciones simples: por ejemplo `bateria_ok = True → "puede seguir"`, y `False → "debe parar"`.
4. Termina mostrando cuántos booleanos son `True` (sumándolos con `True`/`False`, que en Python valen 1/0).

## Entregable

- `solucion/booleanos.py`.
- La salida de la consola.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Los cuatro booleanos están bien nombrados y bernilai | 30 % |
| Cada booleano se traduce a una frase con significado | 40 % |
| La cuenta de los `True` es correcta | 20 % |
| Comentario explicando por qué los booleanos son 1/0 | 10 % |

## Pista de cara al futuro

Estas preguntas son la entrada del módulo de condiciones. Lo que aquí haces con cuatro `if` escritos a mano,soon lo harás con un `if` que decida la orden del robot.
