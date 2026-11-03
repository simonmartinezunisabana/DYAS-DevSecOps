# Changelog

Registro de los cambios de cada versión publicada de la API de reservas de salas de estudio.

## [1.1.0] - 2026-11-02

### Agregado
- `integrantes.txt` con los datos del equipo.
- Despliegue continuo con GitHub Actions: publicación de la imagen en GHCR (etiquetas de versión y `sha-<commit>`), verificación de la firma, despliegue en el runner autohospedado, prueba de humo y verificación del SLO con k6.
- Protección de `main` con un ruleset: Pull Request, una aprobación y los cinco checks de CI obligatorios.

### Cambiado
- Versión del proyecto: `1.0.0` → `1.1.0`.

## [1.0.0]

- Versión base del taller: API de reservas con arquitectura hexagonal, pruebas, reglas de ArchUnit y controles de seguridad (SAST, SCA, secretos e imagen).
