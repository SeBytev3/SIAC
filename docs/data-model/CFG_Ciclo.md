# CFG_Ciclo

## Información general

**Nombre de la lista:** CFG_Ciclo

**Descripción:**
Almacena los ciclos de evaluación o gestión del sistema. Un ciclo representa un periodo de trabajo (por ejemplo, 2026–2028) sobre el cual se relacionarán las demás entidades.

---

## Campos

| Nombre | Tipo SharePoint | Obligatorio | Descripción |
|---------|-----------------|-------------|-------------|
| Title | Una línea de texto | Sí | Nombre del ciclo |
| Codigo | Una línea de texto | Sí | Código único del ciclo |
| Programa | Una línea de texto | Sí | Programa asociado |
| Proposito | Varias líneas de texto | No | Objetivo del ciclo |
| FechaInicio | Fecha y hora | Sí | Inicio del ciclo |
| FechaFin | Fecha y hora | Sí | Finalización del ciclo |
| Estado | Opción | Sí | Planeado, Activo, Cerrado |
| Activo | Sí/No | Sí | Indica el ciclo vigente |

---

## Relaciones

Esta lista será referenciada por:

- CFG_ModeloVersion
- CNA_Recomendacion
- MEJ_Oportunidad
- IND_Medicion
- DOC_Revision

---

## Observaciones

Solo debe existir un ciclo activo al mismo tiempo.