# disaster-launcher (canal de actualizaciones del mod TD2DR Amy Canon + Sonic)

Este repositorio es el **canal de actualizaciones** del mod.
El launcher parcheado del mod consulta aqui:

- `releases/latest` -> ultima version del juego + servidor
- `changelog.txt` (rama main) -> novedades que se muestran en el launcher

## Como se actualiza el mod (automatico)

1. Se exporta el juego desde GameMaker y se compila el servidor.
2. Se corre `publicar.ps1 -Notas "..."` (arma los zips, elige la version
   siguiente solo, publica el release y el changelog).

Los jugadores solo abren su launcher y este descarga todo solo.

## Reglas del launcher

- El release debe estar **publicado** (no vale draft ni prerelease).
- El tag tiene que ser DISTINTO al de la version anterior.
- Los nombres de los assets deben contener `DisasterWin` y `BetterServerWin`.

---
Basado en el Disaster Launcher original de Team Exe Empire (MIT).
Mod: Amy Canon + Sonic por AmyRose21.
