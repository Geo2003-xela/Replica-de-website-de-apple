# Réplica Visual - Landing Page de Apple
**Curso:** Fundamentos de desarrollo y estilo web
**Estudiante:** Edwin Geovanni Hernandez Santizo  
**Referencia:** [Apple Latinoamérica](https://www.apple.com/la/)

## Secciones Replicadas
1. Barra de navegación superior (TechNova Navbar).
2. Hero principal oscuro (Presentación de Evento).
3. Sección destacada del producto Phone 17 Pro.
4. Sección destacada de Laptop Air.
5. Cuadrícula (Grid) de 4 productos secundarios.
6. Banner promocional estático (Simulación de Carrusel).
7. Notas legales con texto reducido.
8. Footer dividido en múltiples columnas de navegación.

## Conceptos HTML Utilizados
* **HTML5 Semántico:** Implementación estricta de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, y `<footer>` para estructurar de manera óptima el documento.
* **Contenido:** Enlaces (`<a>`), listas (`<ul>`, `<li>`), e imágenes estructuradas localmente.

## Conceptos CSS Utilizados
* **Box Model:** Control de márgenes, rellenos y reseteo global mediante `box-sizing: border-box`.
* **Flexbox:** Aplicado principalmente en el `.navbar` para distribuir horizontalmente el logotipo, los enlaces de navegación y la barra de búsqueda, así como en las columnas del footer antes del breakpoint.
* **CSS Grid:** Utilizado en la sección `.products-grid` para forzar un diseño exacto de 2 columnas en pantallas grandes (`repeat(2, 1fr)`).
* **Responsive Design:** Implementación de `@media (max-width: 768px)` para alternar la cuadrícula de productos a 1 columna y reordenar las columnas del footer verticalmente, eliminando desbordamientos horizontales.

## Dificultades Encontradas
* *Maquetar el pie de página de forma flexible sin usar librerías externas.*
* *Alineación exacta de imágenes de fondo y posicionamiento de textos encima de los banners mediante propiedades relativas y absolutas.*
* *Encontrar la localidad de las imagenes, al principio me tiraba error porque no se habian guardado correctamente las imagenes, luego el live server no encontraba la localidad de las imagenes pero finalmente lo pude resolver"
