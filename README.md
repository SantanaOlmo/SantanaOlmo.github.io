# Origen HTTPS (Play / TWA) — estud.io

Sitio público en la **raíz** de `https://santanaolmo.github.io/`.

| Ruta | Rol |
| --- | --- |
| `/` | Landing mínima → enlace a la PWA |
| `/privacidad/` | Política de privacidad (Play / Ajustes) |
| `/eliminar-cuenta/` | Borrado de cuenta (exigencia Play; enlaza a la PWA) |
| `/.well-known/assetlinks.json` | Digital Asset Links (Chrome ↔ app `io.estud.app`) |
| `/stud.io_Distribution/` | PWA (otro repo: `stud.io_Distribution`) |

Fuente de verdad en el repo privado: carpeta `play-host/`.
Las huellas se generan con `npm run android:sync-assetlinks` (no editar a mano).

No tocar este repo a mano salvo emergencia; publicar desde `stud.io` con el
workflow *Publish play host*.
