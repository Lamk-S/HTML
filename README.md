# HTML — Apuntes y Proyectos Prácticos

[HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
[CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
[Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
[VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
[Status](https://img.shields.io/badge/Status-En%20Progreso-yellow?style=for-the-badge)
[Stars](https://img.shields.io/github/stars/Lamk-S/HTML?style=social)

> Repositorio de aprendizaje documentado sobre HTML5, desde fundamentos hasta estructuras semánticas y proyectos reales con CSS y Bootstrap.

**Repositorio:** https://github.com/Lamk-S/HTML

---

## Objetivo
Mantener un registro claro, ordenado y progresivo de todo lo aprendido en el curso de HTML, con enfoque en **estructura y semántica correcta**, accesibilidad básica y preparación para CSS y JavaScript.

No es solo teoría: cada concepto tiene su archivo de práctica y se valida en proyectos de caso real.

## Estructura del Repositorio
```text
HTML/
├── Basic/
│ ├── 001-HelloWorld.html ... 027-Semantic-Elements.html
│ ├── Practical exercises/
│ │   └── Curso-online/         # Landing page 100% semántica
│ ├── resources/
│ │   ├── audio/ | img/ | img/favicon/
│ ├── style/                    # form.css, head.css, table.css
│ └── js/                       # head.js
│
└── WebPages/
    ├── WP01-TechStore/         # E-commerce con HTML + CSS puro
    │   └── assets/css/ | assets/img/
    └── WP02-Bootstrap/
        ├── B01-Integration/
        ├── B02-GridSystem/     # Grid, responsive, carousel
        ├── B03-Components/     # Cards, forms, dropdowns
        ├── B04-Forms/          # Formulario avanzado
        └── B05-Login/          # Login UI
```

## Contenido del Curso - Basic (27 Lecciones)

- **Fundamentos:** 001-HelloWorld, 002-NestedElements, 005-Attributes, 006-RootFolder, 007-BasicSyntax, 008-html-basic-structure
- **Texto y Listas:** 009-Titles-Paragraphs, 010-TextFormatting, 011-Lists, 003-UnorderedLists, 004-ReplaceableComponents
- **Enlaces y Rutas:** 012-Relative-Paths, 013-Internal-Links, 014-External-Links, 015-Page-Links
- **Multimedia:** 016-Image-Formats, 017-Images-HTML, 018-Video-HTML, 019-Iframes, 020-YouTube-Embed, 021-Audio-Embed
- **Estructura Avanzada:** 022-Tables-Basics, 023-Forms-Elements, 024-Input-Elements, 025-Head-Elements, 026-Meta-Attributes, 027-Semantic-Elements

## Proyectos Prácticos

### 1. Curso Online - HTML Semántico Puro
`Basic/Practical exercises/Curso-online/index.html`
Landing page construida **solo con HTML**, sin CSS/JS intencionalmente.
- Uso correcto de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<blockquote>`, `<footer>`, `<address>`, `<dl>`
- Jerarquía de encabezados y `aria-label` en navegación
- Formulario accesible con `label for`, `required`

### 2. WP01 - Lamk's Tech Store
E-commerce de tecnología con HTML + CSS puro.
- Header fijo con navegación suave (`scroll-behavior`)
- Hero banner, grid de ofertas con precios y descuentos
- Categorías con imágenes circulares, formulario de sugerencias
- Layout con CSS Grid + Flexbox, componentes reutilizables

### 3. WP02 - Bootstrap 5.3
Migración a framework y componentes:
- **B01 Integration:** Setup base de Bootstrap
- **B02 GridSystem:** Sistema de 12 columnas, `col-*`, `justify-content-*`, imágenes `img-fluid` y carousel
- **B03 Components:** Cards, badges personalizados, inputs y dropdowns
- **B04 Forms:** Formulario de inscripción con validación, `input-group`, radios, checkboxes
- **B05 Login:** Login centrado con FontAwesome, estilos custom y focus states

## Tecnologías y Herramientas
**Core:** HTML5, CSS3, Bootstrap 5.3
**Librerías:** Ionicons, FontAwesome
**Editor:** Visual Studio Code + Live Preview para cambios en tiempo real

## Cómo Ejecutar Localmente
```bash
# 1. Clonar repositorio
git clone https://github.com/Lamk-S/HTML.git
cd HTML

# 2. Abrir en VS Code
code .

# 3. Ejecutar
# Usa la extensión Live Preview o abre cualquier .html en el navegador
```

No requiere instalación de dependencias.

##  Buenas Prácticas Aplicadas
- HTML validado W3C, semántica primero sobre `div` innecesarios
- Atributos `alt` descriptivos, favicon multi-resolución
- `head` completo: charset, viewport, title, meta
- Separación de responsabilidades: /style, /js, /resources
- Accesibilidad: labels asociados, fieldset/legend, contraste y navegación por teclado

## Roadmap
- [x] Fundamentos y semántica HTML
- [x] Proyecto TechStore con CSS puro
- [x] Integración Bootstrap 5
- [ ] Desplegar WebPages en GitHub Pages
- [ ] Refactor a BEM + mobile-first

## Autor
**Melvin López (Lamk-S)**
- GitHub: [@Lamk-S](https://github.com/Lamk-S)
