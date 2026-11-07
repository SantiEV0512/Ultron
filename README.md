# Dawncore AI Phone — ULTRÓN 0.9.1

Repositorio de trabajo para ULTRÓN.

## Estado de publicación

El paquete `Dawncore-AI-Phone-0.9.1-RELEASE-CANDIDATE.zip` ya está cargado en esta rama de GitHub.

- [Descargar el paquete 0.9.1](./Dawncore-AI-Phone-0.9.1-RELEASE-CANDIDATE.zip)
- [Consultar el checksum SHA-256](./Dawncore-AI-Phone-0.9.1-SHA256.txt)

La presencia del ZIP confirma la carga del archivo, pero no demuestra por sí sola que el proyecto compile o que sus funciones estén verificadas.

## Pendiente antes de considerarlo estable

- Compilar la aplicación Android.
- Ejecutar las pruebas automatizadas del Worker.
- Probar el flujo principal y RED LINE en el LG con Android 6 (API 23).
- Validar la configuración real de WhatsApp Business Cloud API y Gmail OAuth.
- Verificar el almacenamiento de secretos: no incluir claves API, tokens ni credenciales en el APK ni en Git.

## Seguridad y limitaciones

- RED LINE bloquea acciones dentro de ULTRÓN; no garantiza el bloqueo completo del sistema Android.
- La evolución de código debe permanecer aislada, revisada y sujeta a aprobación antes de llegar a producción.
- No instalar una APK candidata en el teléfono principal sin revisar primero permisos, configuración y pruebas.

Consulta `docs/SETUP_0.9.1.md` cuando se vaya a configurar el entorno.