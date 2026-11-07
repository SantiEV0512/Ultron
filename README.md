# Dawncore AI Phone — ULTRÓN 0.9.1

Release candidate del proyecto ULTRÓN para Android 6.0+ (minSdk 23).

## Estado

- Código fuente y documentación de la versión 0.9.1.
- La APK todavía requiere compilación y pruebas en el LG Android 6.
- No se incluyen claves API ni credenciales privadas.

## Funciones y configuración

Consulta `docs/SETUP_0.9.1.md` para configurar WhatsApp Business Cloud API, Gmail OAuth, Groq, Fish Audio y Cloudflare Worker. Las credenciales deben guardarse como secretos del Worker; nunca dentro del APK ni del repositorio.

## Seguridad

- El LLM se trata como entrada no confiable y no puede autorizar acciones ni cambiar RED LINE.
- Evolution Lab genera propuestas acotadas; no ejecuta código ni modifica la app instalada.
- RED LINE bloquea dentro de ULTRÓN, no todo Android.
- El desbloqueo remoto no omite el PIN local.

## Compilación y pruebas

El workflow de GitHub Actions permite solicitar una compilación debug. Ejecuta también las pruebas del Worker desde `cloudflare/` con `npm test`. No consideres esta versión lista para uso crítico hasta que CI y las pruebas físicas en el LG terminen correctamente.
