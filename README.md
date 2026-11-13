# DormyTop Astro

Frontend estático de DormyTop construido con Astro.

## Desarrollo

```bash
npm install
npm run dev
npm run build
```

## Decap CMS

El panel está disponible en `/admin/` y su configuración vive en `public/admin/config.yml`.

Los datos visuales se editan desde Decap y se guardan en Git:

- `src/data/site.json`: banners, promociones, sección Quiénes somos, bento, sedes, logos y medios de pago.
- `src/data/products.json`: catálogo visual y productos destacados.

Para probar Decap de forma local, instala y ejecuta su proxy:

```bash
npx decap-server
```

Para producción con GitHub se debe configurar OAuth y añadir `base_url` y `auth_endpoint` bajo `backend` en `public/admin/config.yml`. No se debe guardar ningún secreto en este repositorio.
