# Simulación de Plasma con el método Particle-in-Cell en 2.5 dimensiones

Este repositorio contiene códigos Python y C++ para simular el comportamiento del plasma mediante el método Particle-in-Cell (PIC) en 2.5 dimensiones. Los códigos fueron diseñados para ser fácilmente modificables y escalables, permitiendo una gran flexibilidad en la simulación de diferentes escenarios.

## Contenido

El repositorio cuenta con los siguientes archivos:

- `pic_2.5D.py`: Código Python para la simulación del plasma mediante PIC en 2.5D.
- `pic_2.5D.cpp`: Código C++ para la simulación del plasma mediante PIC en 2.5D.
- `pic_2.5D_gui.py`: Código Python con interfaz gráfica de usuario para la simulación del plasma mediante PIC en 2.5D.
- `README.md`: Archivo que contiene información sobre el repositorio.

## Requerimientos

Los códigos en Python y C++ requieren las siguientes bibliotecas y herramientas:

- Python 3
- C++11
- NumPy
- Matplotlib

## Uso

El código en Python se puede ejecutar con el comando:

- python pic_2.5D.py

Mientras que el código en C++ se puede compilar y ejecutar con los comandos:

- g++ -o run.o pic_2.5D.cpp

## Interfaz gráfica de usuario

El código Python incluye una interfaz gráfica de usuario (GUI) que permite visualizar la simulación del plasma mediante gráficos interactivos. La GUI se basa en la biblioteca Pygame, por lo que es necesario tenerla instalada para utilizarla.

Para utilizar la GUI, simplemente ejecuta el código `pic_2.5D_gui.py` en lugar de `pic_2.5D.py`. La GUI mostrará una ventana con los siguientes elementos:

- Un listbox para determinar los tipos de graficos que se quieren visualizar
- Una lista de parámetros para modificar las variables de iniciación de la simulación
- Un botón para pausar y reanudar la simulación.

Puedes hacer clic y arrastrar en el gráfico para mover la cámara y ver diferentes áreas de la simulación. Además, puedes utilizar las teclas W, A, S y D para mover la cámara arriba, izquierda, abajo y derecha, respectivamente.

¡Diviértete explorando la simulación del plasma con la interfaz gráfica de usuario!

## Contribuciones

Las contribuciones son bienvenidas y se pueden realizar mediante pull requests. Siéntete libre de reportar problemas o sugerir mejoras mediante issues.

## Licencia

Este repositorio está bajo la licencia MIT.
