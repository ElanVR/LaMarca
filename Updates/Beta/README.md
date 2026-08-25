# Canal Beta de Companion

Beta preparada actualmente:

- `versionName`: `2.0.0.0.1`
- `versionCode`: `20001`
- APK: `companion-2.0.0.0.1.apk`
- SHA-256: `757DD8EEDA838B3D7CFC537D81FAA870A88F73A847290F2A51B0C3F5BC898060`

Para publicar una Beta:

1. Usar un `versionCode` mayor que cualquier versión estable o Beta publicada.
2. Generar y firmar el APK release con la misma clave permanente.
3. Copiarlo aquí con nombre único, por ejemplo
   `companion-2.0.1-beta.1.apk`.
4. Calcular su SHA-256.
5. Actualizar este `latest.json` con versión, URL y hash correspondientes.
6. Subir primero el APK a `Updates/Beta/` y `latest.json` al final.

No usar `Updates/app-debug.apk` para distribuir versiones Beta.
