# Arquitectura funcional de SIAC

## Módulos

### CFG - Configuración

Administra los parámetros generales del sistema.

Entidades:

- CFG_Ciclo
- CFG_ModeloVersion
- CFG_Equivalencia

---

### SEC - Seguridad

Controla la asignación de responsables.

Entidades:

- SEC_Asignacion

---

### CNA - Recomendaciones

Gestiona las recomendaciones generadas durante el proceso.

Entidades:

- CNA_Recomendacion

---

### MEJ - Mejoramiento

Gestiona oportunidades, intervenciones y actividades.

Entidades:

- MEJ_Oportunidad
- MEJ_Intervencion
- MEJ_Actividad

---

### IND - Indicadores

Gestiona indicadores y sus mediciones.

Entidades:

- IND_Definicion
- IND_Medicion

---

### DOC - Documentación

Gestiona solicitudes, evidencias, relaciones y revisiones.

Entidades:

- DOC_Solicitud
- DOC_Evidencia
- DOC_Relacion
- DOC_Revision

---

### EVA - Evaluación

Gestiona narrativas de evaluación.

Entidad:

- EVA_Narrativa

---

### GOB - Gobierno

Gestiona decisiones.

Entidad:

- GOB_Decision

---

### ALR - Alertas

Gestiona alertas del sistema.

Entidad:

- ALR_Alerta

---

### RPT - Reportes

Gestiona perfiles y cortes de reportes.

Entidades:

- RPT_Perfil
- RPT_Corte

---

### AUD - Auditoría

Registra eventos relevantes del sistema.

Entidad:

- AUD_Evento