# Fractol

## Descripción

Este proyecto es parte del cursus 42 y se llama **fractol**. El objetivo es explorar fractales matemáticos a través de una interfaz gráfica. Para ello se utiliza la minilibx. Actualmente, solo está programado el conjunto de Mandelbrot. El proyecto está en desarrollo y se publica a modo representativo de los que es proyecto. Tiene como recursos la libreria gráfica citada y la una librería propia **libft** realizada en un proyecto anterior del cursus.

## Compilación

Para compilar el proyecto, usa el siguiente comando:

```sh
make
```

Si realizas cambios en `fractol.h`, recompila el proyecto con:

```sh
make re
```
Para borrar los objetos y el ejecutable:

```sh
make fclean
```
## Ejecución

Para ejecutar el programa, utiliza el siguiente comando:

```sh
./fractol mandelbrot
```

## Controles

- **ESC** o cerrar la ventana: Finaliza el programa.
- **Flechas del teclado**: Mueve la imagen en traslación.
- **Scroll del ratón**: Hace zoom (Nota: la implementación del zoom no está bien).

## Nota

El renderizado es bastante lento y necesita optimización. Para mejorar la velocidad, se recomienda:
- Crear una ventana más pequeña.
- Disminuir el valor de `MAXITER` (número máximo de iteraciones de la ecuación de Mandelbrot).
