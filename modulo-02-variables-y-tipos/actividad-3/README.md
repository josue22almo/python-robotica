# Actividad 3 — Constantes: lo que no cambia

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: f) Se han creado y utilizado constantes y literales.

## Contexto

Hay valores que en un robot no cambian nunca: el número de ruedas, la longitud de una vuelta, la constante `PI`. Esos se escriben en MAYÚSCULAS para que cualquier persona que lea el código sepa que no se tocan.

## Objetivo

Distinguir constantes de variables y usarlas en un cálculo real.

## Lo que debes hacer

1. Crea `solucion/constantes.py`.
2. Declara estas constantes en MAYÚSCULAS:
   - `PI = 3.14159`
   - `RUEDAS = 4`
   - `PASOS_POR_VUELTA = 1080`
3. El robot da una vuelta completa a la rueda de radio `RADIO_RUEDA = 3.5` cm.
4. Calcula e imprime:
   - la longitud de una vuelta de la rueda, en cm;
   - cuántas vueltas da el robot para recorrer **5 metros**;
   - cuántos pasos de motor necesita para esa distancia.
5. Declara además una variable normal (`distancia_objetivo = 500`) para comprobar que las constantes y las variables conviven.

## Entregable

- `solucion/constantes.py`.
- La salida de la consola con los tres resultados.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Todas las constantes declaradas en mayúsculas | 25 % |
| Los cálculos son correctos (revisa las unidades) | 40 % |
| Se usan las constantes en los cálculos, no números sueltos | 25 % |
| Comentarios que explican las unidades | 10 % |

## Pista de cara al futuro

La constante `PI` te volverá a aparecer en trigonometría cuando el robot trace una trayectoria curva. Acostúmbrate a escribir el número, la unidad y el significado en un comentario.
