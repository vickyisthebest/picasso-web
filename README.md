# picasso-web

Static assets loaded by the BedLoop website through Configuración > Web > CSS personalizado.

| File | Purpose | Live URL after GitHub Pages is on |
|---|---|---|
| css/picasso-mobile-v1.css | Mobile booking bar, licence number wrap, header overflow fix | https://<account>.github.io/picasso-web/css/picasso-mobile-v1.css |

## Release rules
1. Never edit a released file. Add a new version (v2, v3) so the URL in BedLoop only changes on purpose.
2. Rollback: put the previous URL back in CSS personalizado, or clear the field.
3. Every release is tested at 390px and 1366px on the homepage, Picasso Suites 1.1, 1.4 and Begur before the BedLoop field is changed.
