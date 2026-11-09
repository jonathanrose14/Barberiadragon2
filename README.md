# Dragon Barber Club

Sitio web de una barbería, desarrollado como proyecto final del curso de desarrollo web en Coderhouse.

## 🔗 Sitio desplegado
https://barberiadragon2.vercel.app/

## Páginas
- **Inicio**: banner, mapa, cortes destacados, galería con carousel, video y newsletter
- **Menú**: servicios de la barbería
- **Ofertas**: promociones en tarjetas
- **Nosotros**: información de la barbería
- **Contacto**: datos y formulario de contacto

## Tecnologías
- HTML5 semántico
- CSS3 (Grid, Flexbox y media queries)
- SCSS (variables, nesting, mixins, extend y partials)
- Bootstrap 5.3
- AOS (animaciones al hacer scroll)
- Git y GitHub
- Vercel (deploy)

## Características
- Diseño responsive (mobile, tablet y desktop)
- Navbar de Bootstrap con menú hamburguesa
- Paleta negra, dorada y blanca con tipografías propias (Google Fonts)
- Estados interactivos con `:hover`, `:focus` y `:active`
- SEO on-page: títulos, meta description, meta keywords, encabezados con keywords e imágenes con nombres descriptivos
- Accesibilidad: textos alternativos y contraste AA

## Estructura
- `index.html` en la raíz y las otras 4 páginas en `pages/`
- `scss/`: estilos en SCSS (`main.scss` solo importa los partials con `@use`)
- `styles/`: CSS compilado
- `assets/`: imágenes e íconos

## Cómo ejecutarlo en local
1. Clonar el repositorio: `git clone https://github.com/jonathanrose14/Barberiadragon2.git`
2. Abrir la carpeta en VS Code
3. Abrir `index.html` con Live Server
4. Para recompilar los estilos: `npm run sass`

## Autor
[Jonathan Lepez] - [@jonathanrose14](https://github.com/jonathanrose14)
