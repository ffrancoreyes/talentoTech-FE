# talentoTech-FE

## Clase 1 - 10/09/2024

En la primer clase de introducción se vieron cosas como instalar VSCODE - Extensiónes de VSCODE para el desarrollo web y estructura básica de una página (HTML).

## Clase 2 - 17/09/2024

los archivos HTML, son documentos de maquetación para páginas web. las mismas usan etiquetas o tags. hay muchos tipos de etiquetas.

Algunos ejemplos: "h1" para títulos o "p" para párrafos

## Clase 3 - 24/09/2024
- Listas ordenadas y desordenadas
- Enlaces: Relativos (Que está en los directorios en los que se encuentra mi sitio) y absolutas (se encuentra en lugares externos a nuestro directorio)
- Elementos de línea y bloque: los de línea se sobreponen al lado del otro elemento de línea: ejemplo
ElementoDeLinea1 ElementoDeLínea2

Los elementos de bloque ocupan el 100vw
ElementoDeBloque1 <br>
ElementoDeBloque2

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