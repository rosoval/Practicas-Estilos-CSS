# Práctica de FlexBox y GridBox

## Indice

- [Práctica de FlexBox y GridBox](#práctica-de-flexbox-y-gridbox)
  - [Indice](#indice)
  - [Ejercicios](#ejercicios)
    - [Ejercicio 1 - Centrado básico (flex)](#ejercicio-1---centrado-básico-flex)
    - [Ejercicio 2 - Menú horizontal](#ejercicio-2---menú-horizontal)
    - [Ejercicio 3 - Espaciado automático](#ejercicio-3---espaciado-automático)
    - [Ejercicio 4 - Cards con wrap](#ejercicio-4---cards-con-wrap)
    - [Ejercicio 5 - Grid básico](#ejercicio-5---grid-básico)
    - [Ejercicio 6 - Galería de imágenes](#ejercicio-6---galería-de-imágenes)
    - [Ejercicio 7 - Elemento que ocupa varias columnas](#ejercicio-7---elemento-que-ocupa-varias-columnas)
    - [Ejercicio 8 - Layout de páginas (Grid clásico)](#ejercicio-8---layout-de-páginas-grid-clásico)
    - [Ejercicio 9 - Grid + Flex combinado](#ejercicio-9---grid--flex-combinado)

## Ejercicios

Por cada ejercicio crear un directorio `flex_gird/ejercicio<num>/` con su `index.html` y `style.css` correspondiente.

### Ejercicio 1 - Centrado básico (flex)

**Objetivo**: Centrar un elemento en el medio de la pantalla.

```html
<div class="contenedor">
  <div class="caja"></div>
</div>
```

> **Consigna**: la caja debe quedar perfectamente centrada (horizontal y vertical)

### Ejercicio 2 - Menú horizontal

**Objetivo**: Alinear elementos en fila

```html
<nav class="menu">
  <a>Inicio</a>
  <a>Productos</a>
  <a>Contactos</a>
</nav>
```

> **Consigna**:
>
> - (1) Mostrar los links en fila
> - (2) Separarlos uniformemente
> - (3) Centrar verticalmente

### Ejercicio 3 - Espaciado automático

**Objetivo**: usar `space-between`

```html
<header class="header">
  <div>Logo</div>
  <div>Usuario</div>
</header>
```

> **Consigna**:
>
> - (1) Logo a la izquierda
> - (2) Usuario a la derecha
> - (3) Ambos centrados verticalmente

### Ejercicio 4 - Cards con wrap

**Objetivo**: hacer layouts responsive simple

```html
<div class="contenedor">
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
</div>
```

> **Consigna**:
>
> - (1) Mostrar cards en fila
> - (2) Que bajen de línea si no entran
> - (3) Separación entre ellas

### Ejercicio 5 - Grid básico

**Objetivo**: crear estructura simple

```html
<div class="grid">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
```

> **Consigna**:
>
> - (1) Crea 3 columnas iguales
> - (2) Agrega espacio entre ellas

### Ejercicio 6 - Galería de imágenes

**Objetivo**: Usar `repeat` y `fr`

```html
<div class="galeria">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
```

> **Consigna**:
>
> - (1) 3 columnas iguales
> - (2) filas automáticas
> - (3) Espaciado uniforme

### Ejercicio 7 - Elemento que ocupa varias columnas

**Objetivo**: usar `gird-column`

```html
<div class="grid">
  <div class="grande"></div>
  <div></div>
  <div></div>
</div>
```

> **Consigna**: El primer elemento debe ocupar 2 columnas

### Ejercicio 8 - Layout de páginas (Grid clásico)

**Objetivo**: Estructura completa

```html
<div class="layout">
  <header>Header</header>
  <aside>Sidebar</aside>
  <main>Contenido</main>
  <footer>Footer</footer>
</div>
```

> **Consigna**:
>
> - (1) Header arriba (toda la fila)
> - (2) Sidebar a la izquierda (25%)
> - (3) Main a la derecha (75%)
> - (4) Footer abajo toda la fila

### Ejercicio 9 - Grid + Flex combinado

**Objetivo**: usar ambos juntos

```html
<div class="layout">
  <header>
    <div>Logo</div>
    <nav>
      <a>Inicio</a>
      <a>Productos</a>
      <a>Contactos</a>
    </nav>
  </header>
  <main>Contenido</main>
  <footer>Footer</footer>
</div>
```


