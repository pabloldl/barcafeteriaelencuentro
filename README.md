# Bar Cafetería El Encuentro

Web estática en HTML, CSS y JavaScript. Abre `index.html` con Live Server. No necesita instalación ni compilación.

Solo se incluyen nombre, actividad y dirección confirmados. Las fotografías son ilustrativas y se identifican como tales. No hay carta, horarios ni datos de contacto no confirmados.

La página contiene una única etiqueta `noindex, nofollow`, que debe conservarse también en el repositorio. Repositorio: https://github.com/pabloldl/barcafeteriaelencuentro. La web no se ha desplegado.

## Recursos locales

Fotografías descargadas de Unsplash, optimizadas en WebP (calidad 80, anchos entre 1000 y 1800 px). Licencia de uso comercial: https://unsplash.com/license

| Archivo | Fuente original |
| --- | --- |
| `assets/mesa.webp` | https://images.unsplash.com/photo-1495474472287-4d71bcdd2085 |
| `assets/cafe.webp` | https://images.unsplash.com/photo-1442512595331-e89e73853f31 |
| `assets/espresso.webp` | https://images.unsplash.com/photo-1510707577719-ae7c14805e3a |
| `assets/barra.webp` | https://images.unsplash.com/photo-1445116572660-236099ec97a0 |

Estas fotografías no documentan el establecimiento ni su oferta. No se usan como testimonios de instalaciones o productos reales.

Tipografías locales: Fraunces (600) y DM Sans (400), bajo SIL Open Font License. Licencias conservadas en `assets/LICENSE-*.txt`. La web no realiza solicitudes externas hasta que el visitante abre Google Maps.

## Verificación realizada

Comprobada en Chrome headless a 375, 768, 1440 y 1920 px: sin desbordamiento horizontal; cuatro imágenes y ambas fuentes cargadas; enlaces internos con destinos existentes; los tres enlaces de Google Maps contienen la dirección confirmada; una sola etiqueta robots con `noindex, nofollow`; sin errores de JavaScript ni de carga. Se revisaron visualmente las capturas completas de 375 y 1440 px.

Comprobado también que la preferencia de movimiento reducido desactiva las animaciones y el desplazamiento suave, y que el contenido permanece visible con JavaScript desactivado. Sintaxis de JavaScript validada con `node --check`.

No se ha realizado una prueba en Safari o en un iPhone físico, ni se ha verificado de forma externa la ficha del negocio en Google Maps. Los enlaces buscan la dirección facilitada, sin inventar coordenadas.
