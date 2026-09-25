# NeuroLab — Sitio web sobre Redes Neuronales

Sitio de 3 páginas (HTML5 + CSS3) desarrollado como plantilla para el
**Parcial N°1** de la asignatura **Ingeniería Web**, Facultad de
Ingeniería de Sistemas Computacionales, Universidad Tecnológica de
Panamá (UTP). Tema asignado: **Redes Neuronales**.

## Vista general

| Página          | Archivo               | Contenido                                                        |
|------------------|------------------------|-------------------------------------------------------------------|
| Inicio           | `html/index.html`     | Hero, sección "Conceptos clave" y tarjetas promocionales          |
| Acerca de        | `html/acerca.html`    | `<article>` explicativo + `<aside>`, video y audio de ejemplo     |
| Contacto         | `html/contacto.html`  | Formulario validado, ubicación y mapa de Google embebido          |

## Estructura de carpetas

```
├── html/
│   ├── index.html
│   ├── acerca.html
│   └── contacto.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── img/
│   ├── logo.svg
│   └── network-mesh.svg
├── video/        (agregar aquí el video real)
├── audio/        (agregar aquí el audio real)
├── LEEME.txt     (guía paso a paso para completar la plantilla)
└── README.md
```

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- CSS3 (variables, Grid, Flexbox, diseño responsive)
- JavaScript nativo (menú móvil, validación de formulario, guardado de datos)
- Tipografías: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (títulos) y [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) (texto), vía Google Fonts

## Paleta de colores

| Color              | Uso                          | Hex        |
|--------------------|-------------------------------|------------|
| Azul marino         | Fondos oscuros, texto de títulos | `#0A1628` |
| Cobalto             | Color de marca / enlaces      | `#2444B8` |
| Cobalto claro       | Estados hover                 | `#3B5FE0` |
| Turquesa (acento)   | Detalles y contraste          | `#00C7B1` |
| Fondo claro         | Fondo general del sitio       | `#F5F7FB` |

## Funcionalidades

- **Navegación responsive** con menú hamburguesa en móvil.
- **Formulario de contacto** con validación de nombre, apellido,
  correo, teléfono, asunto y mensaje.
- **Guardado de datos**: al enviarse el formulario, el registro se
  guarda en `localStorage` y se descarga automáticamente como
  `contactos.json` (ver `js/script.js`).
- **Mapa de Google Maps** embebido en la página de contacto.
- Diseño accesible: foco de teclado visible y respeto a
  `prefers-reduced-motion`.

## Cómo verlo localmente

No requiere instalación. Basta con abrir `html/index.html` en el
navegador, o servirlo con una extensión tipo "Live Server".

## Pendiente antes de entregar (plantilla → contenido real)

- [ ] Reemplazar los textos de ejemplo por información real y verificada.
- [ ] Cambiar cada recuadro `placeholder-img` por imágenes reales dentro de `/img`.
- [ ] Agregar el video y audio reales en `/video` y `/audio`.
- [ ] Actualizar enlaces de redes sociales, teléfono y correo.
- [ ] Cambiar la ubicación del mapa por la dirección real (ver `LEEME.txt`).
- [ ] Renombrar la carpeta raíz del proyecto con los apellidos de los 2 integrantes.
- [ ] Subir el proyecto a Teams y a un hosting gratuito (Netlify, GitHub Pages, Vercel).

## Técnica de diseño utilizada

Wireframes de baja fidelidad, usados como base para la estructura y
disposición de cada página.

## Autoría

Proyecto académico — Emilio Muñoz Ortiz, Ingeniería Web (1SF134), UTP.
