# RFM Dinamico DOC ROI

Aplicacion web DOC ROI para diagnosticar RFM dinamico, segmentacion por comportamiento de cliente, activacion comercial y fidelizacion economica.

## Que incluye

- Hero y ruta guiada con identidad visual DOC ROI.
- Laboratorio por pestanas: datos, periodos, scoring, segmentos, optico marketing, calculo, cuadro de mando y CSV.
- Carga CSV, pegado desde Excel/Sheets, ejemplo docente y plantilla descargable.
- Configuracion de cortes temporales en meses, pesos R/F/M, matriz de scoring por percentiles, matriz de segmentos y presupuesto de activacion.
- Calculo en navegador de RFM por dos periodos, delta, segmento, movimiento y tratamiento.
- Cuadro de mando imprimible con KPIs, distribucion de segmentos y matriz de migracion.
- CSV operativo con acciones recomendadas para cargar en CRM, automatizacion o Excel.

## Campos de entrada

El CSV o tabla pegada debe incluir:

- `customer_id`
- `order_id`
- `date`
- `amount`

Tambien se aceptan equivalentes en espanol como `cliente`, `fecha` e `importe`.

## Publicar en Vercel

Proyecto estatico. En Vercel importa este repositorio y usa:

- Framework Preset: Other
- Build Command: vacio
- Output Directory: `.`
