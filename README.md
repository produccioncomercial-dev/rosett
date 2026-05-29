# Rossett Joyería de Plata

Página web estática para publicar un catálogo ecommerce de joyería de plata en GitHub Pages.

## Archivos importantes

- `index.html`: diseño, filtros, galería, detalle de producto y botón de WhatsApp.
- `404.html`: copia técnica de la página para que GitHub Pages pueda abrir enlaces directos como `/rosett/SKU`.
- `productosrosett.csv`: catálogo de productos. Puedes reemplazarlo todos los días con el mismo nombre.

## Cómo actualizar productos

1. Exporta tu CSV actualizado.
2. Renómbralo exactamente como `productosrosett.csv`.
3. Reemplaza el archivo anterior en la carpeta del sitio.
4. Sube el cambio a GitHub.

Solo se muestran productos con `Publicado` igual a `1`.

## Cómo subirlo a GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `productosrosett.csv` y este `README.md` a la raíz del repositorio.
3. En GitHub entra a `Settings` > `Pages`.
4. En `Build and deployment`, elige `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Guarda los cambios.

GitHub te mostrará una URL parecida a `https://tu-usuario.github.io/tu-repositorio/`.

En este proyecto, los productos se abren con enlaces del tipo `https://produccioncomercial-dev.github.io/rosett/SKU` y las páginas del catálogo con `/2`, `/3`, etc.
