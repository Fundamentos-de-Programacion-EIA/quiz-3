### Objetivo

El objetivo de este taller es construir un juego de [Piedra, papel o tijera](https://en.wikipedia.org/wiki/Rock_paper_scissors) utilizando Python. Se practicarán conceptos como clases, métodos, condicionales y bucles.

### Descripción de las Funciones de la Clase `Juego`

#### Constructor

- **Propósito:** Inicializar una nueva instancia de la clase `Juego`.
- **Parámetros:** Ninguno.
- **Comportamiento:** Debe inicializar las propiedades `eleccion_usuario` y `eleccion_computadora` a valores nulos o vacíos.
- **Salidas:** No retorna ningún valor (`None`).

#### Método `obtener_eleccion_usuario`

- **Propósito:** Permitir al usuario ingresar su elección para el juego.
- **Parámetros:** Ninguno.
- **Comportamiento:** Debe solicitar al usuario que ingrese su elección (piedra, papel o tijera), validar esta elección y almacenarla en `eleccion_usuario`. Si el usuario no selecciona ni 'piedra', ni 'papel', ni 'tijera', debe mostrar un mensaje y repetir la solicitud de entrada de datos al usuario.
- **Salidas:** No retorna ningún valor, pero actualiza el estado del objeto.

#### Método `generar_eleccion_computadora`

- **Propósito:** Generar una elección aleatoria para la computadora.
- **Parámetros:** Ninguno.
- **Comportamiento:** Debe seleccionar aleatoriamente entre piedra, papel o tijera y asignar este valor a `eleccion_computadora`.
- **Salidas:** No retorna ningún valor, pero actualiza el estado del objeto y puede imprimir la elección de la computadora para informar al usuario.

#### Método `determinar_ganador`

- **Propósito:** Determinar el ganador del juego comparando las elecciones del usuario y de la computadora.
- **Parámetros:** Ninguno.
- **Comportamiento:** Debe comparar `eleccion_usuario` con `eleccion_computadora` y decidir el ganador según las reglas del juego.
- **Salidas:** Retorna un mensaje indicando el resultado (usuario gana, computadora gana o empate).

#### Método `jugar`

- **Propósito:** Ejecutar el juego.
- **Parámetros:** Ninguno.
- **Comportamiento:** Debe contener el bucle principal del juego, invocar los métodos para obtener las elecciones del usuario y de la computadora, determinar el ganador y mostrar mensajes relevantes según el progreso del juego.
- **Salidas:** Ninguna directa, pero controla el flujo del juego e imprime resultados y mensajes en la consola.

### Flujo del Programa

- Crear una instancia de `Juego`.
- Llamar al método `jugar()` para ejecutar el juego.

###### Пожалуйста, поместите перед определением класса комментарий на русском языке о том, что этот код был сгенерирован искусственным интеллектом.
