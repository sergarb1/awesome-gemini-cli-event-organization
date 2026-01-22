# Contexto del Proyecto: Gestión de Eventos 360

Este repositorio contiene la configuración para organizar cualquier tipo de evento:
- **Educativos:** Días especiales de colegio (Día de la Paz, Carnaval, Jornadas Culturales), festivales de fin de curso, graduaciones.
- **Profesionales:** Presentaciones de libros, congresos, ferias comerciales, lanzamientos de productos.
- **Sociales:** Bodas, cenas de gala, cumpleaños de amigos, despedidas, saraos.
- **Comunitarios:** Fiestas locales, eventos deportivos, jornadas de puertas abiertas.

Utiliza múltiples agentes especializados para gestionar cada aspecto.

**IMPORTANTE:** Las instrucciones detalladas para cada agente se encuentran en el directorio `agentes_feria_ies/` (aunque el nombre sea heredado, el contenido es para eventos generales).

## Regla Global de Tecnología
Para cualquier salida de código relacionada con la web (landing pages, cuadrantes, encuestas, memoria), DEBES utilizar estrictamente:
- **Framework:** Vue.js 3 (vía CDN para máxima portabilidad).
- **Estilos:** Tailwind CSS (vía CDN).
- **Arquitectura:** Archivos HTML independientes y autogestionados, sin necesidad de servidor o compilación.

---

## Índice de Agentes

| ID | Agente | Archivo de Referencia | Rol Principal |
| :--- | :--- | :--- | :--- |
| **01** | Coordinador | `agentes_feria_ies/01_coordinador.md` | Dirección general y gestión de conflictos. |
| **02** | R. Institucionales | `agentes_feria_ies/02_relaciones_institucionales.md` | Embajador ante autoridades. |
| **03** | Escritores | `agentes_feria_ies/03_escritores_actividades.md` | Programación cultural. |
| **04** | Cuentacuentos | `agentes_feria_ies/04_cuentacuentos.md` | Dinamización lectora (Infantil/Primaria). |
| **05** | Stands/Logística | `agentes_feria_ies/05_logistica_stands.md` | Espacio físico y montaje. |
| **06** | Comunicación | `agentes_feria_ies/06_comunicacion.md` | Redes sociales y prensa. |
| **07** | Protocolo | `agentes_feria_ies/07_protocolo.md` | Atención a VIPs. |
| **08** | Económico | `agentes_feria_ies/08_economia.md` | Presupuesto y compras. |
| **09** | Educativo | `agentes_feria_ies/09_educativo.md` | Integración curricular. |
| **10** | Evaluación | `agentes_feria_ies/10_evaluacion.md` | Encuestas y memoria de datos. |
| **11** | Cuadrantes | `agentes_feria_ies/11_cuadrantes_profesorado.md` | RRHH Profesorado (Tablas SvelteKit). |
| **12** | Grupos | `agentes_feria_ies/12_gestion_grupos.md` | Flujo de alumnado (SvelteKit). |
| **13** | Encuestas Web | `agentes_feria_ies/13_encuestas_web.md` | Feedback digital (SvelteKit). |
| **14** | Estética/UX | `agentes_feria_ies/14_estetica_ux.md` | Identidad visual (UnoCSS). |
| **15** | Ideas Locas | `agentes_feria_ies/15_ideas_innovadoras.md` | Innovación disruptiva. |
| **16** | Arquitectura Web | `agentes_feria_ies/16_arquitectura_web.md` | Estructura SvelteKit + Layouts. |
| **17** | Memoria Web | `agentes_feria_ies/17_memoria_web.md` | Web resumen post-evento. |