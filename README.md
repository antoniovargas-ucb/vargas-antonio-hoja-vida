# Hoja de Vida Web - HTML5 Nativo

## Información General

- **Nombre del estudiante:** Ing. Antonio Alexander Vargas Sosa
- **Carrera:** Ingeniería de Sistemas e Ingeniería Mecatrónica
- **Materia:** Tecnologías Web I [SIS-214]
- **Institución:** Universidad Católica Boliviana "San Pablo" (UCB)

---

## 1. Descripción de la Hoja de Vida

Página web profesional tipo *showcase* desarrollada para presentar la información académica, perfil laboral, experiencia profesional, proyectos destacados, servicios de docencia y habilidades técnicas del **Ing. Antonio Alexander Vargas Sosa**. 

El proyecto ha sido elaborado utilizando **exclusivamente HTML5 nativo**, sin hacer uso de frameworks CSS (como Bootstrap o Tailwind) ni librerías externas de JavaScript. Su diseño demuestra el potencial semántico, accesible y funcional de los estándares nativos W3C, garantizando una excelente estructura, navegación por teclado, interactividad nativa y validaciones completas.

---

## 2. Etiquetas HTML5 Utilizadas

El proyecto incluye un uso riguroso y semántico de los siguientes grupos de etiquetas HTML5:

### Estructura Global y Secciones Semánticas
- `<header>`: Encabezado principal del sitio con foto de perfil, título, resumen y enlaces.
- `<nav>`: Menú de navegación principal con enlaces de salto interno a cada sección.
- `<aside>`: Sección lateral complementaria con datos rápidos de disponibilidad.
- `<main>`: Contenedor principal del documento (`id="contenido-principal"`).
- `<section>`: Secciones temáticas principales (Perfil, Formación, Experiencia, Habilidades, etc.).
- `<article>`: Bloques independientes de contenido dentro de las secciones.
- `<footer>`: Pie de página con derechos reservados, nota de accesibilidad y enlace directo a descarga del CV.

### Etiquetas de Interactividad y Medición Nativa
- `<picture>` y `<source>`: Carga adaptativa de imágenes responsive según el tamaño de pantalla.
- `<details>` y `<summary>`: Bloques colapsables interactivos para desplegar información adicional sin recargar.
- `<dialog>`: Ventana emergente (modal) nativa HTML5 para la ficha rápida de contacto.
- `<progress>`: Barra de progreso de avance porcentual de titulación y metas.
- `<meter>`: Medidores de nivel de dominio técnico e idiomas con atributos `min`, `max`, `low`, `high`, `optimum` y `value`.

### Semántica de Texto
- `<h1>`, `<h2>`, `<h3>`: Jerarquía estricta de encabezados.
- `<p>`: Párrafos de texto explicativo.
- `<strong>`: Énfasis fuerte de importancia.
- `<em>`: Énfasis conceptual.
- `<mark>`: Texto resaltado relevante.
- `<small>`: Texto secundario y aclaratorio.
- `<time datetime="...">`: Fechas y periodos temporales estructurados.
- `<address>`: Datos de contacto profesional.
- `<blockquote>` y `<cite>`: Citas profesionales destacadas.
- `<abbr title="...">`: Abreviaturas explicadas para tecnologías de asistencia.
- `<code>` y `<kbd>`: Fragmentos de código e instrucciones de teclado.
- `<dl>`, `<dt>`, `<dd>`: Listas de descripción para glosario y pares clave-valor.

### Listas
- `<ul>` y `<li>`: Listas no ordenadas (habilidades, fortalezas, herramientas).
- `<ol>` y `<li>`: Listas ordenadas secuenciales (metodología de trabajo).
- `<dl>`, `<dt>`, `<dd>`: Listas de definición.

