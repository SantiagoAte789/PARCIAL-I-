# PARCIAL-I-
# CV Web — Santiago Atehortua Jaramillo

Hoja de vida (CV) web personal, desarrollada como parcial práctico para la asignatura
**Programación en Ambiente Web I** — Unidad Central del Valle del Cauca (Uceva).

## Descripción

Sitio web de una sola página que presenta el perfil profesional de Santiago Atehortua
Jaramillo, estudiante de Ingeniería de Sistemas y Tecnólogo en Análisis y Desarrollo de
Software. Incluye las secciones solicitadas en el enunciado del parcial: información
personal, perfil profesional, formación académica, experiencia, habilidades, proyectos,
cursos/certificaciones y contacto.

## Tecnologías utilizadas

Únicamente las exigidas por el enunciado del parcial:

- **HTML5** — estructura semántica del contenido (`header`, `nav`, `main`, `section`,
  `article`, `aside`, `footer`).
- **CSS3** — estilos personalizados y diseño responsive (`css/styles.css`).
- **PicoCSS** (vía CDN) — framework CSS base.



## Secciones obligatorias cubiertas

| Sección del enunciado   | Ubicación en `index.html` |
|--------------------------|----------------------------|
| Información personal     | `#inicio` |
| Perfil profesional       | `#perfil` |
| Formación académica      | `#formacion` |
| Experiencia              | `#experiencia` |
| Habilidades              | `#habilidades` |
| Proyectos                | `#proyectos` |
| Cursos y certificaciones | `#cursos` |
| Contacto                 | `#contacto` |

## Características técnicas

- Etiquetas HTML5 semánticas y jerarquía de encabezados correcta (`h1` → `h2` → `h3`).
- Navegación fija (sticky) con menú responsive tipo hamburguesa, resuelto **solo con
  CSS** (técnica de checkbox oculto + `:checked`).
- Diseño responsive probado en anchos de escritorio, tablet y celular mediante media
  queries en `css/styles.css` (puntos de quiebre en 860px, 720px y 480px).
- Formulario de contacto (`#contacto`) construido solo con HTML: usa
  `action="mailto:..."` para abrir el cliente de correo del usuario con el mensaje ya
  redactado. 





## Autor

**Santiago Atehortua Jaramillo**
Estudiante de Ingeniería de Sistemas — Uceva, Tuluá, Colombia



