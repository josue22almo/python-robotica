# Actividad 7 — El perfil completo del robot

- *Módulo*: 2 · Variables y tipos
- *Fecha límite de entrega*: pendiente de apertura
- *RA 1*: d), e), f) y h) de los tipos de variables, constantes, literales y conversiones.

## Contexto

Con variables, constantes y conversiones ya se puede describir un robot entero. Esta actividad es la primera donde todo lo aprendido tiene que funcionar junto.

## Objetivo

Programa un resumen del robot con los cinco tipos de datos trabajando a la vez.

## Lo que debes hacer

1. Crea `solucion/perfil.py`.
2. Declara como mínimo estas variables, cada una con su tipo:
   - `nombre` (str), `version` (str), `anio` (int), `altura_cm` (float), `peso_kg` (float), `autonomia_h` (float), `autonomo` (bool).
3. Crea la constante `VERSION_ESPERADA = "v1.0"` y comprueba con un `if` si la versión de tu robot es la esperada (esto es un adelanto del módulo de condiciones).
4. Muestra una ficha con una línea por variable, alineada, incluyendo el tipo.
5. Calcula la densidad del robot (`peso / (altura * ancho * fondo)`, invéntate las medidas que falten) y muéstrala con dos decimales.

## Entregable

- `solucion/perfil.py`.
- La salida de la consola con la ficha completa.

## Criterios de evaluación

| Criterio | Peso |
|---|---|
| Todas las variables con el tipo correcto | 30 % |
| La comparación de versión con `if` funciona | 20 % |
| La ficha está alineada y con el tipo visible | 20 % |
| El cálculo de densidad es correcto | 20 % |
| Comentarios y nombres claros | 10 % |

## Pista de cara al futuro
Este `if` es el primero de tu vida. En el módulo de condiciones verás cómo una decisión envuelve un bloque entero de código y qué pasa cuando el robot tiene que elegir entre dos rutas.
