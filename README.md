### **Proyecto de html css**
## **Introduccion**

### Mandato Mejorado

Hola Claudio,

Este proyecto consiste en mejorar los tres mandatos de la tarea anterior. Utilizarás este repositorio para subir tus proyectos, organizados en tres carpetas diferentes: **Proyecto 1**, **Proyecto 2** y **Proyecto Combinado**.

Al inicio del repositorio, encontrarás una guía sobre el **Box Model**, que te servirá de referencia para dar formato y estilo a los elementos de tus proyectos, como ajustar márgenes, relleno (padding), bordes y dimensiones. Además, al final, se incluye una **guía de etiquetas HTML** para que puedas consultar rápidamente la documentación de las etiquetas que utilices.

### En cuanto a **Git**, sigue estas pautas:
1. **Haz un commit por cada cambio significativo**. Algunos ejemplos de cuándo debes hacer un commit:
   - **Añadiste una tabla completa** a tu página, como la tabla de razas de perros o gatos.
   - **Cambiaste la estructura de una página**, como reorganizar secciones o modificar el diseño general.
   - **Agregaste o modificaste un estilo CSS importante**, como ajustar el tamaño de las imágenes o cambiar el espaciado entre los elementos de la tabla.
   - **Subiste nuevas imágenes o modificaste el contenido** de una página de detalles.
   - **Corregiste errores importantes en el código** o cambiaste la lógica de los enlaces entre páginas.

2. **Descripciones claras en los commits**. Cada commit debe describir claramente lo que cambiaste. Ejemplos:
   - "Añadí tabla de razas de perros con enlaces a las páginas de detalles."
   - "Modifiqué la estructura de la página principal para mejorar el diseño."
   - "Agregué imágenes de perros y gatos en la carpeta img y ajusté el tamaño de las imágenes."
   - "Corregí los enlaces para abrir páginas de detalles en una nueva pestaña."

Esto ayudará a llevar un control claro de cada mejora o cambio que realices en los proyectos.

---

### Términos Fundamentales de Git

1. **Repositorio (Repository)**:
   Un repositorio es el lugar donde se almacenan todos los archivos de tu proyecto y el historial de versiones de cada archivo.
   - Ejemplo: "Este repositorio contiene los tres proyectos: Proyecto 1, Proyecto 2 y Proyecto Combinado."

2. **Clone**:
   Comando que copia un repositorio desde GitHub (o cualquier servicio Git remoto) a tu computadora local.
   - Ejemplo: "Para empezar a trabajar en un proyecto que está en GitHub, primero lo clono usando `git clone <URL_del_repositorio>`."

3. **Commit**:
   Un commit es un "snapshot" o captura de los cambios en el proyecto en un momento dado. Incluye un mensaje que describe qué se ha cambiado.
   - Ejemplo: "Después de agregar la tabla de razas de perros, hice un commit con el mensaje: `git commit -m 'Añadí tabla de razas de perros'`."

4. **Stage (Staging Area)**:
   Es el área donde añades los cambios antes de confirmarlos con un commit. Solo los archivos en el área de stage serán incluidos en el siguiente commit.
   - Ejemplo: "Para preparar un archivo para el commit uso `git add archivo.html`. Luego de hacer el commit, esos cambios quedan guardados."

5. **Branch**:
   Un branch es una "rama" del proyecto, donde puedes desarrollar nuevas funcionalidades sin afectar el branch principal (a menudo llamado `main` o `master`).
   - Ejemplo: "Cree una nueva rama `git checkout -b nueva-funcionalidad` para trabajar en un nuevo estilo de la página sin afectar la rama principal."

6. **Merge**:
   Merge se usa para combinar cambios de diferentes ramas. Por ejemplo, puedes trabajar en una nueva funcionalidad en una rama separada y luego combinar esos cambios con la rama principal.
   - Ejemplo: "Cuando terminé de agregar la nueva funcionalidad, hice un merge a la rama principal con `git merge nueva-funcionalidad`."

7. **Pull**:
   Este comando actualiza tu repositorio local con los últimos cambios que hayan sido añadidos al repositorio remoto.
   - Ejemplo: "Para obtener los últimos cambios de mis compañeros de equipo, hago `git pull origin main`."

8. **Push**:
   Push envía tus cambios locales al repositorio remoto, como GitHub.
   - Ejemplo: "Después de hacer commits en mi computadora, subo los cambios a GitHub con `git push origin main`."


Tutorial de github

https://www.youtube.com/watch?v=TuOQBfhp-r0



