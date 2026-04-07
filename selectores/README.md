# Práctica de selectores

## Indice

- [Práctica de selectores](#práctica-de-selectores)
  - [Indice](#indice)
  - [Prerquisitos](#prerquisitos)
  - [Selectores](#selectores)
    - [Ejercicio 1 - Selector por etiquetas](#ejercicio-1---selector-por-etiquetas)
    - [Ejercicio 2 - Selector por clase](#ejercicio-2---selector-por-clase)
    - [Ejercicio 3 - Selector por id](#ejercicio-3---selector-por-id)
    - [Ejercicio 4 - Selector descendente](#ejercicio-4---selector-descendente)
    - [Ejercicio 5 - Selector de hijo directo](#ejercicio-5---selector-de-hijo-directo)
    - [Ejercicio 6 - Selector de múltiples elementos](#ejercicio-6---selector-de-múltiples-elementos)
    - [Ejercicio 7 - Selector de clase dentro de otro elemento](#ejercicio-7---selector-de-clase-dentro-de-otro-elemento)
    - [Ejercicio 8 - Selector de atributo](#ejercicio-8---selector-de-atributo)
    - [Ejercicio 9 - Pseudoclases básicas](#ejercicio-9---pseudoclases-básicas)
    - [Ejercicio 10 - nth-child](#ejercicio-10---nth-child)
    - [Ejercicio extra](#ejercicio-extra)

## Prerquisitos

Crearemos un fork (copia de repositorio) que nos permiten tomar todo el contenido de un repositorio y hacerlo propio.

Para crearlo simplemente seleccionamos la opción `Create a new fork` desde el repositorio.

![alt text](../assets/github-fork.png)

Una vez copiado el repositorio en nuestra cuenta podremos clonarlo usando el comando `git clone` o desde vsCode

![alt text](../assets/vscode-clone-git.png)

## Selectores

Práctica de selectores.

### Ejercicio 1 - Selector por etiquetas

**Objetivo**: Usar selector de etiquetas.

Abre los archivos [ejercicio1.html](../selectores/ejercicio01/index.html) y [ejercicio1.css](../selectores/ejercicio01/style.css) con el siguiente contenido:

```html
<h1>Título</h1>
<p>Párrafo 1</p>
<p>Párrafo 2</p>
```

> **Consigna**: Cambiar el color de todos los `<p>` a azul (blue).

### Ejercicio 2 - Selector por clase

**Objetivo**: usar clases correctamente

Abre los archivos [ejercicio2.html](../selectores/ejercicio02/index.html) y [ejercicio2.css](../selectores/ejercicio02/style.css) con el siguiente contenido:

```html
<p class="destacado">Importante</p>
<p>Normal</p>
<p class="destacado">Muy importante</p>
```

> **Consigna**: Hacer que todos los elementos con clase `.destacado` tengan fondo amarillo (`background-color`) y texto negrita (`font-weight`)

### Ejercicio 3 - Selector por id

**Objetivo**: diferenciar id vs clase

Abre los archivos [ejercicio3.html](../selectores/ejercicio03/index.html) y [ejercicio3.css](../selectores/ejercicio03/style.css) con el siguiente contenido:

```html
<h1 id="titulo">Mi página</h1>
<h1>Otro título</h1>
```

> **Consigna**: Cambiar el color del elemento con id `titulo`.

### Ejercicio 4 - Selector descendente

**Objetivo**: Diferenciar padres de hijos

Abre los archivos [ejercicio4.html](../selectores/ejercicio04/index.html) y [ejercicio4.css](../selectores/ejercicio04/style.css) con el siguiente contenido:

```html
<div>
  <p>Párrafo dentro</p>
</div>
<p>Párrafo fuera</p>
```

> **Consigna**: solo el párrafo (`<p>`) dentro del `<div>` debe ser verde.

### Ejercicio 5 - Selector de hijo directo

**Objetivo**: Probar selector de hijo directo.

Abre los archivos [ejercicio5.html](../selectores/ejercicio05/index.html) y [ejercicio5.css](../selectores/ejercicio05/style.css) con el siguiente contenido:

```html
<div>
  <p>Hijo directo</p>
  <section>
    <p>Nieto</p>
  </section>
</div>
```

> **Consigna**: Aplicar color azul solo al hijo directo (`<p>` dentro de `<div>`, no el nieto).

### Ejercicio 6 - Selector de múltiples elementos

**Objetivo**: agrupar selectores

Abre los archivos [ejercicio6.html](../selectores/ejercicio06/index.html) y [ejercicio6.css](../selectores/ejercicio06/style.css) con el siguiente contenido:

```html
<h1>Título</h1>
<h2>Subtítulo</h2>
<p>Texto</p>
```

> **Consigna**: Hacer que `<h1>` y `<h2>` tengan el mismo color (por ejemplo violeta).

### Ejercicio 7 - Selector de clase dentro de otro elemento

**Objetivo**: combinar selectores

Abre los archivos [ejercicio7.html](../selectores/ejercicio07/index.html) y [ejercicio7.css](../selectores/ejercicio07/style.css) con el siguiente contenido:

```html
<div>
  <p class="texto">Texto 1</p>
</div>

<section>
  <p class="texto">Texto 2</p>
</section>
```

> **Consigna**: Solo el `.texto` dentro del `<div>` debe ser rojo.

### Ejercicio 8 - Selector de atributo

**Objetivo**: introducir selectores más avanzados.

Abre los archivos [ejercicio8.html](../selectores/ejercicio08/index.html) y [ejercicio8.css](../selectores/ejercicio08/style.css) con el siguiente contenido:

```html
<input type="text">
<input type="password">
<input type="email">
```

> **Consigna**: Cambiar el borde de los inputs de tipo "password" a rojo.

### Ejercicio 9 - Pseudoclases básicas

**Objetivo**: interacción

Abre los archivos [ejercicio9.html](../selectores/ejercicio09/index.html) y [ejercicio9.css](../selectores/ejercicio09/style.css) con el siguiente contenido:

```html
<a href="#">Link 1</a>
<a href="#">Link 2</a>
```

> **Consigna**: Cambiar el color de los links cuando el mouse pasa por arriba (`:hover`).

### Ejercicio 10 - nth-child

**Objetivo**: selectores estructurales

Abre los archivos [ejercicio10.html](../selectores/ejercicio10/index.html) y [ejercicio10.css](../selectores/ejercicio10/style.css) con el siguiente contenido:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
</ul>
```

> **Consigna**: Cambiar el color de los elementos pares y el primer elemento.

### Ejercicio extra

**Objetivo**: colocar todos los ejercicios en una única página.

Crear el directorio `../selectores/ejercicioExtra/index.html` y `../selectores/ejercicioExtra/style.css` con el siguiente contenido:

- Por cada ejercicio (10) crear un `<section id="<ejercicio>` y colocar el contenido del `<body>` dentro.
- Dentro de `style.css` colocar el contenido de cada css agregando antes de cada uno el id (ej: `#ejercicio1 p{}`) para que se aplique solo al section

```html
<section id="ejercicio1">
  ...
</section>
```

```css
#ejercicio1 p {
  color: red;
}
```
