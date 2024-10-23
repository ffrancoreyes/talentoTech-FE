# talentoTech-FE
Hola, Soy ***Fabrizzio Franco Reyes***, estudiante de Ingeniería en Sistemas de la Información en la **Universidad Tecnológica Nacional** y creador de este repositorio donde se fueron subiendo todos los contenidos vistos durante la cursada del curso de desarollo web FrontEnd de **Talento Tech**.


#### En caso de querer realizar un cambio al contenido
- Envía la solicitud de Issue a través de Github
- Contáctame
    * Mail: ffrancoreyes@frba.utn.edu.ar
    * Teléfono: +541151489765

#### Información Importante:
- En caso de usar de forma didáctica este repositorio, **dar créditos**.

## Indice:
- [talentoTech-FE](#talentotech-fe)
      - [En caso de querer realizar un cambio al contenido](#en-caso-de-querer-realizar-un-cambio-al-contenido)
      - [Información Importante:](#información-importante)
  - [Indice:](#indice)
  - [Clase 1 - 10/09/2024](#clase-1---10092024)
  - [Clase 2 - 17/09/2024](#clase-2---17092024)
    - [Etiquetas básicas de HTML](#etiquetas-básicas-de-html)
      - [Etiquetas esenciales:](#etiquetas-esenciales)
      - [Etiquetas de contenido:](#etiquetas-de-contenido)
      - [Etiquetas de listas:](#etiquetas-de-listas)
      - [Etiquetas de tablas:](#etiquetas-de-tablas)
      - [Etiquetas de enlaces:](#etiquetas-de-enlaces)
    - [Selectores CSS](#selectores-css)
    - [Propiedades CSS comunes](#propiedades-css-comunes)
    - [Cómo incluir CSS en HTML](#cómo-incluir-css-en-html)
    - [Cascada y Especificidad](#cascada-y-especificidad)
    - [Algunas propiedades de CSS](#algunas-propiedades-de-css)
  - [Clase 6 - 22/10/2024](#clase-6---22102024)
    - [Unidades de medidas: Absolutas](#unidades-de-medidas-absolutas)
      - [Principales Unidades Absolutas:](#principales-unidades-absolutas)
    - [Unidades de medidas: Relativas](#unidades-de-medidas-relativas)
      - [Principales Unidades Relativas:](#principales-unidades-relativas)
    - [Comparativa Absolutas vs Relativas](#comparativa-absolutas-vs-relativas)
    - [Uso de colores en css](#uso-de-colores-en-css)
      - [Formas de Especificar Colores en CSS:](#formas-de-especificar-colores-en-css)
      - [Ejemplo de uso de colores en CSS:](#ejemplo-de-uso-de-colores-en-css)
    - [Consideraciones:](#consideraciones)
    - [Uso de background:](#uso-de-background)
      - [Principales Propiedades de Fondo en CSS:](#principales-propiedades-de-fondo-en-css)
      - [Uso de la Propiedad `background` (shorthand):](#uso-de-la-propiedad-background-shorthand)
      - [Ejemplo Completo con Colores e Imágenes de Fondo:](#ejemplo-completo-con-colores-e-imágenes-de-fondo)
    - [Uso de fuentes y tipografías](#uso-de-fuentes-y-tipografías)
    - [Propiedades Básicas de Fuentes en CSS:](#propiedades-básicas-de-fuentes-en-css)
    - [Fuentes Web y Google Fonts:](#fuentes-web-y-google-fonts)
      - [1. **Usar Google Fonts**:](#1-usar-google-fonts)
      - [2. **@font-face** (Cargar Fuentes Personalizadas):](#2-font-face-cargar-fuentes-personalizadas)
    - [Ejemplo Completo:](#ejemplo-completo)


## Clase 1 - 10/09/2024
En la primer clase de introducción se vieron cosas como instalar VSCODE - Extensiónes de VSCODE para el desarrollo web y estructura básica de una página (HTML).

## Clase 2 - 17/09/2024

### Etiquetas básicas de HTML

#### Etiquetas esenciales:

* **`<!DOCTYPE html>`**: Define el tipo de documento HTML, asegurando que el navegador interprete correctamente la página.
* **`<html>`**: Es la etiqueta raíz del documento HTML que envuelve todo el contenido de la página.
* **`<head>`**: Contiene metadatos sobre el documento, como enlaces a archivos CSS, scripts o información de SEO.
* **`<title>`**: Define el título del documento, que se muestra en la pestaña del navegador.
* **`<body>`**: Contiene el contenido visible de la página web (texto, imágenes, etc.).

#### Etiquetas de contenido:

* **`<h1>` a `<h6>`**: Define encabezados de distintos niveles de importancia, donde `<h1>` es el más importante y `<h6>` el menos.
* **`<p>`**: Define un párrafo de texto.
* **`<br>`**: Inserta un salto de línea.
* **`<hr>`**: Inserta una línea horizontal para dividir secciones.
* **`<div>`**: Define una división o sección en el documento, útil para agrupar contenido y aplicarle estilos.
* **`<span>`**: Define una sección dentro de una línea de texto, ideal para aplicar estilos en línea.
* **`<pre>`**: Muestra texto preformateado, respetando espacios y saltos de línea tal como aparecen en el código fuente.
* **`<blockquote>`**: Define una cita larga de texto, comúnmente usada para citas de fuentes externas.
* **`<code>`**: Define un fragmento de código en línea, usado para mostrar ejemplos de código.

#### Etiquetas de listas:

* **`<ul>`**: Define una lista desordenada, comúnmente mostrada con viñetas.
* **`<ol>`**: Define una lista ordenada, normalmente numerada.
* **`<li>`**: Define un elemento de una lista.
* **`<dl>`**: Define una lista de definiciones.
* **`<dt>`**: Define un término en una lista de definiciones.
* **`<dd>`**: Define la descripción o definición de un término en una lista de definiciones.

#### Etiquetas de tablas:

* **`<table>`**: Define una tabla en HTML.
* **`<tr>`**: Define una fila dentro de una tabla.
* **`<td>`**: Define una celda dentro de una fila en una tabla.
* **`<th>`**: Define una celda de encabezado dentro de una tabla, generalmente alineada al centro o en negrita.
* **`<caption>`**: Define un título o descripción para una tabla.

#### Etiquetas de enlaces:

* **`<a>`**: Define un enlace a otra página web o recurso, utilizando el atributo `href` para definir la URL de destino.
  
  ```html
  <a href="https://www.example.com">Visita nuestro sitio</a>

#### Etiquetas de multimedia:

* **`<img>`**: Inserta una imagen.
* **`<audio>`**: Inserta un archivo de audio.
* **`<video>`**: Inserta un archivo de vídeo.

#### Etiquetas de formularios:

* **`<form>`**: Define un formulario.
* **`<input>`**: Define un campo de entrada en un formulario (texto, contraseña, botón, etc.).
* **`<textarea>`**: Define un área de texto en un formulario.
* **`<button>`**: Define un botón.
* **`<select>`**: Define una lista desplegable.
* **`<option>`**: Define una opción en una lista desplegable.
* **`<label>`**: Define una etiqueta para un elemento de formulario.
* **`<fieldset>`**: Agrupa elementos relacionados en un formulario.
* **`<legend>`**: Define un título para un `<fieldset>`.

#### Etiquetas semánticas:

* **`<article>`**: Define un artículo independiente.
* **`<aside>`**: Define contenido aparte del contenido principal (ej. una barra lateral).
* **`<footer>`**: Define el pie de página de un documento o sección.
* **`<header>`**: Define la cabecera de un documento o sección.
* **`<nav>`**: Define un conjunto de enlaces de navegación.
* **`<section>`**: Define una sección en un documento.


## Clase 3 - 24/09/2024
### Listas en HTML
Las listas en HTML te permiten organizar la información de forma estructurada. Hay dos tipos principales de listas:

#### Listas desordenadas (`<ul>`)

*   Se usan para elementos que no siguen un orden específico.
*   Se definen con la etiqueta `<ul>`.
*   Cada elemento de la lista se define con la etiqueta `<li>`.

#### Listas ordenadas (`<ol>`)
*   Se usan para elementos que siguen un orden secuencial.
*   Se definen con la etiqueta `<ol>`.
*   Cada elemento de la lista se define con la etiqueta `<li>`.

### Enlaces

Los enlaces son la esencia de la web, permitiendo a los usuarios navegar entre diferentes páginas y recursos. En HTML, se crean usando la etiqueta `<a>`, que significa "anchor" (ancla).

#### Anatomía de un enlace

* **`<a>`**: Etiqueta que define el enlace.
  * **href**: Atributo que especifica la URL (dirección web) a la que apunta el enlace.
  * **"Texto del enlace"**: El texto visible que los usuarios hacen clic para seguir el enlace.

#### Tipos de enlaces

1. **Absolutos**: Incluyen la URL completa.
   * Ejemplo: `<a href="https://www.google.com">Google</a>`
   
2. **Relativos**: Hacen referencia a una ubicación relativa al documento actual.
   * Ejemplo: `<a href="otra_pagina.html">Otra página</a>`
   
3. **En la misma página**: Apuntan a una sección específica dentro de la misma página usando un ancla (`#`).
   * Ejemplo: `<a href="#seccion2">Ir a la sección 2</a>` (requiere un elemento con `id="seccion2"` en la página)

4. **A recursos externos**: Pueden enlazar a archivos PDF, imágenes, etc.
   * Ejemplo: `<a href="documento.pdf">Descargar PDF</a>`

#### Atributos importantes

* **target**: Controla cómo se abre el enlace:
  * `_blank`: Abre el enlace en una nueva pestaña o ventana.
  * `_self`: Abre el enlace en la misma pestaña o ventana (valor por defecto).
  * `_parent`: Abre el enlace en el marco padre.
  * `_top`: Abre el enlace en la ventana completa.
  
* **title**: Proporciona información adicional que se muestra al pasar el cursor sobre el enlace.

* **download**: Indica al navegador que descargue el recurso enlazado en lugar de abrirlo.

* **rel**: Define la relación entre el documento actual y el enlazado. Algunos valores comunes son:
  * `noopener`: Mejora la seguridad al abrir enlaces en nuevas pestañas.
  * `nofollow`: Indica a los motores de búsqueda que no sigan el enlace.


### Elementos de Línea y de bloque

En HTML, los elementos se clasifican principalmente en dos tipos: **elementos de bloque** y **elementos de línea**. Esta clasificación determina cómo se comportan visualmente en una página web.

#### Elementos de bloque:

* **Ocupan todo el ancho disponible:** Se extienden a lo largo de toda la línea, ocupando el espacio horizontal máximo.
* **Forzan un salto de línea:** Siempre comienzan en una nueva línea y empujan el contenido que les sigue hacia abajo.
* **Permiten definir ancho y alto:** Puedes controlar sus dimensiones mediante CSS.
* **Ejemplos:** `<p>`, `<h1>` a `<h6>`, `<div>`, `<ul>`, `<ol>`, `<li>`, `<form>`, `<table>`

#### Elementos de línea:

* **Ocupan solo el espacio necesario:** Se ajustan al contenido que contienen, sin forzar saltos de línea.
* **Se alinean uno junto al otro:** Permiten que otros elementos se coloquen en la misma línea.
* **No se puede definir ancho o alto directamente:** Su tamaño se determina por el contenido.
* **Ejemplos:** `<span>`, `<a>`, `<img>`, `<strong>`, `<em>`, `<input>`, `<button>`

#### Aquí tienes una analogía:

Imagina una página web como una hoja de papel. Los elementos de bloque son como párrafos escritos en líneas separadas, mientras que los elementos de línea son como palabras individuales dentro de una oración.

### Diferencias clave:

| Característica  | Elementos de bloque        | Elementos de línea      |
|-----------------|----------------------------|-------------------------|
| Ancho           | Ocupan todo el ancho disponible | Ocupan solo el espacio necesario |
| Salto de línea  | Forzan un salto de línea    | No forzan un salto de línea |
| Dimensiones     | Se puede definir ancho y alto | No se puede definir ancho o alto directamente |



## Clase 4 - 01/10/2024

### Multimedia

*   **`<img>`: El elemento esencial**

    Este es el elemento principal para mostrar imágenes en una página web. Es un elemento vacío, lo que significa que no tiene etiqueta de cierre. Requiere al menos el atributo `src` para funcionar.

    **Atributos clave:**

    *   `src`: Especifica la URL de la imagen.
    *   `alt`: Proporciona una descripción textual de la imagen para usuarios que no pueden verla (esencial para la accesibilidad y SEO).
    *   `width`: Define el ancho de la imagen en píxeles.
    *   `height`: Define el alto de la imagen en píxeles.
    *   `loading="lazy"`: Permite la carga diferida de la imagen, mejorando el rendimiento de la página.


### Audio

*   **`<audio>`**

    *   Etiqueta principal que define el reproductor de audio.
    *   `controls`: Atributo que muestra los controles de reproducción (play, pausa, volumen, etc.).
    *   `<source>`: Permite especificar diferentes fuentes de audio en distintos formatos para asegurar la compatibilidad con varios navegadores.
    *   `src`: Indica la URL del archivo de audio.
    *   `type`: Especifica el tipo MIME del archivo de audio (e.g., `audio/mpeg` para MP3, `audio/ogg` para Ogg).
    *   **Texto alternativo:** Se muestra si el navegador no soporta la etiqueta `<audio>`.

    **Atributos importantes:**

    *   `autoplay`: Inicia la reproducción automáticamente al cargar la página.
    *   `loop`: Repite el audio en bucle.
    *   `muted`: Silencia el audio por defecto.
    *   `preload`: Indica al navegador cómo debe precargar el audio:
        *   `none`: No precargar.
        *   `metadata`: Precargar solo los metadatos (e.g., duración).
        *   `auto`: Precargar el audio completo.


### Iframes

*   **`<iframe>`**

    El elemento `<iframe>` en HTML te permite incrustar otro documento HTML dentro del documento actual. Piensa en él como una ventana que muestra contenido de otra página web dentro de tu página.

    **Atributos:**

    *   `src`: Este atributo es obligatorio y especifica la URL del documento que se va a mostrar en el iframe.

        Ejemplo: `src="https://www.ejemplo.com/pagina.html"`

    *   `width` y `height`: Definen el ancho y alto del iframe en píxeles o porcentaje.

        Ejemplo: `width="500" height="300"`

    *   `title`: Proporciona un título descriptivo para el iframe, que es importante para la accesibilidad.

        Ejemplo: `title="Mapa del sitio"`

    *   `frameborder`: Controla si el iframe tiene un borde. Puede ser "1" (con borde) o "0" (sin borde).

        Ejemplo: `frameborder="0"`

    *   `allowfullscreen`: Permite que el contenido del iframe se muestre en pantalla completa si el contenido lo soporta.

        Ejemplo: `allowfullscreen`

    *   `sandbox`: Habilita un conjunto de restricciones de seguridad para el contenido del iframe. Puedes especificar diferentes valores para controlar permisos como la ejecución de scripts, el acceso al DOM principal, etc.

        Ejemplo: `sandbox="allow-scripts allow-same-origin"`

    *   `loading`: Indica al navegador cómo debe cargar el iframe:

        *   `eager`: Carga el iframe inmediatamente (valor por defecto).
        *   `lazy`: Carga el iframe de forma diferida, cuando el usuario se desplaza cerca de él.


### Tablas

*   Las tablas en HTML se utilizan para organizar datos en filas y columnas. Aunque en el pasado se usaban para maquetar páginas web (algo que ahora se hace con CSS), su función principal es la presentación de información tabular.

    1.  `<table>`: Define la tabla. Todo el contenido de la tabla debe ir dentro de esta etiqueta.

    2.  `<tr>`: Define una fila dentro de la tabla.

    3.  `<td>`: Define una celda de datos dentro de una fila. Aquí es donde va el contenido de la celda (texto, imágenes, etc.).

    4.  `<th>`: Define una celda de encabezado dentro de una fila. Se utiliza para etiquetar las filas o columnas. El texto dentro de `<th>` se muestra en negrita por defecto.

    **Elementos adicionales:**

    *   `<caption>`: Define un título para la tabla. Se coloca justo después de la etiqueta `<table>`.
    *   `<thead>`: Agrupa las filas de encabezado de la tabla.
    *   `<tbody>`: Agrupa las filas de datos de la tabla.
    *   `<tfoot>`: Agrupa las filas de pie de página de la tabla.
    *   `<col>` y `<colgroup>`: Se utilizan para definir propiedades para una o varias columnas.

    **Atributos útiles:**

    *   `colspan`: Atributo de `<td>` o `<th>` que permite que una celda ocupe varias columnas.
    *   `rowspan`: Atributo de `<td>` o `<th>` que permite que una celda ocupe varias filas.
    *   `border`: Atributo de `<table>` que define el grosor del borde de la tabla (en desuso, se recomienda usar CSS).


### Formularios

Los formularios en HTML son esenciales para interactuar con los usuarios, permitiéndoles enviar información a un servidor web. Se utilizan para diversas tareas, como iniciar sesión, enviar comentarios, realizar compras y mucho más.

**Elementos clave de un formulario en HTML:**

1.  **`<form>`:** Define el formulario. Todos los elementos del formulario deben ir dentro de esta etiqueta.

    **Atributos importantes:**

    *   `action`: Especifica la URL del servidor donde se enviarán los datos del formulario.
    *   `method`: Define el método HTTP para enviar los datos (`get` o `post`).
        *   `get`: Los datos se envían en la URL.
        *   `post`: Los datos se envían en el cuerpo de la solicitud HTTP.

2.  **Elementos de entrada:**

    *   **`<input>`:** Permite crear diferentes tipos de campos de entrada:
        *   `text`: Campo de texto de una sola línea.
        *   `password`: Campo de contraseña que oculta los caracteres.
        *   `email`: Campo para direcciones de correo electrónico.
        *   `number`: Campo para números.
        *   `date`: Campo para fechas.
        *   `checkbox`: Casilla de verificación.
        *   `radio`: Botón de opción.
        *   `submit`: Botón para enviar el formulario.
        *   `reset`: Botón para reiniciar los campos del formulario.
        *   `file`: Campo para seleccionar archivos.
        *   ...y muchos más.

    *   **`<textarea>`:** Crea un campo de texto de varias líneas.

    *   **`<select>`:** Crea una lista desplegable.

    *   **`<option>`:** Define las opciones dentro de una lista desplegable (`<select>`).

    *   **`<button>`:** Crea un botón. Puedes especificar el tipo de botón con el atributo `type` (submit, reset, button).

3.  **Etiquetas:**

    *   **`<label>`:** Crea una etiqueta para un elemento de entrada. Es importante asociar la etiqueta con el elemento de entrada mediante el atributo `for` en la etiqueta y el atributo `id` en el elemento de entrada.


## Clase 5 - 08/10/2024

CSS (Cascading Style Sheets) es un lenguaje utilizado para describir la presentación de un documento HTML. Mientras que HTML estructura el contenido de una página web, CSS controla cómo ese contenido se presenta visualmente al usuario, permitiendo separar el contenido de su presentación.

### Sintaxis de CSS
CSS está compuesto por **reglas** que indican qué estilo aplicar a qué elementos de HTML. Cada regla CSS tiene dos partes principales:
- **Selector**: Indica a qué elementos HTML se aplicarán los estilos.
- **Declaración**: Define el conjunto de estilos que se aplicarán, que a su vez se dividen en propiedades y valores.

Ejemplo de una regla CSS:

```css
p {
  color: blue;
  font-size: 16px;
}
```

En este caso, `p` es el selector que aplica estilos a todos los elementos `<p>` de la página. La declaración dentro de las llaves `{}` establece que el texto debe ser azul (`color: blue;`) y el tamaño de la fuente será de 16 píxeles (`font-size: 16px;`).

### Selectores CSS
Los selectores son esenciales en CSS, ya que determinan qué elementos del documento se estilizan. Algunos de los selectores más comunes son:

- **Selector de etiqueta**: Se refiere a una etiqueta HTML específica (por ejemplo, `p`, `h1`, `div`).
  ```css
  h1 {
    color: red;
  }
  ```

- **Selector de clase**: Aplica estilos a elementos que tienen un atributo `class`. Utiliza un punto `.` antes del nombre de la clase.
  ```css
  .my-class {
    margin: 10px;
  }
  ```

- **Selector de ID**: Aplica estilos a un elemento con un atributo `id`. Usa una almohadilla `#` antes del nombre del ID.
  ```css
  #my-id {
    background-color: yellow;
  }
  ```

### Propiedades CSS comunes

Algunas propiedades de estilo comunes que puedes utilizar en CSS incluyen:

- **Color**: Define el color del texto.
  ```css
  color: red;
  ```

- **Background**: Controla el color o imagen de fondo de un elemento.
  ```css
  background-color: lightgray;
  ```

- **Margin y Padding**: Margin controla el espacio fuera del borde de un elemento, mientras que Padding controla el espacio dentro del borde, alrededor del contenido.
  ```css
  margin: 20px;
  padding: 10px;
  ```

- **Font**: Establece el tamaño, tipo y estilo de la fuente.
  ```css
  font-family: Arial, sans-serif;
  font-size: 18px;
  ```

### Cómo incluir CSS en HTML

Hay varias formas de agregar CSS a un documento HTML:

1. **CSS en línea**: Se aplica directamente dentro de un elemento HTML utilizando el atributo `style`.
   ```html
   <p style="color: blue;">Este es un texto en azul.</p>
   ```

2. **Estilos internos**: Se incluyen dentro de la etiqueta `<style>` en la sección `<head>` del documento HTML.
   ```html
   <style>
     p {
       color: blue;
     }
   </style>
   ```

3. **Estilos externos**: Se incluyen en un archivo separado con extensión `.css` y se vinculan en el HTML con la etiqueta `<link>`.
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

### Cascada y Especificidad

CSS utiliza un modelo en cascada para determinar qué reglas aplicar cuando hay múltiples estilos que coinciden con un mismo elemento. Los navegadores asignan prioridad a las reglas CSS en función de la **especificidad** de los selectores y la **proximidad** de la declaración.

Por ejemplo:
- Los estilos en línea tienen mayor prioridad que los estilos internos o externos.
- Un `ID` tiene más peso que una `clase` o una etiqueta HTML.

Aquí tienes una lista de propiedades CSS comunes junto con una breve descripción de su uso:


### Algunas propiedades de CSS

1. **color**  
   Define el color del texto dentro de un elemento.
   ```css
   color: red;
   ```

2. **background-color**  
   Establece el color de fondo de un elemento.
   ```css
   background-color: lightblue;
   ```

3. **font-size**  
   Controla el tamaño del texto.
   ```css
   font-size: 18px;
   ```

4. **font-family**  
   Define la fuente del texto, permitiendo elegir entre múltiples tipos de letra.
   ```css
   font-family: Arial, sans-serif;
   ```

5. **font-weight**  
   Especifica el grosor de la fuente (por ejemplo, normal, bold).
   ```css
   font-weight: bold;
   ```

6. **text-align**  
   Controla la alineación del texto (izquierda, derecha, centro o justificado).
   ```css
   text-align: center;
   ```

7. **margin**  
   Define el espacio exterior alrededor de un elemento, creando espacio entre el borde del elemento y otros elementos.
   ```css
   margin: 10px;
   ```

8. **padding**  
   Define el espacio interior de un elemento, entre el contenido y su borde.
   ```css
   padding: 20px;
   ```

9. **border**  
   Establece el borde de un elemento, incluyendo su grosor, estilo y color.
   ```css
   border: 2px solid black;
   ```

10. **width**  
    Define el ancho de un elemento.
    ```css
    width: 300px;
    ```

11. **height**  
    Controla la altura de un elemento.
    ```css
    height: 200px;
    ```

12. **display**  
    Define cómo se debe mostrar un elemento (por ejemplo, block, inline, none).
    ```css
    display: block;
    ```

13. **position**  
    Controla la posición de un elemento en la página (relative, absolute, fixed, sticky).
    ```css
    position: absolute;
    ```

14. **top, right, bottom, left**  
    Junto con `position`, define la ubicación de un elemento en relación a su contenedor.
    ```css
    top: 50px;
    left: 20px;
    ```

15. **overflow**  
    Define cómo se maneja el contenido desbordado que excede el área del contenedor (visible, hidden, scroll, auto).
    ```css
    overflow: hidden;
    ```

16. **z-index**  
    Controla la capa de apilamiento de un elemento en la pantalla, permitiendo que algunos elementos se superpongan a otros.
    ```css
    z-index: 10;
    ```

17. **opacity**  
    Establece el nivel de transparencia de un elemento, con valores de 0 (completamente transparente) a 1 (completamente opaco).
    ```css
    opacity: 0.8;
    ```

18. **cursor**  
    Cambia el tipo de cursor cuando el usuario pasa el mouse sobre un elemento.
    ```css
    cursor: pointer;
    ```

19. **box-shadow**  
    Aplica una sombra a un elemento.
    ```css
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
    ```

20. **transition**  
    Define las transiciones entre los cambios de estilo de un elemento.
    ```css
    transition: all 0.3s ease-in-out;
    ```

21. **transform**  
    Aplica transformaciones como rotación, escalado o traslación a un elemento.
    ```css
    transform: rotate(45deg);
    ```

22. **flex**  
    Permite la creación de diseños flexibles mediante la disposición de elementos hijos dentro de un contenedor.
    ```css
    display: flex;
    ```

23. **grid-template-columns**  
    Define el número y el tamaño de las columnas en un contenedor de cuadrícula (Grid).
    ```css
    grid-template-columns: 1fr 2fr;
    ```

24. **justify-content**  
    Alinea los elementos hijos horizontalmente en un contenedor flex o grid.
    ```css
    justify-content: space-between;
    ```

25. **align-items**  
    Alinea los elementos hijos verticalmente en un contenedor flex o grid.
    ```css
    align-items: center;
    ```
## Clase 6 - 22/10/2024

### Unidades de medidas: Absolutas

Las **unidades absolutas** tienen un tamaño fijo e invariable, independientemente del contexto del diseño, como el tamaño de la pantalla o las preferencias del usuario. Son útiles cuando se desea un control exacto sobre las dimensiones, pero pueden ser menos flexibles en diseños responsivos.

#### Principales Unidades Absolutas:
- **`px` (píxeles)**: Un píxel es el tamaño más pequeño de una pantalla. Es la unidad más común para tamaños fijos.
- **`cm` (centímetros)**: Unidad basada en el sistema métrico.
- **`mm` (milímetros)**: También basada en el sistema métrico.
- **`in` (pulgadas)**: 1 pulgada equivale a 96 píxeles.
- **`pt` (puntos)**: Principalmente usado en impresión. 1 punto es 1/72 de una pulgada.
- **`pc` (picas)**: 1 pica equivale a 12 puntos.

> Estas unidades pueden ser útiles en contextos como impresoras, pero en pantallas, **`px`** es la más usada de las absolutas.

### Unidades de medidas: Relativas
Las **unidades relativas** son aquellas cuyo tamaño depende de algún otro valor, como el tamaño del elemento contenedor, la pantalla o las preferencias del usuario. Son más flexibles y recomendadas para diseño web responsivo, ya que permiten que el contenido se adapte a diferentes tamaños de pantalla o configuraciones.

#### Principales Unidades Relativas:
- **`em`**: Relativa al tamaño de la fuente del elemento padre. Si el elemento padre tiene un tamaño de fuente de 16px, 1 `em` será igual a 16px.
- **`rem` (root em)**: Similar a `em`, pero relativa al tamaño de la fuente raíz del documento (`html`). Generalmente, el tamaño de fuente base es de 16px, por lo que 1 `rem` = 16px a menos que se haya modificado.
- **`%` (porcentaje)**: Relativa al tamaño del elemento padre. Por ejemplo, si un ancho de un elemento se define como `50%`, será la mitad del tamaño de su contenedor.
- **`vw` (viewport width)**: Relativa al ancho de la ventana del navegador. 1 `vw` es igual al 1% del ancho de la ventana.
- **`vh` (viewport height)**: Relativa a la altura de la ventana del navegador. 1 `vh` es igual al 1% de la altura de la ventana.
- **`vmin`** y **`vmax`**: Relativas al menor o mayor valor entre `vw` y `vh`. Es decir, `vmin` toma el valor más pequeño entre el ancho y la altura de la ventana, mientras que `vmax` toma el mayor.

### Comparativa Absolutas vs Relativas
- **Unidades absolutas** ofrecen control preciso, pero no se adaptan bien a cambios en pantallas o configuraciones de usuario.
- **Unidades relativas** son más flexibles, facilitando el diseño responsivo, ya que permiten que el tamaño del contenido cambie en función del dispositivo o de otros factores.

### Uso de colores en css

En CSS, los **colores** son fundamentales para diseñar y dar estilo a los elementos HTML. Puedes definir colores de varias maneras, y se usan para propiedades como `color` (texto), `background-color` (fondo), `border-color`, entre otras.

#### Formas de Especificar Colores en CSS:

1. **Nombres de colores**:
   CSS define una lista de nombres de colores predefinidos que puedes usar directamente.
   - Ejemplo:
     ```css
     color: red; /* Nombre de color */
     background-color: blue; /* Nombre de color */
     ```
   Algunos nombres comunes son: `red`, `blue`, `green`, `yellow`, `black`, `white`, `gray`, etc.

2. **Colores Hexadecimales**:
   Es una de las formas más usadas para definir colores en CSS. Los colores hexadecimales son representados con un `#` seguido de 6 dígitos hexadecimales, donde cada par representa el valor de rojo (RR), verde (GG), y azul (BB) en el formato `#RRGGBB`.
   - Ejemplo:
     ```css
     color: #ff0000; /* Rojo puro */
     background-color: #00ff00; /* Verde puro */
     ```
   Puedes también usar versiones cortas de los colores hexadecimales, como `#f00` para `#ff0000`.

3. **RGB (Red, Green, Blue)**:
   Otra forma común de definir colores es usando la función **`rgb()`**, donde los valores de **rojo (R)**, **verde (G)** y **azul (B)** van de 0 a 255.
   - Ejemplo:
     ```css
     color: rgb(255, 0, 0); /* Rojo puro */
     background-color: rgb(0, 255, 0); /* Verde puro */
     ```

4. **RGBA (RGB con Opacidad)**:
   Similar a `rgb()`, pero incluye un cuarto valor que representa la **opacidad (alpha)**. El valor de alpha va de 0 (completamente transparente) a 1 (completamente opaco).
   - Ejemplo:
     ```css
     color: rgba(255, 0, 0, 0.5); /* Rojo al 50% de opacidad */
     background-color: rgba(0, 0, 255, 0.7); /* Azul al 70% de opacidad */
     ```

5. **HSL (Hue, Saturation, Lightness)**:
   La función **`hsl()`** define colores utilizando tres parámetros:
   - **Hue** (matiz): Un valor entre 0 y 360 que representa el color en el espectro (0 = rojo, 120 = verde, 240 = azul).
   - **Saturation** (saturación): Un porcentaje que determina la intensidad del color. 100% es el color completamente saturado, 0% es gris.
   - **Lightness** (luminosidad): Otro porcentaje que determina la claridad o oscuridad del color. 0% es negro, 100% es blanco.
   - Ejemplo:
     ```css
     color: hsl(0, 100%, 50%); /* Rojo saturado */
     background-color: hsl(120, 100%, 50%); /* Verde puro */
     ```

6. **HSLA (HSL con Opacidad)**:
   Similar a `hsl()`, pero con un cuarto parámetro para la opacidad.
   - Ejemplo:
     ```css
     color: hsla(0, 100%, 50%, 0.5); /* Rojo saturado al 50% de opacidad */
     background-color: hsla(240, 100%, 50%, 0.3); /* Azul saturado al 30% de opacidad */
     ```

#### Ejemplo de uso de colores en CSS:

```css
body {
    background-color: #f4f4f4; /* Color de fondo usando hexadecimal */
    color: rgb(33, 33, 33); /* Color del texto usando RGB */
}

h1 {
    color: hsl(240, 100%, 50%); /* Azul saturado con HSL */
}

p {
    background-color: rgba(255, 165, 0, 0.7); /* Naranja translúcido con RGBA */
    color: white; /* Texto blanco */
}
```

### Consideraciones:
- **Contraste**: Asegúrate de usar combinaciones de colores con suficiente contraste, especialmente para el texto sobre fondos, para garantizar la accesibilidad.
- **Transparencia**: Usar **rgba** o **hsla** para colores con transparencia permite superponer elementos de manera más creativa.
- **Variables CSS**: Es posible definir colores como variables para mantener un diseño consistente.


### Uso de background:

En CSS, la propiedad `background` se utiliza para aplicar fondos a los elementos HTML. Los fondos pueden ser colores, imágenes o incluso una combinación de ambos. CSS proporciona varias propiedades relacionadas para controlar los aspectos de los fondos, como su repetición, tamaño, posición, etc.

#### Principales Propiedades de Fondo en CSS:

1. **`background-color`**:
   Esta propiedad define el **color** de fondo de un elemento.
   - Ejemplo:
     ```css
     div {
         background-color: #f0f0f0; /* Fondo gris claro */
     }
     ```

2. **`background-image`**:
   Esta propiedad permite establecer una **imagen** como fondo del elemento.
   - Ejemplo:
     ```css
     body {
         background-image: url('imagen-de-fondo.jpg');
     }
     ```

3. **`background-repeat`**:
   Controla cómo se repite la imagen de fondo.
   - Valores:
     - `repeat`: Repite la imagen en ambas direcciones (valor por defecto).
     - `no-repeat`: No repite la imagen.
     - `repeat-x`: Repite la imagen solo horizontalmente.
     - `repeat-y`: Repite la imagen solo verticalmente.
   - Ejemplo:
     ```css
     div {
         background-image: url('patron.png');
         background-repeat: repeat-x; /* Repite solo en el eje horizontal */
     }
     ```

4. **`background-position`**:
   Establece la posición inicial de la imagen de fondo. Los valores más comunes son:
   - Palabras clave como `left`, `right`, `top`, `bottom`, `center`.
   - Coordenadas como `20px 40px` o porcentajes `50% 50%`.
   - Ejemplo:
     ```css
     div {
         background-image: url('imagen.jpg');
         background-position: center; /* Imagen centrada */
     }
     ```

5. **`background-size`**:
   Define el tamaño de la imagen de fondo.
   - Valores:
     - `auto`: Mantiene el tamaño original de la imagen (valor por defecto).
     - `cover`: Escala la imagen para cubrir todo el área del elemento, puede recortar la imagen si no encaja perfectamente.
     - `contain`: Escala la imagen para que sea completamente visible dentro del elemento, sin recortes.
     - Especificaciones de tamaño como `100px 200px` o porcentajes como `100%`.
   - Ejemplo:
     ```css
     div {
         background-image: url('imagen.jpg');
         background-size: cover; /* La imagen cubrirá toda la caja */
     }
     ```

6. **`background-attachment`**:
   Controla si la imagen de fondo se desplaza junto con el contenido o se mantiene fija.
   - Valores:
     - `scroll`: La imagen se desplaza con el contenido (valor por defecto).
     - `fixed`: La imagen de fondo permanece fija cuando se desplaza la página.
     - `local`: La imagen se desplaza dentro del contenedor si tiene scroll.
   - Ejemplo:
     ```css
     body {
         background-image: url('imagen-de-fondo.jpg');
         background-attachment: fixed; /* Fondo fijo al hacer scroll */
     }
     ```

7. **`background-clip`**:
   Define hasta dónde se extiende el fondo dentro del contenedor.
   - Valores:
     - `border-box`: El fondo se extiende hasta el borde del contenedor (valor por defecto).
     - `padding-box`: El fondo se extiende solo hasta el borde del área de padding.
     - `content-box`: El fondo se extiende solo dentro del área de contenido.
   - Ejemplo:
     ```css
     div {
         background-color: yellow;
         background-clip: content-box; /* El color de fondo solo está en el contenido */
     }
     ```

8. **`background-origin`**:
   Determina el área de posicionamiento del fondo.
   - Valores:
     - `border-box`: Posiciona el fondo desde el borde.
     - `padding-box`: Posiciona desde el padding.
     - `content-box`: Posiciona desde el contenido.
   - Ejemplo:
     ```css
     div {
         background-image: url('imagen.jpg');
         background-origin: padding-box; /* La imagen comienza en el área de padding */
     }
     ```

#### Uso de la Propiedad `background` (shorthand):
Es posible definir todos los aspectos del fondo en una sola propiedad utilizando la propiedad abreviada `background`.

**Ejemplo completo**:
```css
div {
    background: url('imagen.jpg') no-repeat center/cover fixed #333;
    /* Imagen centrada, no repetida, tamaño cubre todo el contenedor, fondo fijo y color de respaldo gris oscuro */
}
```

#### Ejemplo Completo con Colores e Imágenes de Fondo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Fondos en CSS</title>
    <style>
        body {
            background-color: #e0e0e0; /* Fondo de color gris claro */
            font-family: Arial, sans-serif;
        }

        .fondo-imagen {
            background-image: url('https://via.placeholder.com/800');
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            background-attachment: fixed;
            height: 400px;
            margin: 20px 0;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .fondo-color {
            background-color: #3498db; /* Color de fondo azul */
            padding: 50px;
            text-align: center;
            color: white;
        }
    </style>
</head>
<body>

    <section class="fondo-color">
        <h1>Sección con Fondo de Color</h1>
        <p>Esta sección tiene un fondo de color sólido.</p>
    </section>

    <section class="fondo-imagen">
        <h1>Sección con Fondo de Imagen</h1>
    </section>

</body>
</html>
```

### Uso de fuentes y tipografías

En CSS, las **fuentes** y **tipografías** son esenciales para el diseño y la legibilidad del contenido en una página web. CSS ofrece varias propiedades para controlar el estilo de las fuentes, como el tipo de letra, el tamaño, el grosor, la altura de línea y más. A continuación te explico las propiedades principales relacionadas con las fuentes y la tipografía:

### Propiedades Básicas de Fuentes en CSS:

1. **`font-family`**:
   - Define la **familia tipográfica** que se usará en un texto.
   - Se puede especificar una lista de familias de fuentes de reserva en caso de que la primera no esté disponible.
   - Es recomendable incluir tanto **fuentes personalizadas** como una **fuente genérica** (serif, sans-serif, monospace, etc.).
   - Ejemplo:
     ```css
     body {
         font-family: 'Arial', 'Helvetica', sans-serif;
     }
     ```
   En este ejemplo, se intentará usar primero `Arial`, luego `Helvetica`, y si no están disponibles, se usará cualquier fuente **sans-serif**.

2. **`font-size`**:
   - Define el **tamaño** del texto.
   - Puede expresarse en varias unidades:
     - **Absolutas**: `px` (píxeles), `pt` (puntos).
     - **Relativas**: `em`, `rem`, `%`, `vw` (anchura del viewport), etc.
   - Ejemplo:
     ```css
     h1 {
         font-size: 2em; /* Tamaño del texto es 2 veces el tamaño de la fuente del contenedor */
     }
     ```

3. **`font-weight`**:
   - Controla el **grosor** de la fuente.
   - Valores comunes:
     - **Normal**: `normal` (400).
     - **Negrita**: `bold` (700).
     - Números de 100 a 900 (donde 400 es el normal y 700 es negrita).
   - Ejemplo:
     ```css
     p {
         font-weight: bold; /* Negrita */
     }
     ```

4. **`font-style`**:
   - Controla el **estilo** de la fuente, como **cursiva** o normal.
   - Valores:
     - `normal`: Texto sin cursiva.
     - `italic`: Texto en cursiva.
     - `oblique`: Texto inclinado.
   - Ejemplo:
     ```css
     em {
         font-style: italic; /* Texto en cursiva */
     }
     ```

5. **`line-height`**:
   - Establece la **altura de línea**, es decir, el espacio entre líneas de texto.
   - Puede ser un número (que multiplica el tamaño de la fuente), un valor en unidades, o un porcentaje.
   - Ejemplo:
     ```css
     p {
         line-height: 1.5; /* 1.5 veces la altura de la fuente */
     }
     ```

6. **`text-align`**:
   - Controla la **alineación del texto** dentro de su contenedor.
   - Valores comunes:
     - `left`: Alinea a la izquierda (valor por defecto en la mayoría de los navegadores).
     - `center`: Centra el texto.
     - `right`: Alinea a la derecha.
     - `justify`: Justifica el texto (alineado a ambos lados).
   - Ejemplo:
     ```css
     h1 {
         text-align: center; /* Texto centrado */
     }
     ```

7. **`text-transform`**:
   - Controla la **transformación del texto**, como convertir todo a mayúsculas, minúsculas o la capitalización de la primera letra de cada palabra.
   - Valores:
     - `uppercase`: Convierte todo el texto a mayúsculas.
     - `lowercase`: Convierte todo el texto a minúsculas.
     - `capitalize`: Pone en mayúscula la primera letra de cada palabra.
   - Ejemplo:
     ```css
     h1 {
         text-transform: uppercase; /* Todo en mayúsculas */
     }
     ```

8. **`letter-spacing`**:
   - Ajusta el **espaciado entre letras**.
   - Se puede aumentar o disminuir usando valores positivos o negativos.
   - Ejemplo:
     ```css
     h1 {
         letter-spacing: 2px; /* Aumenta el espacio entre letras */
     }
     ```

9. **`text-decoration`**:
   - Define decoraciones como **subrayado**, tachado o sobrelineado.
   - Valores comunes:
     - `underline`: Subraya el texto.
     - `line-through`: Tacha el texto.
     - `none`: Sin decoración (para eliminar subrayados en enlaces, por ejemplo).
   - Ejemplo:
     ```css
     a {
         text-decoration: none; /* Sin subrayado en enlaces */
     }
     ```

### Fuentes Web y Google Fonts:
Para utilizar fuentes que no están instaladas en el sistema del usuario, es común utilizar **Google Fonts** o **@font-face** para cargar fuentes externas.

#### 1. **Usar Google Fonts**:
   - Google Fonts es un servicio que proporciona una amplia variedad de fuentes para usar en la web.
   - Para usar una fuente, puedes importar una fuente de Google en tu HTML de la siguiente manera:
   - Ejemplo:
     ```html
     <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
     ```
   - Luego, en el CSS:
     ```css
     body {
         font-family: 'Roboto', sans-serif;
     }
     ```

#### 2. **@font-face** (Cargar Fuentes Personalizadas):
   - Con `@font-face`, puedes cargar una fuente personalizada desde tu servidor.
   - Ejemplo:
     ```css
     @font-face {
         font-family: 'MiFuente';
         src: url('mifuente.woff2') format('woff2'),
              url('mifuente.woff') format('woff');
     }

     body {
         font-family: 'MiFuente', sans-serif;
     }
     ```

### Ejemplo Completo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Fuentes y Tipografías</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            font-size: 16px;
            line-height: 1.6;
            text-align: justify;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 700;
            text-align: center;
            text-transform: uppercase;
            margin-bottom: 20px;
        }

        p {
            font-size: 1rem;
            line-height: 1.5;
        }

        em {
            font-style: italic;
        }

        strong {
            font-weight: bold;
        }

        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Ejemplo de Tipografías</h1>
    <p>Este es un ejemplo del uso de la tipografía <strong>Roboto</strong> obtenida de Google Fonts. Puedes aplicar diferentes <em>estilos</em> y tamaños de fuente para mejorar la legibilidad y estética del contenido.</p>
    <p>Visita <a href="https://fonts.google.com/" target="_blank">Google Fonts</a> para encontrar más opciones de fuentes.</p>
</body>
</html>
```




