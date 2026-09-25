# NeuroLab — Sitio web sobre Redes Neuronales

Sitio de 3 páginas (HTML5 + CSS3) para el **Parcial N°1** de la
asignatura **Ingeniería Web**, Facultad de Ingeniería de Sistemas
Computacionales, Universidad Tecnológica de Panamá (UTP). Tema:
**Redes Neuronales**.

## Contenido de cada página

### `html/index.html` — Inicio
- Hero con imagen de portada e introducción al tema.
- **Conceptos clave**: neuronas artificiales, análisis de datos y
  aprendizaje, cada uno con imagen propia.
- Recuadro "Dato clave" sobre la cantidad de parámetros de una red
  neuronal.
- Tarjetas "Cómo funcionan" y "Casos de uso reales", con enlaces a
  Acerca de y Contacto.

### `html/acerca.html` — Acerca de
- **¿Qué es la inteligencia artificial?**: definición y relación con
  las redes neuronales, con imagen ilustrativa y explicación del flujo
  de trabajo (recolección, limpieza y división de datos).
- **Video introductorio**: video de YouTube embebido
  (`youtube.com/embed/M6oDiCQCins`) sobre el tema.
- Explicación del entrenamiento y la propagación inversa (backpropagation).
- **Tipos de redes neuronales**: prealimentadas, recurrentes,
  convolucionales (CNN) y adversariales (GAN).
- **Audio complementario**: narración en `audio/ttsmaker-file-2026-9-24-22-53-54.mp3`,
  con su transcripción completa incluida en la página como alternativa
  accesible.
- Aside "En esta sección" con enlaces internos (anclas `#inteligencia-artificial`,
  `#tipos-de-redes`, `#audio`, `#impacto`) e imagen de apoyo.
- **Impacto**: aplicaciones reales en accesibilidad (detección temprana
  de Alzheimer por voz, traducción de lenguaje de señas en tiempo real,
  subtitulado automático).

### `html/contacto.html` — Contacto
- Formulario validado (nombre, apellido, correo, teléfono, asunto,
  mensaje) que guarda cada envío y descarga `contactos.json`
  (`js/script.js`).
- Aside "Antes de escribirnos" con recomendaciones para el usuario.
- Bloque de ubicación (Universidad Tecnológica de Panamá, Campus
  Víctor Levi Sasso) con mapa de Google Maps embebido.

> ⚠️ El teléfono, el correo y la dirección de esta página aún tienen
> valores de ejemplo — `(507) 000-0000` / `contacto@neurolab.com`.
> Avísame si quieres que los reemplace por los datos reales antes de
> entregar.

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
├── img/     (íconos de redes sociales, logo e imágenes del contenido)
└── audio/
    └── ttsmaker-file-2026-9-24-22-53-54.mp3
```

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- CSS3 (variables, Grid, Flexbox, diseño responsive)
- JavaScript nativo (menú móvil, validación y guardado del formulario)
- Video embebido de YouTube y audio narrado (generado con una
  herramienta de texto a voz)
- Tipografías: Space Grotesk (títulos) e IBM Plex Sans (texto), vía Google Fonts

## Paleta de colores

| Color              | Uso                              | Hex        |
|--------------------|------------------------------------|------------|
| Azul marino         | Fondos oscuros, texto de títulos   | `#0A1628` |
| Cobalto             | Color de marca / enlaces           | `#2444B8` |
| Cobalto claro       | Estados hover                      | `#3B5FE0` |
| Turquesa (acento)   | Detalles y contraste               | `#00C7B1` |
| Fondo claro         | Fondo general del sitio            | `#F5F7FB` |

## Funcionalidades

- Navegación responsive con menú hamburguesa en móvil.
- Formulario de contacto validado en el navegador.
- Guardado de cada envío en `localStorage` y descarga automática de
  `contactos.json`.
- Mapa de Google Maps embebido.
- Accesibilidad: transcripción del audio, foco de teclado visible y
  respeto a `prefers-reduced-motion`.

## Antes de subirlo a un hosting público

Varias imágenes provienen de bancos de imágenes/stock (Vecteezy,
iStock, etc.) identificables por su nombre de archivo. Si el sitio se
publicará públicamente (no solo para la entrega del parcial), conviene
verificar la licencia de uso de cada una o sustituirlas por imágenes
propias o de bancos con licencia libre.

## Técnica de diseño utilizada

Wireframes de baja fidelidad, usados como base para la estructura y
disposición de cada página.

## Autoría

Proyecto académico — Emilio Muñoz Ortiz, Ingeniería Web (1SF134), UTP.
