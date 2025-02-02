# Documentación del Código HTML del Portafolio

## Información General
Este código corresponde a una página de portafolio personal, creada en la clase "HTML y CSS: ambientes de desarrollo, estructura de archivos y tags" de la unidad **Principiante en Programación G8 - ONE**, que forma parte de la certificación **ORACLE ONE G8 - INACAP**.

### Propósito del Proyecto
El objetivo del proyecto es presentar un portafolio personal que permita a la desarrolladora **Ana García** destacar su experiencia como desarrolladora Front-end y su especialización en React, HTML y CSS. Incluye enlaces a redes sociales y una imagen representativa del trabajo.

---

## Estructura del Código

### Declaración Inicial
```html
<!DOCTYPE html>
<html lang="es-mx">
```
Se utiliza la declaración `<!DOCTYPE html>` para indicar que el documento está en HTML5. El atributo `lang="es-mx"` define el idioma principal como español (México).

---

### `<head>`
El encabezado incluye elementos clave para el funcionamiento y optimización del sitio:

- **Codificación de Caracteres:**
  ```html
  <meta charset="UTF-8">
  ```
  Define la codificación como UTF-8 para soportar caracteres especiales.

- **Compatibilidad:**
  ```html
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  ```
  Garantiza compatibilidad con navegadores modernos.

- **Diseño Responsivo:**
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
  Asegura que el contenido se adapte correctamente a diferentes tamaños de pantalla.

- **Título:**
  ```html
  <title>Portafolio</title>
  ```
  Define el título del documento.

- **Estilos CSS:**
  ```html
  <link rel="stylesheet" href="style.css">
  ```
  Enlaza una hoja de estilos externa llamada `style.css`.

---

### `<body>`
El cuerpo contiene los elementos principales de la página:

#### `<header>`
Un contenedor vacío reservado para posibles elementos de encabezado futuros.

#### `<main>`
Sección principal del contenido, que incluye:

- **Encabezado Principal (`<h1>`):**
  ```html
  Eleve tu negocio digital a otro nivel <strong>con un Front-end de calidad!</strong>
  ```
  Utiliza un texto destacado para captar la atención del usuario.

- **Parrafo Descriptivo (`<p>`):**
  ```html
  ¡Hola! Soy Ana García, desarrolladora Front-end con especialización en React, HTML y CSS. Ayudo a pequeños negocios y diseñadores a llevar a cabo buenas ideas. ¿Hablamos?
  ```
  Proporciona información breve sobre la desarrolladora y su propuesta de valor.

- **Enlaces a Redes Sociales:**
  ```html
  <a href="https://instagram.com/">Instagram</a>
  <a href="https://github.com/">GitHub</a>
  ```
  Permite al usuario conectarse con la desarrolladora en sus redes sociales.

- **Imagen Representativa (`<img>`):**
  ```html
  <img src="Imagem.png" alt="Foto de Ana García desarrolando un proyecto">
  ```
  Muestra una imagen con texto alternativo para accesibilidad.

#### `<footer>`
Un contenedor vacío reservado para elementos del pie de página.

---

## Notas Importantes
1. **Accesibilidad:** Se utiliza el atributo `alt` en la etiqueta `<img>` para describir la imagen a usuarios con discapacidades visuales.
2. **Diseño Responsivo:** La metaetiqueta `viewport` asegura que la página sea visualizada correctamente en dispositivos móviles.
3. **Extensibilidad:** Los elementos `<header>` y `<footer>` se encuentran vacíos, lo que permite futuras ampliaciones en la estructura.

---

## Requisitos Técnicos
1. **Archivo CSS Externo:** Se debe incluir un archivo `style.css` con las reglas de estilo correspondientes.
2. **Imagen:** La imagen `Imagem.png` debe estar ubicada en el mismo directorio que el archivo HTML o ajustarse su ruta si se encuentra en otra ubicación.

---

## Enlaces Relacionados
- [Instagram](https://instagram.com/)
- [GitHub](https://github.com/)

---

### Mejoras Posibles
1. Agregar contenido en las secciones `<header>` y `<footer>` para enriquecer la página.
2. Utilizar una estructura semántica más completa, incluyendo etiquetas como `<nav>` o `<section>` si es necesario.
3. Incluir un favicon en la sección `<head>` para mejorar la presentación en navegadores.
