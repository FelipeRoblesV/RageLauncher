# RageLauncher Remote Config

Este repositorio se usa como fuente remota para el launcher.

## Archivo principal

- `launcher-content.json`: controla version, textos, imagen, noticias, mantenimiento y datos del modpack.

## Flujo

1. Edita `launcher-content.json`.
2. Haz commit a `main`.
3. El launcher descargara los cambios automaticamente.

## Update

El launcher compara `version` contra su version local.
Si cambias ese valor, mostrara el aviso de update y abrira `downloadUrl`.