### En cuanto a **Git**, sigue estas pautas:
1. **Haz un commit por cada cambio significativo**. Algunos ejemplos de cuándo debes hacer un commit:
   - **Añadiste una tabla completa** a tu página, como la tabla de razas de perros o gatos.
   - **Cambiás la estructura de una página**, como reorganizar secciones o modificar el diseño general.
   - **Agregaste o modificaste un estilo CSS importante**, como ajustar el tamaño de las imágenes o cambiar el espaciado entre los elementos de la tabla.
   - **Subiste nuevas imágenes o modificaste el contenido** de una página de detalles.
   - **Corriges errores importantes en el código** o cambias la lógica de los enlaces entre páginas.

2. **Descripciones claras en los commits**. Cada commit debe describir claramente lo que cambiaste, por ejemplo:
   - "Añadí tabla de razas de perros con enlaces a las páginas de detalles."
   - "Modifiqué la estructura de la página principal para mejorar el diseño."
   - "Agregué imágenes de perros y gatos en la carpeta img y ajusté el tamaño de las imágenes."
   - "Corregí los enlaces para abrir páginas de detalles en una nueva pestaña."

Esto ayudará a llevar un control claro de cada mejora o cambio que realices en los proyectos.



## **Tutorial del Box Model**

**Componentes del Box Model**

1. **Content:** El área donde se encuentra el contenido del elemento. Utiliza las propiedades `width` y `height`.

2. **Padding:** El espacio interno entre el contenido y el borde. Utiliza `padding-top`, `padding-right`, `padding-bottom`, `padding-left`, o simplemente `padding` para todos los lados.

3. **Border:** El borde alrededor del padding. Utiliza `border-width`, `border-style`, y `border-color` para definir su grosor, estilo y color.

4. **Margin:** El espacio externo alrededor del borde. Utiliza `margin-top`, `margin-right`, `margin-bottom`, `margin-left`, o simplemente `margin` para todos los lados.

**Cómo Funciona el Box Model**

El tamaño total del elemento es la suma de su contenido, padding, borde y margin. Ajusta estos valores para controlar el diseño y el espaciado en tu página web.

**Ejemplo de CSS para el Box Model:**

```css
.box {
  width: 200px; /* Tamaño del contenido */
  padding: 10px; /* Espacio interno alrededor del contenido */
  border: 5px solid black; /* Borde alrededor del padding */
  margin: 15px; /* Espacio externo alrededor del borde */
  background-color: lightgrey; /* Color de fondo para mejor visualización */
}
```

---

Espero que esta guía te ayude a aplicar correctamente el box model en tus proyectos y te facilite el trabajo con CSS. ¡Buena suerte!

### **Proyecto 1: Perros y Gatos (Simplificado)**

**Objetivo:** Crear una página principal con dos tablas para razas de gatos y perros, con enlaces a páginas de detalles de cada raza.

**Tareas:**

1. **Página Principal (`index.html`):**
   - Crea una tabla para razas de gatos y otra para razas de perros.
   - Cada fila de la tabla debe incluir el nombre de la raza y un enlace a una página de detalles.
   
2. **Páginas de Detalles:**
   - Cada página debe contener:
     - Un título (`<h1>`) con el nombre de la raza.
     - Una imagen de la raza desde la carpeta `img`.
     - Una breve descripción usando `<strong>` y `<em>` para resaltar partes del texto.

3. **CSS (`styles.css`):**
   - **Estiliza las tablas:** Usa bordes, colores de fondo y espaciamiento adecuado. Asegúrate de que las tablas tengan suficiente `padding` en las celdas y `margin` para separarlas de otros elementos.
   - **Imágenes:** Ajusta el tamaño de las imágenes y usa `padding` y `margin` para que no se desborden ni se peguen a otros elementos.
   - **Enlaces:** Estiliza los enlaces para que sean visibles y resalten al pasar el cursor sobre ellos.

4. **Estructura de Carpetas:**
   - Carpeta raíz con `index.html` y `styles.css`.
   - Carpeta `img` para imágenes de los animales.
   - Carpeta `paginas` para las páginas de detalles.

---

### **Proyecto 2: La Importancia del Cuidado de las Mascotas (Simplificado)**

**Objetivo:** Practicar el uso de etiquetas HTML para resaltar texto, enlaces, y trabajar con la estructura semántica de una página.

**Tareas:**

1. **Página de Contenido (`cuidado_mascotas.html`):**
   - Crea un párrafo sobre "La importancia del cuidado de las mascotas" que incluya:
     - Texto en negritas con `<strong>`.
     - Texto en cursivas con `<em>`.
     - Enlaces con `<a>` que se abran en una pestaña nueva (`target="_blank"`).
     - Una imagen ilustrativa de las mascotas con atributos `alt`.
   - Usa etiquetas adicionales como `<u>`, `<mark>`, `<del>`, `<sup>`, y `<sub>`.

