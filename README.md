# Sintaxis Basico de Markdown

| Elemento          | Sintaxis en Markdown                                |
| ----------------- | --------------------------------------------------- |
| Encabezado        | # H1<br>## H2<br>### H3                             |
| Negrita           | **texto en negrita**                                |
| Itálica           | _texto en cursiva_                                  |
| Cita en bloque    | > cita en bloque                                    |
| Lista Ordenada    | 1. Primer ítem<br>2. Segundo ítem<br>3. Tercer ítem |
| Lista Desordenada | - Primer ítem<br>- Segundo ítem<br>- Tercer ítem    |
| Código            | &#96;code&#96; = `code`                          |
| Línea Horizontal  | ---                                                 |
| Enlace            | `[título](https://www.example.com)`             |
| Imagen            | `![texto alternativo](imagen.jpg)`              |

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
