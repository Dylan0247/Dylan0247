<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/tokyo-night.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/tokyo-day.svg">
  <img alt="Hola, soy Dylan. En formación: DevOps y arquitectura de soluciones. Java, DevOps y Kubernetes." src="assets/tokyo-day.svg">
</picture>

<p align="center">
  <a href="#sobre-mí">Sobre mí</a> &nbsp; · &nbsp;
  <a href="#mi-enfoque">Mi enfoque</a> &nbsp; · &nbsp;
  <a href="#práctica-destacada">Cerebro</a> &nbsp; · &nbsp;
  <a href="#proyecto-actual">AnimalGO</a> &nbsp; · &nbsp;
  <a href="https://github.com/Dylan0247?tab=repositories">Repositorios</a>
</p>

## Sobre mí

Soy Dylan y estoy estudiando para orientar mi carrera hacia **DevOps y la arquitectura de soluciones**.

Tengo conocimientos de **Java** y actualmente estoy aprendiendo **Kubernetes**, mientras amplío mi formación en DevOps y diseño de soluciones.

## Mi enfoque

| Base actual | En aprendizaje | Objetivo profesional |
| :--- | :--- | :--- |
| **Java** | **Kubernetes · DevOps · Arquitectura de soluciones** | Trabajar en DevOps y evolucionar hacia arquitectura de soluciones. |

## Práctica destacada

### Cerebro · Automatización y contexto para IA

Implementación personal que conecta **Obsidian, n8n, Ollama, Qwen3 y Codex** para conservar contexto, decisiones y evidencias entre sesiones. La inferencia de Qwen3 es local en **Ubuntu WSL**; el circuito completo también utiliza Codex.

| Área | Trabajo realizado |
| :--- | :--- |
| Integración | Workflows autenticados en n8n y conector **MCP** de ocho herramientas para recuperar contexto, consultar el modelo y preparar propuestas. |
| Automatización | Resúmenes de turnos y relevos estructurados, con prevención de duplicados, reintentos y registro de fallos. |
| Memoria controlada | Separación de estado vigente, histórico y borradores; consolidación revisada con fuentes, hashes, respaldos y restauración. |
| Operación | Servicios en WSL, reinicio de n8n ante fallos y arranque programado desde Windows. |

**Cómo trabajo:** recuperación selectiva de contexto, revisión de respuestas de IA y cambios trazables y recuperables. Las herramientas MCP consultan y proponen; la aplicación de cambios ocurre mediante procesos separados y revisados.

<details>
<summary>Pruebas documentadas y límites</summary>

Según mi documentación de las implementaciones del **5 de octubre de 2026**, revisada el **8 de octubre**:

- **67 pruebas aisladas superadas** entre memoria controlada, guardado automático, consolidación revisada, recuperación filtrada y extracción de pendientes, además de recorridos reales de integración.
- Evaluación de Qwen3: **21 de 30 respuestas** cumplieron completamente el protocolo estricto. Se registraron fallos de citas, clasificación y veredictos; este resultado no mide una precisión general y las respuestas siguen requiriendo revisión.
- Comprobaciones de autenticación, fuentes, hashes, compatibilidad MCP, duplicados, respaldos y restauración.

**Pendiente en ese corte:** observar el primer inicio después de reiniciar Windows y ampliar la evaluación cuando cambien el modelo o sus responsabilidades.

La recuperación usa búsqueda por texto y filtros, sin embeddings ni base vectorial. Los borradores automáticos no se convierten directamente en hechos confirmados ni actualizan el estado vigente.

</details>

## Proyecto actual

### AnimalGO

Mi proyecto actual es un **RPG educativo sobre animales**. Me permite trabajar con una aplicación multiplataforma, una API y servicios de datos y autenticación.

| Componente | Tecnologías del proyecto | Código |
| :--- | :--- | :--- |
| Aplicación y juego | Dart · Flutter · Bonfire · Flame · Tiled | [Frontend →](https://github.com/Dylan0247/frontend) |
| API | Python · FastAPI | [Backend →](https://github.com/Dylan0247/backend) |
| Datos y autenticación | PostgreSQL · Supabase | Incluidos en la aplicación y la API |
| Integración de pagos | Stripe | Incluida en el proyecto |

Los repositorios incluyen documentación de arranque y pruebas de navegación, servicios, autenticación y perfiles.

## Mi trabajo

Puedes explorar mis [repositorios](https://github.com/Dylan0247?tab=repositories) y la actividad que aparece en este perfil para seguir mis proyectos y aprendizaje.

---

<p align="center"><sub>DYLAN0247 &nbsp; / &nbsp; Java · DevOps en formación · Arquitectura de soluciones</sub></p>
