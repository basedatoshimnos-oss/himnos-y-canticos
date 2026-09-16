# Verificación de entrega

Versión web basada en Himnos y Cánticos 1.2.22.

## Alcance verificado

- 150 entradas con letra integradas; 108 con audio, video y partitura.
- Cero identificadores duplicados en el catálogo.
- Carga correcta desde un servidor HTTP local, equivalente al alojamiento estático de GitHub Pages.
- Documento HTML y JavaScript con sintaxis válida.
- Manifest PWA válido y con rutas relativas.
- Service worker limitado al origen de GitHub Pages.
- Inicio directo en la pestaña Himnos.
- Catálogo incluido en el paquete, sin dependencia de una API para mostrar letras.
- Favoritos, guardados, recientes, preferencias y playlists protegidos frente a datos locales dañados o almacenamiento no disponible.
- Navegación por las cuatro pestañas.
- Reproducción, pausa, siguiente, anterior, aleatorio y repetición.
- Creación, renombrado, eliminación, orden y edición de playlists.
- Acción “añadir a playlist” desde Himnos y desde Escucha.
- Controles Media Session cuando el navegador los soporta.
- Partituras abiertas con el visor nativo en iPhone y con visor integrado/fallback en otros navegadores.
- Recursos de interfaz preparados para funcionamiento sin conexión; multimedia excluida de caché intencionalmente.
- Pruebas de lógica para búsqueda, recuperación frente a preferencias dañadas, creación de playlist desde Himnos y adición de elementos.

## Dependencias externas

Los MP3, MP4 y PDF siguen usando el servidor oficial Cloudflare R2. La disponibilidad de esos archivos depende de ese servicio y de la conexión del usuario.
