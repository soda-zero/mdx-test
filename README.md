## Componente Imagen

El componente `Imagen` es un componente reutilizable mostrar imágenes con un tamaño y posición personalizables.

### Propiedades

- `src` (obligatorio): La URL de la imagen que se mostrará.
- `alt` (obligatorio): El texto alternativo para la imagen.
- `priority`: Si se especifica, la imagen se cargará con prioridad.
- `position`: La posición de la imagen dentro de su contenedor. Acepta uno de los siguientes valores: `"left"`, `"center"`, `"right"`.
- `size`: El tamaño de la imagen. Acepta uno de los siguientes valores: `"small"`, `"medium"`, `"full"`.

### Ejemplo de Uso

```js

<Imagen src="ejemplo.jpg" alt="Imagen de Ejemplo" position="center" size="medium"/>

```
---
