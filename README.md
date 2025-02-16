# Amazon Learning - Tienda de Cursos de Idiomas

Este proyecto es una página web simple donde los usuarios pueden comprar cursos de idiomas en línea. Está diseñado para ser fácil de entender y modificar, incluso para personas sin experiencia en informática.

## 1. ¿Qué contiene este proyecto?
El proyecto consta de varias páginas HTML y un archivo de estilos CSS:

- `index.html` → Página principal con los idiomas disponibles.
- `espanol.html`, `ingles.html`, `aleman.html`, `frances.html` → Páginas específicas para cada idioma.
- `curso.html` → Página de ejemplo de un curso individual.
- `styles.css` → Archivo de estilos que da diseño a la página.

## 2. ¿Cómo editar la página web?
### 2.1 Requisitos
Para modificar esta web, solo necesitas:
- Un **editor de texto** (como el Bloc de notas o Visual Studio Code).
- Un **navegador web** (como Google Chrome o Firefox).

### 2.2 Pasos para modificar el contenido
#### **Modificar el nombre de la página**
1. Abre el archivo `index.html` con un editor de texto.
2. Busca la línea:
   ```html
   <h1>Amazon Learning</h1>
   ```
3. Cambia "Amazon Learning" por el nombre que prefieras.
4. Guarda el archivo (`Ctrl + S`) y ábrelo en el navegador para ver los cambios.

#### **Modificar los cursos disponibles**
1. Abre el archivo `index.html`.
2. Busca la sección donde están los cursos:
   ```html
   <div class="card">
       <img src="espanol.jpg" alt="Español">
       <h2>Español</h2>
       <p>Aprende español de manera interactiva y rápida.</p>
       <a href="espanol.html" class="btn">Ver Cursos</a>
   </div>
   ```
3. Cambia el texto dentro de `<h2>`, `<p>` o el enlace dentro de `<a href="..."></a>` según lo que necesites.

#### **Agregar un nuevo idioma**
1. Copia un bloque de código similar al anterior.
2. Cámbiale el nombre y la imagen (ejemplo: `italiano.jpg`).
3. Crea un nuevo archivo `italiano.html` basado en otro archivo de idioma y modifícalo.

### 2.3 Modificar los estilos (diseño)
1. Abre el archivo `styles.css`.
2. Para cambiar los colores de los botones, busca esta parte del código:
   ```css
   .btn {
       background: #0073e6;
   }
   ```
   y cambia el código de color (`#0073e6`) por otro (ejemplo: `#ff0000` para rojo).

3. Guarda el archivo y actualiza la página en el navegador (`F5`).

## 3. ¿Cómo ver los cambios?
Después de modificar los archivos, abre `index.html` en un navegador (haz doble clic en el archivo o arrástralo al navegador) para ver los cambios en tiempo real.

## 4. ¿Cómo subir la página a Internet?
Si deseas que otras personas puedan acceder a la web, puedes subir los archivos a un hosting gratuito como:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

¡Listo! Con esto puedes personalizar la página sin necesidad de saber programar. 🎉

