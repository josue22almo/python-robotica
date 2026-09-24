# Actividad 6 — Autonomía: las cuentas del robot

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: d) Se han identificado los distintos tipos de variables. f) Se han creado y utilizado constantes y literales. h) Se han comprobado las conversiones de tipo.

## Contexto

Antes de dar autonomía a un motor hay que hacer cuentas: cuánta energía consume, cuánto dura la batería, cuántas vueltas aguanta. Todo eso son operaciones con números y unidades.

## Objetivo

Combinar constantes, variables de distintos tipos y conversiones en un cálculo útil.

## Lo que debes hacer

1. Crea `solucion/autonomia.py` con estos datos:
   - `CAPACIDAD_BATERIA = 2200` (mAh, constante)
   - `CONSUMO_MOTOR = 350` (mA)
   - `distancia_bateria = 45` (km que recorre con la carga completa, texto: `"45"`, sí, viene de un sensor)
2. Calcula e imprime:
   - la autonomía en horas (capacidad / consumo);
   - cuántos kilómetros da el robot con la batería al `50 %`;
   - cuántas vueltas de rueda da en un kilómetro (usa `PI`, un diámetro de rueda de 8 cm y la constante `PASOS_POR_VUELTA = 1080`).
3. Convierte explícitamente `distancia_bateria` a número **antes** de operar con ella.
4. Todos los resultados se muestran con su unidad (`h`, `km`, `vueltas`).

## Entregable

- `solucion/autonomia.py`.
- La salida de la consola con los tres resultados y sus unidades.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Los tres cálculos son correctos | 40 % |
| La conversión de `distancia_bateria` es explícita y está antes de usarla | 20 % |
| Se usan las constantes, no números sueltos en las fórmulas | 20 % |
| Cada resultado va acompañado de su unidad | 20 % |

## Pista de cara al futuro
Estas cuentas son la base de un proyecto real: elegir batería y motor según la autonomía que quieres. Cuando llegue el bloque de electrónicaDIMENSIONARás el robot con estos mismos números.