### Tablas Semánticas
- `<table>`: Estructura completa de datos organizados.
- `<caption>`: Título descriptivo de la tabla.
- `<thead>`: Encabezado de la tabla.
- `<tbody>`: Cuerpo principal de datos.
- `<tfoot>`: Pie de la tabla para notas explicativas o totales.
- `<tr>`: Filas de la tabla.
- `<th>`: Celdas de encabezado con atributos `scope="col"` y `scope="row"`.
- `<td>`: Celdas de contenido de datos.

### Multimedia Nativa
- `<figure>`: Contenedor semántico para elementos multimedia.
- `<figcaption>`: Descripción textual acompañante.
- `<img>`: Imágenes con atributos `alt`, `width`, `height` y `loading="lazy"`.
- `<audio controls>`: Reproductor nativo de audio con elementos `<source>` y `<track>`.
- `<video controls>`: Reproductor nativo de video con elementos `<source>` y `<track>`.

### Formularios y Validación Nativa
- `<form>`: Formulario de contacto con método `post`.
- `<fieldset>` y `<legend>`: Agrupación temática de campos de formulario.
- `<label for="...">`: Etiquetas vinculadas explícitamente por `id`.
- `<input>`: Controles nativos (`text`, `email`, `tel`, `date`, `range`, `checkbox`).
- `<datalist>`: Sugerencias nativas de autocompletado para ciudad y materia de interés.
- `<select>`, `<optgroup>`, `<option>`: Menú desplegable organizado por grupos de opciones.
- `<textarea>`: Campo de entrada de mensaje multilínea.
- `<button type="submit">`, `<button type="reset">`, `<button type="button">`: Botones nativos.
- **Validaciones nativas:** Atributos `required`, `minlength`, `maxlength`, `pattern`, `placeholder`, `aria-describedby`, `autocomplete`.

---

## 3. Elementos de Accesibilidad Implementados (A11y)

- **Atributo de idioma:** Configurado `<html lang="es">` en la raíz del documento.
- **Enlace de salto A11y:** Enlace *"Saltar al contenido principal"* al inicio del `<body>` que redirige a `<main id="contenido-principal">`.
- **Textos alternativos:** Atributos `alt` descriptivos en todas las imágenes y fuentes del elemento `<picture>`.
- **Asociación explícita en formularios:** Cada campo cuenta con su etiqueta `<label for="...">` pareada con el `id` respectivo.
- **Atributos ARIA:** Implementación de `aria-describedby` para ayudas textuales (`<small>`), `aria-labelledby` para encabezados de sección y `aria-label` en la navegación.
- **Ventana modal accesible:** Modal `<dialog>` configurado con `aria-labelledby` y `aria-describedby` con botón nativo de cierre `<form method="dialog">`.
- **Navegación secuencial por teclado:** Estructura ordenada navegable limpiamente mediante la tecla `Tab`.
- **Encabezados de tablas accesibles:** Uso explícito de `scope="col"` y `scope="row"` para lectura de datos mediante lectores de pantalla.

---

## 4. Instrucciones para Visualizar el Proyecto

1. Clonas o descargas el repositorio/carpeta del proyecto `web00` en tu equipo local.
2. Abres la carpeta del proyecto.
3. Haces doble clic sobre el archivo `index.html` para abrirlo en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge o Safari).
4. No requiere instalación de paquetes Node.js, compilación ni ejecución de servidor.

---

## 5. Estructura de Archivos del Proyecto

```text
web00/
├── index.html                           # Documento principal HTML5 nativo semántico
├── README.md                            # Documentación técnica explicativa
├── assets/
│   ├── images/
│   │   └── foto1.jpg                    # Fotografía responsive
│   ├── audio/
│   │   ├── audio1.m4a                   # Presentación en audio
│   ├── video/
│   │   ├── video1.mp4                   # Demostración de proyecto en video
│   └── documents/
│       └── CV_Antonio_Vargas.pdf        # Documento CV oficial descargable
├── css/                                 # Directorio reservado para hojas de estilo
└── js/                                  # Directorio reservado para scripts JS
```