2. **CSS (`styles.css`):**
   - **Párrafo:** Estiliza el párrafo para que el texto destacado sea visible. Usa `padding` para darle espacio al contenido y `margin` para separar el párrafo de otros elementos.
   - **Imágenes:** Ajusta el tamaño y la alineación de las imágenes. Asegúrate de que se ajusten correctamente al diseño.
   - **Enlaces:** Estiliza los enlaces para que sean fáciles de identificar y proporcionen una buena experiencia de usuario al pasar el cursor sobre ellos.

3. **Estructura de la Página:**
   - Incluye un título principal (`<h1>`) que resuma el tema de tu página.
   - Usa `<h2>` o etiquetas menores para subtítulos.
   - Asegúrate de que todas las imágenes y enlaces tengan atributos relevantes para mejorar accesibilidad (como `alt` para imágenes).

---

### **Proyecto Combinado: Explora el Mundo de las Mascotas**

**Objetivo:** Crear un sitio web sobre razas de perros y gatos utilizando HTML y CSS, combinando tablas, enlaces, imágenes y varias etiquetas de formato de texto.

**Tareas:**

1. **Página Principal (`index.html`):**
   - Crea una página principal con:
     - Un título destacado (`<h1>`).
     - Dos secciones con títulos (`<h2>`), una para razas de gatos y otra para razas de perros.
     - Una tabla para cada sección con 5 razas diferentes de gatos y perros.
     - Cada fila de la tabla debe incluir el nombre de la raza y un enlace a una página de detalles específica para esa raza.

2. **Páginas de Detalles:**
   - Cada página de detalles debe incluir:
     - Un título (`<h1>`) con el nombre de la raza.
     - Una imagen de la raza desde la carpeta `img`.
     - Un párrafo descriptivo usando `<strong>` y `<em>`.
     - Un enlace adicional que lleve a una fuente externa de información sobre la raza, configurado para abrir en una pestaña nueva (`target="_blank"`).

3. **CSS (`styles.css`):**
   - **Estiliza las tablas:** Asegúrate de que las tablas sean claras y organizadas. Usa `padding` en las celdas y `margin` para separar las tablas de otros elementos.
   - **Imágenes:** Ajusta el tamaño y el espaciado de las imágenes usando `padding` y `margin` para que se alineen correctamente con el texto.
   - **Diseño Cohesivo:** Usa una paleta de colores consistente y fuentes legibles. Asegúrate de que todos los elementos sean fácilmente visibles y accesibles.

4. **Optimización y Accesibilidad:**
   - **Imágenes:** Limita el ancho de las imágenes a un máximo de 200px y usa formatos adecuados para la web. Aplica técnicas de optimización de imágenes.
   - **Accesibilidad:** Usa atributos `alt` en todas las imágenes y aplica técnicas de accesibilidad para mejorar la experiencia del usuario.

5. **Estructura del Proyecto:**
   - Carpeta raíz con `index.html` y `cuidado_mascotas.html`.
   - Carpeta `img` para imágenes de razas.
   - Carpeta `paginas` para páginas de detalles de las razas.
   - `styles.css` para estilos.

   - ### **Guía de Propiedades y Etiquetas para los Ejercicios**

**Proyecto 1: Perros y Gatos (Simplificado)**

1. **Página Principal (`index.html`):**
   - **Tablas:**
     - Propiedades CSS: `border`, `padding`, `margin`
     - Etiquetas HTML: `<table>`, `<tr>`, `<td>`
   - **Imágenes:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<img>`

2. **Páginas de Detalles:**
   - **Descripción de Razas:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<p>`, `<strong>`, `<em>`
   - **Imágenes de Razas:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<img>`

**Proyecto 2: La Importancia del Cuidado de las Mascotas (Simplificado)**

1. **Página de Contenido (`cuidado_mascotas.html`):**
   - **Texto en Negritas y Cursivas:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<p>`, `<strong>`, `<em>`
   - **Enlaces:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<a>`
   - **Imágenes:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<img>`

**Proyecto Combinado: Explora el Mundo de las Mascotas**

1. **Página Principal (`index.html`):**
   - **Tablas:**
     - Propiedades CSS: `border`, `padding`, `margin`
     - Etiquetas HTML: `<table>`, `<tr>`, `<td>`
   - **Imágenes:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<img>`

2. **Páginas de Detalles:**
   - **Descripción de Razas:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<p>`, `<strong>`, `<em>`
   - **Enlace Adicional:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<a>`
   - **Imágenes:**
     - Propiedades CSS: `padding`, `margin`
     - Etiquetas HTML: `<img>`

---


