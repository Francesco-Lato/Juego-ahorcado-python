# Juego del Ahorcado

Este es un simple juego del Ahorcado implementado en Python. El juego permite al jugador seleccionar un nivel de dificultad y adivinar una palabra secreta dentro de un número limitado de intentos.

## Autor
- **Francesco Latorrata**

## Descripción del Juego

El juego del Ahorcado consiste en adivinar una palabra secreta letra por letra. El jugador tiene un número limitado de intentos para adivinar la palabra correcta. Si el jugador adivina todas las letras de la palabra antes de agotar los intentos, gana el juego. De lo contrario, pierde.

## Características

- **Niveles de Dificultad**: El juego ofrece tres niveles de dificultad:
  - **Fácil**: Palabras de 1 a 4 letras.
  - **Medio**: Palabras de 5 a 6 letras.
  - **Difícil**: Palabras de 7 a 10 letras.

- **Interfaz de Menú**: El juego presenta un menú interactivo para que el jugador seleccione el nivel de dificultad o salga del juego.

- **Gestión de Intentos**: El jugador tiene 3 intentos para adivinar la palabra secreta.

## Cómo Jugar

1. **Iniciar el Juego**: Ejecuta el script de Python.
2. **Seleccionar Nivel**: Elige un nivel de dificultad (1: Fácil, 2: Medio, 3: Difícil, 4: Salir).
3. **Adivinar Letras**: Introduce letras para adivinar la palabra secreta.
4. **Ganar o Perder**: Si adivinas la palabra antes de agotar los intentos, ganas. Si no, pierdes.

## Estructura del Código

El código está organizado en varias funciones que manejan diferentes aspectos del juego:

- **`menu()`**: Muestra el menú principal del juego.
- **`elegir_nivel()`**: Permite al jugador seleccionar el nivel de dificultad.
- **`introducir_palabras(lista)`**: Permite al usuario introducir las palabras que se usarán en el juego.
- **`ordenar_listado(lista)`**: Ordena las palabras en los diferentes niveles de dificultad.
- **`mostrar_revelada(palabra, letras_adivinadas)`**: Muestra las letras adivinadas y oculta las no adivinadas.
- **`palabra_secreta(lista, nivel)`**: Selecciona una palabra secreta aleatoria del nivel elegido.
- **`jugar(nivel)`**: Maneja el flujo del juego, incluyendo la lógica de adivinanza y la gestión de intentos.

## Ejecución

Para ejecutar el juego, simplemente corre el script de Python en tu entorno:

```bash
python ahorcado.py
