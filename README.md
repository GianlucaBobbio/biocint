# biocint

Sitio de [biocint.com](https://biocint.com): GitHub Pages desde `master` (raíz), dominio en `CNAME`.

- `index.html`: la página (diseño "combineta", origen en `biocint-exp/designs/11-combineta.html`).
- `js/products.js`: número de WhatsApp (`WHATSAPP_NUMBER`) y helpers compartidos.
- Catálogo: se carga en vivo desde la Google Sheet publicada como CSV (`SPREADSHEET_CSV_URL` en `index.html`). La columna `imagen` acepta `assets/...` o una URL absoluta; se guarda la última versión en el navegador (`localStorage`) y el listado de respaldo del HTML solo aparece si la planilla no carga.
- `images/`: imágenes del sitio anterior, se mantienen porque esas URLs pueden estar indexadas.
- SEO: `robots.txt`, `sitemap.xml`, meta/OG/JSON-LD en el `<head>`, Google Analytics `G-5MLH0P29QC`. Search Console se verifica por DNS (TXT).
