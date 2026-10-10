# Dashboard DSS — Análisis de Ventas Zara

Sistema de Soporte a Decisiones (sitio estático) para analizar 252 productos de Zara por categoría, sección (hombre/mujer), precio, promoción y posición en tienda.

- **Sitio publicado:** _(pega aquí la liga de GitHub Pages)_
- **Fuente de los datos:** dataset de ventas de Zara en Kaggle (`zara.csv`). Autor, liga y fecha de descarga: _(completar)_
- **Tecnologías:** HTML5, CSS3, JavaScript y Chart.js.
- **Integrantes:** _(agrega aquí los nombres)_

## Archivos
- `index.html`: dashboard completo. Incluye los datos procesados dentro del archivo, por eso funciona al abrirlo directamente y en GitHub Pages.
- `zara.csv`: archivo de datos original (separado por punto y coma), incluido como respaldo de la fuente.
- `README.md`: este archivo.

## Notas sobre los datos
- 252 filas y 16 columnas; los datos se tomaron el 19 de febrero de 2024 (una sola fecha), por lo que no hay evolución en el tiempo.
- El **ingreso estimado** se calcula como precio (USD) × volumen de ventas.
- Hay 24 SKU y URL repetidos entre productos con distinto ID, nombre y volumen; se conservaron porque el ID de producto es único.
- 2 filas sin descripción y 1 sin nombre; se conservaron.

## Publicación
Settings → Pages → rama `main`, carpeta raíz. Sube los tres archivos a la raíz del repositorio.
