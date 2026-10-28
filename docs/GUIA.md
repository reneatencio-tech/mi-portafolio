# Guía del proyecto Tienda TECSUP

Documentación del Laboratorio N.° 3 del curso Diseño de Interfaces de Programación Avanzado de TECSUP.

## Descripción del proyecto

Tienda TECSUP es un proyecto web que utiliza HTML, CSS y JavaScript para mostrar productos y calcular el total de un carrito de compras. Durante el laboratorio se identificaron y corrigieron dos errores mediante Git y GitHub.

### Errores identificados

- **Error de cálculo:** el total mostraba S/ 43.00 en lugar de S/ 68.00.
- **Error de estilos:** `index.html` hacía referencia a `estilo.css` en lugar de `estilos.css`.

## Herramientas utilizadas

- **Git:** control de versiones.
- **GitHub:** repositorios remotos, Issues y Pull Requests.
- **Visual Studio Code:** edición del proyecto.
- **HTML, CSS y JavaScript:** tecnologías del sitio web.

## Pasos para descargar y ejecutar el proyecto

1. Abrir el repositorio original en GitHub.
2. Crear un fork en la cuenta personal.
3. Clonar el fork utilizando `git clone`.
4. Abrir la carpeta en Visual Studio Code.
5. Ejecutar `index.html` en un navegador.
6. Verificar el cálculo del carrito y la aplicación de los estilos.

```bash
git clone https://github.com/reneatencio-tech/tienda-tecsup.git
cd tienda-tecsup
code .
```

## Archivos principales

| Archivo | Descripción |
|---|---|
| `index.html` | Estructura de la tienda y enlace a los estilos. |
| `estilos.css` | Presentación visual de la página. |
| `script.js` | Cálculo del total del carrito. |
| `README.md` | Información general del proyecto. |

## Correcciones realizadas

### Corrección del total del carrito

Se modificó la función `calcularTotal()` para multiplicar el precio por la cantidad de cada producto.

```javascript
total = total + producto.precio * producto.cantidad;
```

Resultado esperado: **S/ 68.00**.

### Corrección de los estilos CSS

Se corrigió el enlace de la hoja de estilos dentro de `index.html`.

```html
<link rel="stylesheet" href="estilos.css">
```

## Lista de tareas

- [x] Crear el fork y clonar el repositorio.
- [x] Reportar el error de cálculo mediante el Issue #371.
- [x] Crear el Pull Request #372.
- [x] Reportar el error de estilos mediante el Issue #375.
- [x] Crear el Pull Request #377.
- [ ] Esperar la revisión e integración de las contribuciones por el docente.

## Enlaces del proyecto

- [Repositorio original de Tienda TECSUP](https://github.com/jeisson-tecsup/tienda-tecsup)
- [Mi fork de Tienda TECSUP](https://github.com/reneatencio-tech/tienda-tecsup)
- [Documentación oficial de GitHub](https://docs.github.com/es)

## Evidencia del proyecto

![Captura del proyecto Tienda TECSUP](../img/captura.png)

## Conclusión

Este proyecto permitió aplicar un flujo de trabajo colaborativo mediante Git y GitHub, identificando errores, registrándolos mediante Issues y proponiendo soluciones mediante Pull Requests. La documentación en Markdown facilita que otros estudiantes comprendan el proyecto y puedan reproducir sus resultados.
