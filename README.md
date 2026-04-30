# TP3-stock-multirubro

**Trabajo Práctico N° 3 — Sistema de Gestión de Stock para un Comercio Multirubro**  
Laboratorio de Programación — 6° G

---

## Descripción

Sitio web estático que simula un **Sistema de Gestión de Stock** para el comercio *"El Almacén"*, un negocio multirubro que abarca tres rubros: **Kiosco**, **Librería** y **Regalería**.

Permite visualizar el inventario por rubro, gestionar productos mediante un formulario y consultar el historial de ventas y pagos a cuenta.

---

## Estructura de archivos

```
TP3-stock-multirubro/
├── index.html          → Página principal: presentación y productos destacados
├── gestion.html        → Formulario para agregar/editar productos e inventario actual
├── ventas.html         → Registro de transacciones y pagos a cuenta
├── estilos.css         → Hoja de estilos externa (única)
├── logo.svg            → Logo del comercio (imagen local)
├── icono-kiosco.svg    → Ícono rubro Kiosco (imagen local)
├── icono-libreria.svg  → Ícono rubro Librería (imagen local)
├── icono-regaleria.svg → Ícono rubro Regalería (imagen local)
└── README.md
```

---

## Páginas

### `index.html` — Inicio
- Presentación del comercio con logo y rubros.
- Tres tablas de productos destacados (5 productos por rubro: Kiosco, Librería y Regalería) con columnas Nombre, Precio y Stock.
- Tarjetas de rubros organizadas con **CSS Grid**.
- Accesos rápidos a Gestión y Ventas.

### `gestion.html` — Gestión de Productos
- Formulario para agregar/editar productos con campos: Nombre, Rubro, Precio, Stock, Proveedor y Código Interno.
- Campos organizados con **CSS Grid** (dos columnas).
- Botón "Guardar Producto" y botón "Limpiar Campos" (sin funcionalidad JS).
- Tabla con inventario actual.

### `ventas.html` — Ventas
- Resumen del mes en tarjetas de estadísticas con **Flexbox**.
- Tabla de transacciones con columnas Fecha, Producto, Rubro, Cantidad y Total.
- Sección "Pagos a cuenta" con lista de clientes con saldo pendiente.

---

## Requisitos cumplidos

### HTML
- Etiquetas semánticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<table>`, `<form>`.
- Imágenes locales SVG con atributos `alt` y `title`.
- Atributo `style` en elementos de imagen (`height`, `width`).
- Atributo `title` en botones, inputs y enlaces.
- Comentarios descriptivos en el HTML.
- Navegación con indicador de página activa (clase `activo`).
- Breadcrumbs en páginas secundarias.

### CSS (archivo único: `estilos.css`)
- Selectores de clase (`.tabla-stock`, `.rubros-grid`, etc.) e ID (`#gestion-productos`, `#pagos-cuenta`).
- Colores en **hexadecimal** (`#2c3e50`), **RGB** (`rgb(44, 62, 80)`), **HSL** (`hsl(210, 29%, 24%)`) y **RGBA** (`rgba(44, 62, 80, 0.06)`).
- Márgenes, padding y bordes en múltiples elementos.
- Estilos para tablas y formularios.
- **Flexbox** en: header, navegación, accesos rápidos, tarjetas de estadísticas, botones del formulario y lista de pagos.
- **CSS Grid** en: tarjetas de rubros (3 columnas) y campos del formulario (2 columnas).
- Estilos `hover` en: enlaces de nav, botones, tarjetas, filas de tabla, items de lista y footer.
- Variables CSS con `:root` para consistencia de colores.
- Comentarios explicativos en todo el archivo CSS.

---

## Publicación

- **Repositorio:** `TP3-stock-multirubro`
- **GitHub Pages:** activado desde *Settings > Pages > rama main*
- URL de acceso: `https://[usuario].github.io/TP3-stock-multirubro/`

---

## Cómo usar

1. Clonar o descargar el repositorio.
2. Abrir `index.html` en el navegador (no requiere servidor).
3. Navegar entre las páginas usando el menú superior.

---

*&copy; 2026 — Comercio Multirubro "El Almacén de 6°G"*
