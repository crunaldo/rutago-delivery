# RutaGo Delivery Ops

Aplicacion web estatica para gestionar pedidos, POS, InDrive, clientes, catalogo, reportes, caja y ajustes.

## Publicacion en GitHub Pages

Este directorio esta listo para publicarse como sitio estatico. El archivo principal es `index.html`.

Pasos recomendados:

1. Activar GitHub Pages desde `Settings > Pages`.
2. Seleccionar `Deploy from a branch`, rama `main`, carpeta `/root`.
3. Copiar la URL publicada, por ejemplo `https://crunaldo.github.io/rutago-delivery/`.

## Supabase Auth

Cuando GitHub Pages entregue la URL final:

1. Ir a `Supabase > Authentication > URL Configuration`.
2. Poner esa URL como `Site URL`.
3. Agregar tambien esa URL en `Redirect URLs`.
4. Agregar tambien la variante con `index.html` si se usa directamente.

Esto evita errores de confirmacion de correo causados por `file://` o `localhost`.
