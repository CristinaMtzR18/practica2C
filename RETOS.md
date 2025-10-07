# Retos y pistas (sin spoilers exactos)
Corrige los problemas siguientes (hay muchos más de los listados):

## HTML
- Atributos mal escritos (`integrityy`, `novalidates`, `data-bs-ride`, `data-bs-target`, `aria-controls`).
- IDs duplicados y referencias que no coinciden entre `data-bs-target` y `id`.
- Clases de Bootstrap con errores tipográficos (`container-fluids`, `sticky-topx`, `col-mb-3`, `table-stripped`, `table-responsiv`, `ratio-15x9`).
- Estructuras de *grid* que no suman 12 columnas (`product.html` 6 + 5 + 3).
- Elementos sin `alt` y texto accesible; mal uso de `role`.
- Orden y duplicación de los scripts de Bootstrap.
- Semántica y jerarquías de encabezados inconsistentes.

## CSS
- Propiedades con errores (`background-colorr`, `--brand-contrst`). 
- Selectores mal escritos (`.card-tilte`).
- Conflictos de especificidad y reglas duplicadas (`#productTitle`). 
- Animación/transición aplicada en el estado `:hover` en lugar del estado base.

## Componentes avanzados de Bootstrap
- Carrusel que no avanza por `data-bs-ride` mal escrito.
- Botones del carrusel apuntando a un ID incorrecto.
- Offcanvas y acordeón con `aria-controls`/`data-bs-parent` inconsistentes.
- `ratio` no válido en el mapa.

## Sugerencias
- Valida HTML con el **W3C Validator**.
- Revisa la consola del navegador para errores de JS/DOM.
- Consulta la doc oficial de **Bootstrap 5.3**.
