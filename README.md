# politicas-de-privacidad

Repositorio de políticas de privacidad de todas las apps, publicado con
GitHub Pages. Cada app tiene su propia carpeta con una política específica
(Google Play exige que la política aplique específicamente a la app).

## Estructura

```
_template.md          plantilla base (no se publica)
index.md              listado de apps
<app>/index.md        política en español (URL principal)
<app>/en.md           política en inglés
```

URL resultante: `https://<usuario>.github.io/politicas-de-privacidad/<app>/`

## Publicar

1. Crear el repo público `politicas-de-privacidad` en GitHub y hacer push.
2. Settings > Pages > Source: `Deploy from a branch`, rama `main`, carpeta `/ (root)`.
3. Esperar el build y abrir la URL en una ventana privada (sin login) para comprobar que es pública.
4. Pegar la URL en Play Console > Policy > App content > Privacy policy, y en la pantalla de Ajustes de la app.

## Nueva app

1. Copiar `_template.md` a `<app>/index.md` (y `<app>/en.md`).
2. Completar cada sección con lo que la app hace **realmente**: revisar el
   `AndroidManifest.xml` (permisos), los SDKs instalados (analítica, ads,
   crash reporting) y si hay servidor o cuentas.
3. Verificar que coincida con el formulario *Data safety* de Play Console.
4. Agregar la app a `index.md`.

## Al cambiar una app

Si la app agrega un permiso, un SDK o empieza a usar la red, actualizar su
política **antes** de publicar esa versión y cambiar la fecha de "Última actualización".
