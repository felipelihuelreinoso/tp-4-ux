# Coffea — Landing Page

Landing page estática desarrollada con HTML5 semántico y CSS3, sin JavaScript ni frameworks.

## Cómo ejecutar
1. Descomprimir el proyecto.
2. Abrir la carpeta `coffea-landing` en Visual Studio Code.
3. Abrir `index.html` en el navegador (recomendado: extensión Live Server).

## Estructura
- `index.html`: estructura semántica de las 9 secciones.
- `css/`: tokens, estilos base, layout y componentes.
- `assets/img/`: fotografías reemplazables.
- `assets/icons/`: íconos SVG reemplazables.
- `404.html`: página de error.
- `netlify.toml`: configuración básica de despliegue.

## Recursos visuales pendientes
Buscar los comentarios `REEMPLAZAR` en `index.html` y `css/components/hero.css`.
Los nombres de archivo que espera el proyecto son:

### Imágenes (`assets/img/`)
- `hero.jpg`: fondo principal de espresso y granos.
- `coffee-1.jpg` a `coffee-4.jpg`: cuatro fotos diferentes de café.
- `dessert-1.jpg` a `dessert-4.jpg`: cuatro fotos diferentes de postres.
- `promo-hand.png`: mano con granos de café.
- `promo-beans.png`: granos de café dispersos.
- `newsletter-beans.png`: granos de café para los laterales del newsletter.
- `avatar-1.jpg` a `avatar-3.jpg`: tres avatares de clientes.

### Íconos (`assets/icons/`)
- `search.svg`: lupa del buscador.
- `cat-hot.svg`, `cat-cold.svg`, `cat-cup.svg`, `cat-dessert.svg`: cuatro íconos de categorías.
- `favicon.svg`: favicon de la pestaña.

**Importante:** reemplazar los archivos conservando exactamente estos nombres, o actualizar las rutas correspondientes en HTML/CSS. Usar imágenes propias o con licencia adecuada.

## Personalización recomendada
- Cambiar nombres, descripciones y precios de productos.
- Confirmar moneda: el PRD original utiliza `Rs. 200` como placeholder.
- Cambiar nombres, roles y textos de testimonios.
- Completar los enlaces del footer y redes sociales.
- Confirmar el idioma final del sitio. El contenido de esta versión está en inglés (`lang="en"`).

## Limitaciones intencionales
- No hay backend ni JavaScript.
- El formulario newsletter usa `action="#"`: valida el formato del email en el navegador, pero no guarda ni envía suscripciones.
- Los favoritos son visuales y no persisten.
- Los carruseles usan scroll horizontal nativo en pantallas pequeñas. Las flechas de escritorio son enlaces de ancla básicos.

## Despliegue en Netlify
Conectar el repositorio Git a Netlify. No se necesita build command; el directorio de publicación es `.`.
