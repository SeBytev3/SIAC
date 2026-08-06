# SIAC - Sistema Integral de Administración y Control

## Objetivo

SIAC es una solución desarrollada sobre Microsoft 365 para centralizar la gestión documental y los procesos internos de la organización.

La solución estará basada en:

- SharePoint Online
- Power Apps
- Power Automate
- Power BI
- Microsoft Teams

El objetivo es eliminar procesos manuales, reducir el uso de archivos de Excel como fuente principal de información y disponer de un sistema centralizado, seguro y fácil de mantener.

---

## Alcance

La primera versión incluirá:

- Gestión documental.
- Solicitudes internas.
- Flujos de aprobación.
- Control de estados.
- Notificaciones automáticas.
- Paneles de indicadores.
- Integración con Microsoft Teams.

---

## Principios del proyecto

- Simplicidad antes que complejidad.
- Todo debe poder mantenerse por una sola persona.
- Evitar desarrollos innecesarios.
- Reutilizar componentes cuando sea posible.
- Mantener una estructura organizada y documentada.

---

## Arquitectura

SharePoint será el repositorio principal de datos.

Power Apps será la interfaz para los usuarios.

Power Automate automatizará los procesos.

Power BI mostrará los indicadores.

Teams será el punto de acceso para los usuarios.

---

## Metodología

El desarrollo será incremental.

Cada funcionalidad deberá quedar terminada antes de iniciar la siguiente.

La rama de desarrollo será siempre:

dev

La rama main se utilizará únicamente para versiones estables.