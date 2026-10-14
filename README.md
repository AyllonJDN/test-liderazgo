# Test de Liderazgo · Wendy Wünder

Autodiagnóstico interactivo de 20 preguntas en 4 bloques (Conócete, Da claridad, Escucha, Haz crecer a tu gente).
Al cerrar cada bloque muestra el porcentaje; al final, el puntaje total, el perfil y un plan de 30 días que empieza por el bloque más bajo.

Es un sitio estático (HTML, CSS y JavaScript sin dependencias). Las respuestas se guardan solo en el navegador de cada persona.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `test-liderazgo`).
2. Sube **el contenido** de esta carpeta (`index.html`, `assets/`, `.nojekyll`, `README.md`) a la raíz del repositorio.
   - Desde la web: *Add file → Upload files*, arrastra todo y confirma con *Commit changes*.
3. Ve a *Settings → Pages*. En *Build and deployment* elige *Deploy from a branch*, rama `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/test-liderazgo/`.

## Editar contenido

- Preguntas, acciones del plan y textos de cada bloque: arreglo `BLOCKS` dentro de `index.html`.
- Rangos y mensajes: funciones `level()` (por bloque) y `PROFILES` (total).
- Colores y tipografías: variables CSS en `:root` al inicio del `<style>`.
- Contacto: sección `.cta` (Instagram y correos).

## Estructura

```
index.html            página completa (estilos y lógica incluidos)
assets/               logos, isotipo, destello y fotos de Wendy (WebP con transparencia)
.nojekyll             evita que GitHub Pages procese el sitio con Jekyll
```
