# Notify and Tag Custom Action

Composite Action para estandarizar releases generando tags semánticos, release notes y alertas de notificación.

## Inputs
- `version` (Obligatorio): Versión semántica del release (ej. `1.0.0`).
- `environment` (Opcional): Entorno destino (`staging`, `production`). Default: `staging`.
- `webhook_url` (Opcional): URL de webhook para notificación.
- `create_tag` (Opcional): Si debe crear el tag git. Default: `true`.

## Outputs
- `tag_name`: Nombre del tag generado.
- `release_notes`: Ruta del archivo generado con las notas del release.