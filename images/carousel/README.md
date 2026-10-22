# Carpeta para Imágenes del Carrusel

Coloca aquí las imágenes que deseas que aparezcan en el Carrusel del Hero Banner.

## Archivos actuales:
- `banner-hero.jpg` (Imagen principal inicial de la campaña "MIRA LO MEJOR - Copa Libertadores")

## Cómo agregar más imágenes:
1. Copia tu nueva imagen en esta carpeta (`public/images/carousel/`).
   Por ejemplo: `public/images/carousel/mi-nueva-imagen.jpg`
2. Abre el archivo `src/data/carouselSlides.js`.
3. Agrega un nuevo elemento al array `CAROUSEL_SLIDES` con la ruta de tu imagen:
   ```javascript
   {
     id: 'slide-2',
     image: '/images/carousel/mi-nueva-imagen.jpg',
     alt: 'Descripción de la imagen',
     title: 'MIRA LO MEJOR',
     subtitle: 'Vive la Final en Montevideo',
     badge: 'TCL & Dismac'
   }
   ```
4. Guarda el archivo y el carrusel mostrará automáticamente las diapositivas con transiciones suaves, controles de navegación y temporizador automático.
