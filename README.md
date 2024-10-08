# talentoTech-FE
Hola, Soy ***Fabrizzio Franco Reyes***, creador de este repositorio donde se fueron subiendo todos los contenidos vistos durante la cursada del curso de desarollo web FrontEnd de Talento Tech.

## Información Importante:
- En caso de usar de forma didáctica este repositorio, dar créditos.
### En caso de querer realizar un cambio al contenido
- Envía la solicitud de Issue a través de Github
o
- Contáctame
    * Mail: ffrancoreyes@frba.utn.edu.ar
    * Teléfono: +541151489765


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
