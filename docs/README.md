# OctoAcme – Documentación de Gestión de Proyectos

Bienvenido a la documentación centralizada de gestión de proyectos de OctoAcme. Este repositorio contiene los procesos, guías, roles y mejores prácticas que utilizamos para ejecutar proyectos de forma consistente, transparente y centrada en el cliente.

## Resumen de los Procesos de Gestión de Proyectos de OctoAcme

OctoAcme implementa un enfoque de gestión de proyectos **iterativo y centrado en el cliente** que abarca todo el ciclo de vida del proyecto, desde la iniciación hasta el cierre. El proceso comienza con la **iniciación del proyecto**, donde se valida la necesidad empresarial mediante un documento de una página (Project One-pager) que define el problema, los objetivos medibles y los criterios de éxito. Una vez aprobado por los líderes de producto y patrocinadores, el proyecto avanza a la **fase de planificación**, donde se crea un backlog priorizado con criterios de aceptación detallados, se estima el alcance utilizando T-shirt sizing o story points, y se establecen los hitos de entrega. Durante esta etapa se identifican explícitamente dependencias y riesgos, creándose un registro de riesgos que se revisa regularmente en las sincronizaciones semanales.

La **ejecución y seguimiento** se organizan en torno a un ritmo de trabajo estructurado que incluye standups diarios de 15 minutos, sincronizaciones de entrega semanales y demostraciones al final de cada sprint. El equipo utiliza tableros de proyectos (GitHub Projects) con flujos de trabajo claros: Backlog, Ready, In Progress, In Review, QA y Done. Las prácticas de calidad son rigurosas: se requieren pruebas unitarias e integrales, se mantiene un escaneo de seguridad en el CI, y se implementan PRs pequeños (≤ 400 líneas) con al menos una aprobación antes de la fusión. La **comunicación es multinivel**: sincronizaciones semanales PM-Product Lead, standups dos veces por semana para el equipo de entrega, y actualizaciones mensuales de stakeholders, con rutas de escalación definidas (nivel de equipo → PM → Product Lead → Patrocinador).

Al finalizar cada sprint o hito importante, OctoAcme realiza **retrospectivas estructuradas** que capturan lo que funcionó bien, áreas de mejora, y generan elementos de acción con propietarios y fechas límite claras. La **liberación a producción** sigue un proceso riguroso: se verifica que todos los criterios de aceptación estén cumplidos, pasan los escaneos de seguridad y CI, se preparan notas de liberación y un plan de reversión, y se ejecutan pruebas de humo antes del despliegue. Después de la liberación, el equipo realiza verificaciones post-despliegue y comunica a stakeholders y soporte.

Los **roles clave** en OctoAcme son: Project Manager (coordina entrega, cronogramas y comunicaciones), Product Manager (define resultados y prioriza), Developers (implementan features con calidad), QA/Testing (valida criterios de aceptación), y Stakeholders (proporcionan inputs y aprobaciones). Todos estos roles se comunican a través de artefactos centralizados—charters, roadmaps, backlogs, registros de riesgos y documentación de retrospectivas—que se mantienen versionados en el repositorio del proyecto. Este enfoque combinado de **claridad de propiedad, iteración pequeña, medición de impacto y aprendizaje continuo** crea una base sólida para escalar proyectos de múltiples equipos mientras se mantiene la alineación y la transparencia.

## Documentos Disponibles

### 📋 Visión General
- **[Visión General de Gestión de Proyectos](octoacme-project-management-overview.md)** — Introducción concisa a nuestro enfoque, roles clave y artefactos principales.

### 🚀 Ciclo de Vida del Proyecto
- **[Guía de Iniciación de Proyectos](octoacme-project-initiation.md)** — Pasos iniciales para validar y autorizar trabajo, alinear stakeholders y crear un plan ligero.
- **[Planificación de Proyectos](octoacme-project-planning.md)** — Cómo convertir una iniciativa aprobada en un backlog accionable y plan de entrega.
- **[Ejecución y Seguimiento](octoacme-execution-and-tracking.md)** — Orientación para la gestión día a día, seguimiento de progreso y ritmo de trabajo.
- **[Guía de Lanzamiento y Despliegue](octoacme-release-and-deployment.md)** — Estandarización de lanzamientos a producción para reducir riesgos e mejorar observabilidad.
- **[Retrospectiva y Mejora Continua](octoacme-retrospective-and-continuous-improvement.md)** — Cómo capturar aprendizajes y convertirlos en mejoras accionables.

### 🔑 Roles y Comunicación
- **[Roles y Personas](octoacme-roles-and-personas.md)** — Definición de roles típicos: Project Manager, Product Manager, Developers, QA y Stakeholders.
- **[Gestión de Riesgos y Comunicación](octoacme-risks-and-communication.md)** — Identificación, gestión y comunicación de riesgos, dependencias y escalaciones.

## Principios Clave

✓ **Customer-first**: Priorizar el valor y la usabilidad del cliente.
✓ **Iterative delivery**: Entregar incrementos pequeños, testables.
✓ **Clear ownership**: Cada proyecto tiene un PM y Product Lead nombrados.
✓ **Data-informed decisions**: Medir impacto e iterar con evidencia.
✓ **Psychological safety**: Fomentar feedback y aprendizaje.

## Plantillas y Checklists

Las plantillas de issues para actualizar documentación de procesos están disponibles en:
- `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` — Plantilla para solicitar actualizaciones o nueva contenido en documentos de proceso.

## Cómo Usar Esta Documentación

- **Para nuevos miembros**: Comienza con la [Visión General](octoacme-project-management-overview.md) y luego revisa los documentos del ciclo de vida en orden.
- **Para iniciar un proyecto**: Sigue la [Guía de Iniciación](octoacme-project-initiation.md).
- **Para planificar**: Consulta [Planificación de Proyectos](octoacme-project-planning.md).
- **Durante la ejecución**: Mantén actualizado el [Registro de Riesgos](octoacme-risks-and-communication.md) y sigue el ritmo de trabajo en [Ejecución y Seguimiento](octoacme-execution-and-tracking.md).
- **Antes de liberar**: Revisa la [Guía de Lanzamiento](octoacme-release-and-deployment.md).
- **Después de un milestone**: Ejecuta una [Retrospectiva](octoacme-retrospective-and-continuous-improvement.md).

Mantén los documentos del Charter del Proyecto actualizados en el repositorio del proyecto. Si deseas agregar contenido nuevo o mejoras, crea un issue utilizando la plantilla de actualización de documentos de proceso.

---

*Última actualización: Junio 2026*
*Mantenido por: OctoAcme Project Management Team*
