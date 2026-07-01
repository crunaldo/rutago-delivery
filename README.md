# RutaGo Delivery Ops

Aplicación web estática para gestionar pedidos, POS, InDrive, clientes, catálogo, reportes, caja y ajustes.

## Publicación en GitHub Pages

Este directorio está listo para publicarse como sitio estático. El archivo principal es `index.html`.

Pasos recomendados:

1. Crear un repositorio en GitHub.
2. Subir el contenido de esta carpeta a la rama `main`.
3. Activar GitHub Pages desde `Settings > Pages`.
4. Seleccionar `Deploy from a branch`, rama `main`, carpeta `/root`.
5. Copiar la URL publicada, por ejemplo `https://usuario.github.io/rutago-delivery/`.

## Supabase Auth

Cuando GitHub Pages entregue la URL final:

1. Ir a `Supabase > Authentication > URL Configuration`.
2. Poner esa URL como `Site URL`.
3. Agregar también esa URL en `Redirect URLs`.
4. Si se usa una ruta específica, agregar la variante con `index.html`.

Esto evita errores de confirmación de correo causados por `file://` o `localhost`.
