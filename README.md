# Landing Page

Portfolio personal como web developer especializado en el ecosistema
JavaScript moderno. Mi carta de presentación profesional, con tema Tokyo Night,
tipografía JetBrains Mono y enfoque mobile-first.

## Descripción

Mi página personal tipo portfolio donde presento mi perfil como desarrollador
frontend. Incluye secciones de presentación, stack tecnológico con acordeones
nativos, proyectos destacados con tarjetas interactivas y contacto directo.
Todo el contenido está en español. Sin JavaScript.

## Tecnologías

- **HTML5** — estructura semántica (`header`, `main`, `footer`, `nav`,
  `section`, `article`, `address`)
- **CSS3 puro** — sin preprocesadores ni frameworks
- **CSS @layers** — organización modular en 10 capas
- **CSS Custom Properties** — sistema de diseño con colores Tokyo Night
- **CSS Grid** — grid de proyectos responsivo con `auto-fill` y `minmax()`
- **CSS Flexbox** — header, nav, footer, links y badges
- **BEM** — convención de nomenclatura para clases CSS
- **Responsive Images** — `loading="eager"` en hero, `decoding="async"`
- **Sin JavaScript** — cero dependencias del lado del cliente

## Características

- **Diseño mobile-first** — optimizado para móviles, tablet y desktop
- **Tema Tokyo Night** — dark mode nativo vía variables CSS
- **Stack interactivo** — acordeón con `<details>` y `<summary>` sin JS
- **Grid de proyectos** — tarjetas con efecto hover en `translateY`
- **Accesibilidad** — skip link, `:focus-visible`, `prefers-reduced-motion`,
  estilos de impresión
- **SEO** — meta tags, Open Graph, Twitter Cards, canonical
- **Performance** — `content-visibility: auto` con `contain-intrinsic-size`

## Estructura del proyecto

```text
.
├── index.html           # Página principal (~347 líneas)
├── css/
│   └── styles.css       # Estilos (~659 líneas, 10 @layers)
├── assets/
│   ├── developer.png    # Imagen de perfil (hero)
│   ├── favicon.png      # Favicon del sitio
│   └── preview.png      # Preview para Open Graph
├── .github/
│   └── workflows/
│       └── deploy.yml   # Deploy a GitHub Pages
├── .gitignore
└── README.md
```

## Secciones de la página

1. **Nav** — sticky con logo B14S, enlaces a Sobre Mí, Stack, Proyectos,
   Contacto
2. **Hero** — título profesional, descripción, imagen de perfil, enlaces a
   GitHub y LinkedIn
3. **Tech bar** — tecnologías principales (HTML5, CSS3, JavaScript)
4. **Sobre Mí** — tarjeta con mi perfil profesional y objetivo Full Stack
5. **Stack** — 4 acordeones: Lenguajes, Markup & Styling, Herramientas,
   Metodologías
6. **Proyectos** — 3 tarjetas: agent-stack (skills para IA), Ableton (réplica
   visual), Podia (landing informativa)
7. **Contacto** — cita motivacional y email con botón de acción
8. **Footer** — enlaces sociales (GitHub, LinkedIn, Twitter, Facebook) y
   copyright

## Breakpoints

| Nombre  | Valor   | Diseño                                              |
| ------- | ------- | --------------------------------------------------- |
| Mobile  | < 768px | Layout apilado, hero centrado, grids 1 columna      |
| Tablet  | 768px+  | Hero horizontal (row-reverse), links a la izquierda |
| Desktop | 1024px+ | Hero ampliado al 90%, imagen de perfil más grande   |

## Cómo ver el proyecto

No requiere instalación ni build. Abrir `index.html` directamente en el
navegador.

- Opción 1: Abrir el archivo localmente
- Opción 2: [Ver en GitHub Pages](https://14bryanespinoza.github.io/landing-page/)

---

Bryan Espinoza — 2026
