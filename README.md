# Frontend Mentor - Recipe Page Solution

Esta es mi solución al desafío [Recipe page](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm) de Frontend Mentor. Este reto me permitió practicar buenas prácticas de HTML y CSS enfocadas en diseño responsivo, organización del código y manejo de tipografías personalizadas.

## 📋 Tabla de contenido

- [🔍 Vista general](#-vista-general)
  - [✅ El reto](#el-reto)
  - [📸 Captura de pantalla](#captura-de-pantalla)
  - [🔗 Enlaces](#enlaces)
- [🛠️ Mi proceso](#-mi-proceso)
  - [🧱 Tecnologías usadas](#tecnologías-usadas)
  - [📚 Lo que aprendí](#lo-que-aprendí)
  - [🧭 Desarrollo futuro](#desarrollo-futuro)
  - [🔧 Recursos útiles](#recursos-útiles)
- [👤 Autor](#autor)

---

## 🔍 Vista general

### ✅ El reto

Construir una página de receta a partir de un diseño provisto por Frontend Mentor, asegurando:
- Semántica HTML5 correcta.
- Diseño responsivo para dispositivos móviles y escritorio.
- Buen uso de tipografías personalizadas locales.
- Estructura limpia y ordenada del código.

### 📸 Captura de pantalla

![Recipe Screenshot](./design/desktop-design.jpg)

### 🔗 Enlaces

- 📄 Solución: [Mi repositorio en GitHub](https://github.com/Alejo224)
- 🌐 Sitio en vivo: [Ver proyecto](https://alejo224.github.io/frontendmentor-recipe/)

---

## 🛠️ Mi proceso

### 🧱 Tecnologías usadas

- HTML5 semántico
- CSS3
- Flexbox
- Tipografías personalizadas locales (`@font-face`)
- Mobile-first workflow
- Media queries
- Buenas prácticas con estructura modular de clases (`BEM-like`)

### 📚 Lo que aprendí

- Cómo enlazar y usar fuentes descargadas localmente con `@font-face`.
- Cómo estructurar HTML semántico utilizando `header`, `main`, `section`, `article` y `footer`.
- Uso de `flex` y `flex-wrap` para adaptar el diseño a distintos tamaños.
- Aplicar `media queries` para mejorar la visualización en pantallas móviles.
- Organización del código en capas: contenido (`HTML`), estilo (`styles.css`), y tipografías (`fonts.css`).

#### Ejemplo de `@font-face` personalizado:

```css
@font-face {
  font-family: "Outfit";
  src: url("/assets/fonts/outfit/static/Outfit-Light.ttf") format("truetype");
  font-weight: 300;
  font-display: swap;
}
````

#### Ejemplo de diseño responsivo:

```css
@media screen and (max-width: 480px) {
  .card {
    margin: 0;
  }

  img {
    border-radius: 0;
    margin: 0;
  }
}
```

### 🧭 Desarrollo futuro

* Aplicar un sistema de diseño con `CSS Variables` para colores y tipografías.
* Mejorar accesibilidad usando `aria-labels` y roles.
* Implementar un modo oscuro como mejora extra.

### 🔧 Recursos útiles

* [CSS Tricks - @font-face Guide](https://css-tricks.com/snippets/css/using-font-face/)
* [MDN - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
* [Frontend Mentor Tips](https://www.frontendmentor.io/resources)

---

## 👤 Autor

* GitHub: [@Alejo224](https://github.com/Alejo224)
* Frontend Mentor: [@Alejo224](https://www.frontendmentor.io/profile/Alejo224)

---

## ✅ Créditos

Desafío realizado gracias a la plataforma [Frontend Mentor](https://www.frontendmentor.io). Inspiración tomada de su diseño base.
Código y estructura realizados completamente por mí.
