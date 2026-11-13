# DormyTop Astro

Frontend estático de DormyTop construido con Astro.

## Desarrollo

```bash
npm install
npm run dev
npm run build
```

## Sveltia CMS

El panel está disponible en `/admin/` y se configura en `public/admin/config.yml`.

- `src/data/site.json`: banners, promociones, Quiénes somos, bento, sedes, logos y medios de pago.
- `src/data/products.json`: catálogo visual y productos destacados.

En desarrollo abre `/admin/` con Chrome o Edge, pulsa **Work with Local Repository** y selecciona la raíz de este repositorio. Los cambios se guardarán en los archivos locales; revísalos y súbelos con Git.

Para edición remota en producción con GitHub hace falta OAuth: añade un autenticador y configura `base_url` y `auth_endpoint` dentro de `backend`. Los secretos nunca se guardan en el repositorio.
