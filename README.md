# BookBridge — descargas oficiales

Plugin para copiar libros y su estructura de carpetas entre Kindle y Android con KOReader, sin sincronizar progreso ni anotaciones.

**[Descargar la última versión](https://github.com/albert-ice/BookBridge-releases/releases/latest/download/BookBridge.zip)**

## Primera instalación

1. Descarga `BookBridge.zip`.
2. Extrae `bookbridge.koplugin` dentro de `koreader/plugins/` en **ambos dispositivos**.
3. Reinicia KOReader.

En las siguientes versiones: **Herramientas → BookBridge → Buscar actualizaciones → Descargar e instalar**. Reinicia KOReader al terminar. No necesitas iniciar sesión en GitHub. Las versiones anteriores sin este menú necesitan instalar este ZIP una vez.

La copia de libros usa la red local; buscar actualizaciones requiere conexión a Internet. El actualizador cambia únicamente BookBridge, no KOReader. Detén las copias y el servidor antes de instalar. Se conserva una copia de la instalación anterior.

## Archivos de cada versión

- `BookBridge.zip`: instalación manual. Incluye el código fuente Lua legible y la licencia.
- `BookBridge-update.json`: paquete verificado que utiliza el actualizador integrado.
- `SHA256SUMS`: sumas de comprobación de los dos paquetes.

Este repositorio contiene las versiones descargables. El repositorio de trabajo permanece privado. El código distribuido en cada versión se publica bajo AGPL-3.0; consulta `LICENSE` dentro del ZIP. Los paquetes incluyen el código necesario para el plugin Lua y no requieren compilación.

Las pruebas automatizadas no sustituyen las comprobaciones específicas de permisos, suspensión y Wi-Fi en cada modelo de Kindle o Android.
