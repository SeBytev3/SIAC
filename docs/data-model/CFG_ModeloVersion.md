# CFG_ModeloVersion

## Descripción

Define las versiones del modelo de evaluación utilizadas por SIAC.

Cada versión pertenece a un ciclo.

---

## Lista SharePoint

CFG_ModeloVersion

---

## Campos

| Campo | Tipo |
|--------|------|
| Title | Texto |
| Codigo | Texto |
| Version | Texto |
| Descripcion | Texto multilínea |
| FechaPublicacion | Fecha |
| Estado | Opción |
| Ciclo | Lookup → CFG_Ciclo |

---

## Reglas

- Cada versión pertenece a un único ciclo.
- Solo puede existir una versión activa por ciclo.

---

## Consumido por

- Power Apps
- Power Automate
- Power BI