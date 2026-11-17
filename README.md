# KOVEX POS 1.0.3 — instalador de distribución

Este repositorio contiene únicamente el instalador de **KOVEX POS 1.0.3** para Windows (x64).
No contiene código fuente.

## Descarga

Descarga el instalador desde la sección **Releases** (versión `v1.0.3`).

| Archivo | SHA-256 |
|---|---|
| `Lesly Miranda POS Setup 1.0.3.exe` | `8d118559048c383837e721b68e0309086f7d7779cfa8adbdb30d13bce0fd58cf` |

Verifica el archivo antes de instalarlo, en PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 ".\Lesly Miranda POS Setup 1.0.3.exe"
```

El valor debe coincidir exactamente con el de la tabla.

## Notas

- El instalador **no tiene firma digital**; Windows SmartScreen puede mostrar un aviso. Instálalo sólo cuando el responsable de la boutique lo indique.
- Esta versión incluye los iconos Lucide y los campos de escaneo mejorados.
- La instalación no debe hacerse en horario de venta ni antes del Fin de día.
