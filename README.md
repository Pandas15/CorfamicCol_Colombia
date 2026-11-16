# CORFAMICOL · Corporación para las Familias de Colombia

Sitio oficial de convocatorias y contacto de la **Corporación para las Familias de Colombia (CORFAMICOL)**.

Publicado con GitHub Pages.

## Estructura

```
index.html                 Página de inicio (listado de convocatorias)
postulacion1.html          Convocatoria 1 — Aguachica (Cesar), Educación Inicial en el Hogar
logo_corfamicol.png        Logo oficial
documentos/                Formatos que descargan los aspirantes (.doc para firmar + .pdf para leer)
.nojekyll                  Evita el procesamiento de Jekyll en GitHub Pages
```

## Pendientes antes de publicar

Estos datos están como marcador y hay que reemplazarlos con los reales:

- `[[CORREO]]` — correo de contacto / postulaciones
- `[[TELEFONO]]` — teléfono
- `[[DIRECCION]]` — dirección

## Cómo se monta una convocatoria

Cuando haya una convocatoria (municipios, cargos, requisitos, fecha y hora de cierre y correo de
postulación), se crea `postulacionN.html` con el mismo diseño y se agrega la tarjeta en la sección
**Convocatorias** de `index.html`.
