# Trabajo Practico Nº1 Programación Visual Grupo 7

**Integrantes:**
- 1- Miranda Facundo David / MirandaFD0
- 2- Leandro Abel Ezequiel Camacho/leandrocamacho02
- 3- Porco Lucas Ricardo / lucas777porco-ai
- 4- Murillo Sanjines Tania / edutania
- 5- Robles Joaquín Raúl / JoaquinRaulRobles
## Breve Descripción del Trabajo

### Parte 1: Estructura con HTML
En esta primera parte, se enfocó en diseñar y maquetar la estructura base de nuestra plataforma de **Gestión de Proyectos Educativos**. El trabajo consistió puramente en el uso de HTML, dejando de lado cualquier estilo visual.

**Lo que se implementó:**

* **Estructura Semántica:** Se organizó cada página utilizando etiquetas de bloque como `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>` para que el sitio sea accesible y esté bien dividido.
* **Navegación Funcional:** Armado de un menú global con etiquetas `<a>` que vincula correctamente los cuatro archivos principales: `index.html`, `proyectos.html`, `detalle.html` y `perfil.html`.
* **Organización de Información:** Uso de listas (`<ul>` y `<ol>`) para mostrar desde las estadísticas del dashboard hasta los recursos de los proyectos.
* **Implementación de tablas:** Uso de la etiqueta `<table>` para detallar los roles del equipo y las métricas de seguimiento.
* **Maquetado de un formulario:** Uso de la etiqueta `<form>` con selectores para la futura funcionalidad de filtrado en el explorador de proyectos.

---

### Parte 2: Aplicación de Estilos con CSS
En esta segunda etapa, el enfoque pasó de la estructura a la presentación visual, aplicando hojas de estilo a los documentos HTML previamente construidos. 

**Lo que se implementó en esta parte:**

* **Organización y Vinculación:** Se creó una carpeta `css` en el directorio raíz para alojar el archivo `styles.css`. Este archivo externo se asoció a todos los documentos HTML utilizando la etiqueta `<link>` dentro de la sección `<head>`.
* **Estilo Externo:** Se aplicaron los diseños empleando exclusivamente un archivo CSS alojado en la carpeta (css) externo a los documentos HTML, manteniendo así una clara separación entre la estructura y la presentación visual.
* **Sistemas de Maquetación Avanzados:** Se implementó **CSS Grid** para estructurar el diseño general de las páginas y **Flexbox** para manejar la alineación de los componentes internos (como `nav`, `cards` y `forms`).
* **Consistencia Visual:** Se aplicaron variables CSS dentro de `:root` para centralizar y utilizar de manera uniforme los colores y las tipografías en toda la plataforma.
* **Interactividad:** Se definieron los estados `:hover`, `:focus` y `:active` dependiendo la cantidad de elementos interactivos, mejorando la experiencia del usuario al navegar.
* **Selectores:** Se implementaron reglas de estilo haciendo uso de selectores CSS mediante clases (`class`) e identificadores (`id`) para apuntar a los elementos HTML correspondientes.