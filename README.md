# Python y Robótica

Conjunto de actividades evaluables (**40 % de la nota**) para la asignatura *Robótica y fundamentos de programación* (1r SMX). El 60 % restante es el proyecto final: el robot.

Curso: 2026-2027

## Consideraciones importantes sobre las actividades

- En este repositorio encontrarás los enunciados de las actividades de la asignatura.
- Verás que **no están todas publicadas**. Debes ir actualizando el repositorio a medida que el profesor abra cada módulo.
- Para mantener los enunciados al día, entra en el [Aula de repos](https://josue.alcantaramoreno.com/aula/) con el código de asignatura `python-2627`.
- Dentro de cada actividad, el enunciado está en un archivo `README.md`. En ese mismo archivo aparece la **fecha límite de entrega** cuando el profesor abra la actividad.
- Entregar fuera de esa fecha supone suspender la actividad. Los cambios hechos a posteriori también se descartarán.
- El 40 % de la nota sale de aquí (nota continua).

## Estructura de carpetas

Cada módulo del curso tiene sus actividades. La estructura es:

```shell
/modulo-01-hola-mundo
  /actividad-1
    README.md      # enunciado de la actividad
    /solucion       # aquí subes tu código
/modulo-02-variables-y-tipos
  /actividad-2
  /actividad-3
  ...
```

> Es un ejemplo. El número de actividades depende de lo que se haya abierto hasta ese momento.

## Cómo entregar tu solución a una actividad

| Si usas la IA, quiero que subas la conversación. Si no sabes hacerlo, pregúntale a Google.

Dentro de cada actividad, crearás una carpeta `/solucion` donde subirás el código. Esta es la estructura que espero:

```shell
/modulo-01-hola-mundo
  /actividad-1
    README.md
    /solucion
      hola.py
      hola-salida.txt   # la salida de la consola, en un fichero
```

Cuando el enunciado pida la salida del programa, guárdala en un fichero de texto llamado `<nombre-del-programa>-salida.txt` dentro de `solucion/`.

Commitea a menudo. Una entrega con un solo commit de 400 líneas no se revisa.

## Herramientas

- Python 3.12 o superior.
- El editor que prefieras: VS Code, PyCharm, IDLE... lo importante es que lo conozcas.
- En el aula de actividades se corrigen las Ip implicadas en los ejercicios de cada módulo.

## Criterios generales de evaluación

Se aplican a todas las actividades. Los pesos concretos de cada actividad están en su enunciado.

| Criterio | Peso |
|---|---|
| El programa funciona y cumple el enunciado | 50 % |
| Código claro: nombres buenos, sin repetir, funciones cortas | 20 % |
| Comentarios | 10 % |
| Commits y carpetas bien organizados | 10 % |
| Conversación de IA subida, si la has usado | 10 % |

## El proyecto final

El 60 % de la nota es el proyecto: un robot que funcione. Se hace en grupos y se entrega al final del curso, con su documentación técnica y su presentación. El enunciado se publicará aquí más adelante.

## Dudas

Las dudas de código se preguntan en clase. Las de enunciado, en el aula de repos.
