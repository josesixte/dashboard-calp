# Dashboard C.A.L.P. — Consumo de Energía

Dashboard de consumo de energía eléctrica de la Cooperativa de Agua y Luz Pinamar Ltda., a partir de los cuadros mensuales de EDEA S.A.

🔗 Publicado con GitHub Pages: se agrega el link acá una vez activado.

## Contenido

- `index.html` — dashboard (HTML + Chart.js, sin build, autocontenido).
- `COOP__PINAMAR_LTDA__0726.xls` — cuadro fuente de EDEA con los datos crudos.

## Actualizar datos

Cada mes, sumar una fila nueva al array `data` dentro de `index.html` (sección `<script>`) con los valores del cuadro de EDEA: energía Pico/Resto/Valle (kWh) y potencia registrada Pico/Resto/Valle (kW).

## Desarrollo local

Es un archivo HTML autocontenido — simplemente abrilo en el navegador. No requiere build ni dependencias instaladas.
