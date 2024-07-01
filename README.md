# Restaurante Bolivian Food

Bienvenido al proyecto del sitio web "Restaurante Bolivian Food". Este proyecto tiene como objetivo presentar el restaurante, su historia, su menú, y proporcionar una manera fácil para que los clientes se pongan en contacto y realicen pedidos en línea.

## Índice

1. [Estructura del Proyecto](#estructura-del-proyecto)
2. [Contenido de las Páginas](#contenido-de-las-páginas)
3. [Estilos CSS](#estilos-css)
4. [Instalación](#instalación)
5. [Contribuciones](#contribuciones)
6. [Contacto](#contacto)
7. [Licencia](#licencia)

## Estructura del Proyecto

El proyecto está compuesto por varias páginas web y un archivo de estilos CSS. A continuación se detalla la estructura del proyecto:

### Archivos HTML

1. **index.html**: Página principal del restaurante.
2. **sobre-nosotros.html**: Página que proporciona información sobre la historia y misión del restaurante.
3. **menu.html**: Página que muestra el menú con varios platos típicos de Bolivia, incluyendo fotos, precios y descripciones.
4. **contactanos.html**: Página de contacto con un formulario para que los usuarios puedan enviar mensajes al restaurante.

### Archivo CSS

1. **style.css**: Archivo de estilos CSS que proporciona la apariencia y el diseño del sitio web.

## Contenido de las Páginas

### index.html

La página principal incluye:
- Un encabezado con el nombre del restaurante y un menú de navegación.
- Una breve introducción al restaurante y su propuesta.

### sobre-nosotros.html

La página "Sobre Nosotros" incluye:
- Información sobre la historia del restaurante.
- Secciones que detallan la misión y la pasión del restaurante por la cocina boliviana.
- Varias imágenes que representan la experiencia y el ambiente del restaurante.

### menu.html

La página "Menú" incluye:
- Una lista de 10 platos típicos bolivianos.
- Cada plato tiene una imagen, precio, breve descripción de los ingredientes y un botón para hacer un pedido.

### contactanos.html

La página "Contáctanos" incluye:
- Un formulario de contacto que permite a los usuarios enviar sus nombres, correos electrónicos, números de teléfono y mensajes.
- Botón para enviar el formulario.

## Estilos CSS

El archivo **style.css** define los estilos para todas las páginas del sitio web, incluyendo:
- Estilos generales para el cuerpo, encabezados y navegación.
- Estilos específicos para las secciones de contenido.
- Estilos para formularios de contacto y botones de envío.

### Ejemplo de código CSS:

```css
body {
  font-family: 'Lucida Sans', sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
  padding: 20px;
}

header {
  background: rgb(108, 83, 249);
  color: #ffffff;
  padding: 20px;
  text-align: center;
  margin-bottom: 20px;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0px;
}

nav ul li {
  display: inline;
  margin-right: 60px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  padding: 5px 10px;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

nav ul li a:hover {
  background-color: #45a049;
}

.content-box {
  background: rgb(191, 197, 250);
  border: 2px solid #cccccc;
  padding: 20px;
  margin-bottom: 20px;
}

.contact-form label {
  margin-bottom: 5px;
  font-weight: bold;
}

.contact-form input,
.contact-form textarea {
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #cccccc;
  border-radius: 5px;
}

.contact-form button {
  margin: auto;
  padding: 10px;
  background-color: #6658fe;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  width: 250px;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #2455f7;
}

footer {
  background: rgb(120, 98, 248);
  color: #fff;
  text-align: center;
  padding: 10px 0;
  margin-top: 20px;
}
```

### Contribuciones
Si deseas contribuir a este proyecto, por favor, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature-nuevaCaracterística).
3. Realiza tus cambios y haz commit (git commit -m 'Añadir nueva característica').
4. Sube tus cambios a la rama (git push origin feature-nuevaCaracterística).
5. Abre un Pull Request.

### Contacto
Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto con nosotros enviando un correo electrónico a huayhualopezwendy@gmail.com.

### Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
