# Repositorio de Comprensión Lectora · 2.º grado de primaria

> **Importante sobre esta versión:** los nombres técnicos de imágenes, videos y PDF usan rutas sin tildes, eñes, espacios ni símbolos para evitar incompatibilidades de codificación. Los títulos que aparecen en la página siguen escritos correctamente en español. Al actualizar, sube la carpeta `assets/`, la carpeta `recursos/` y `index.html` juntos.


Sitio web estático, pensado para abrirse en computador, tableta o teléfono. Incluye lecturas en PDF, talleres, videos con miniaturas, búsqueda por texto y favoritos guardados en el navegador.

## Contenido

- **Lectura literal:** cinco lecturas y sus cinco talleres.
- **Lectura inferencial:** cinco lecturas y sus cinco talleres.
- **Videos:** siete recursos audiovisuales con miniaturas personalizadas.
- **Favoritos:** se guardan localmente en el navegador/dispositivo donde se seleccionan.
- **Búsqueda:** por título, personaje o tema.

## Publicarlo en GitHub Pages

1. Descomprime el archivo ZIP.
2. Abre la carpeta `repositorio-comprension-lectora`.
3. Sube **el contenido de esa carpeta** a la raíz del repositorio de GitHub. El archivo `index.html` debe quedar en la raíz; no dejes una carpeta adicional envolviéndolo.
4. En GitHub, entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, la rama principal (normalmente `main`) y la carpeta **`/ (root)`**; guarda los cambios.
6. Espera a que GitHub Pages indique que el sitio está publicado y abre la URL que proporciona.

El archivo `.nojekyll` incluido evita que GitHub Pages procese los archivos como un sitio Jekyll. Las rutas de los recursos son relativas, por lo que funcionan tanto en la raíz de un dominio como en un repositorio publicado bajo una subruta.

## Antes de publicar

- Conserva la estructura `assets/` y `recursos/`; el HTML utiliza esas rutas.
- No cambies los nombres de los PDF, videos ni miniaturas sin actualizar las rutas del catálogo en `index.html`.
- Si sustituyes un video, revisa también su miniatura y la duración que muestra la tarjeta.
- Prueba el sitio publicado en computador y teléfono, abre al menos una lectura, un taller y cada video, y comprueba que la búsqueda y los favoritos funcionan.

## Datos locales

Los favoritos se guardan en el almacenamiento local del navegador. No se sincronizan automáticamente entre dispositivos ni entre navegadores. Los PDF y videos se sirven como archivos estáticos del mismo repositorio.
