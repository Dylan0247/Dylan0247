<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/tokyo-night.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/tokyo-day.svg">
  <img alt="Hola, soy Dylan. En formación: DevOps y arquitectura de soluciones. Java, DevOps y Kubernetes." src="assets/tokyo-day.svg">
</picture>

<p align="center">
  <a href="#sobre-mí">Sobre mí</a> &nbsp; · &nbsp;
  <a href="#mi-enfoque">Mi enfoque</a> &nbsp; · &nbsp;
  <a href="#práctica-destacada">Cerebro</a> &nbsp; · &nbsp;
  <a href="#proyectos-de-final-de-grado-superior">AnimalGO</a> &nbsp; · &nbsp;
  <a href="https://github.com/Dylan0247?tab=repositories">Repositorios</a>
</p>

## Sobre mí

Soy Dylan y estoy estudiando para orientar mi carrera hacia **DevOps y la arquitectura de soluciones**.

Tengo conocimientos de **Java** y actualmente estoy aprendiendo **Kubernetes**, mientras amplío mi formación en DevOps y diseño de soluciones.

## Mi enfoque

| Área | Conocimientos y enfoque |
| :--- | :--- |
| Desarrollo | **Java · Python · Dart · Flutter** |
| Práctica aplicada | **Orquestación de IA generativa**, integración de modelos y herramientas mediante n8n, Ollama y MCP en Cerebro. |
| En aprendizaje | **Kubernetes · DevOps · Infraestructura de servidores y nube · Arquitectura de soluciones** |
| Objetivo profesional | Trabajar en DevOps y evolucionar hacia el diseño y la operación de infraestructura y soluciones en la nube. |

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

## Proyectos de final de grado superior

### AnimalGO · Proyecto anterior

**RPG educativo sobre animales desarrollado como proyecto de final de grado superior.** Integra una aplicación en **Flutter y Dart**, una API en **Python y FastAPI**, y servicios de datos y autenticación con **Supabase y PostgreSQL**.

[Aplicación →](https://github.com/Dylan0247/frontend) &nbsp; · &nbsp; [API →](https://github.com/Dylan0247/backend)

## Mi trabajo

Puedes explorar mis [repositorios](https://github.com/Dylan0247?tab=repositories) y la actividad que aparece en este perfil para seguir mis proyectos y aprendizaje.

---

<p align="center"><sub>DYLAN0247 &nbsp; / &nbsp; Java · DevOps en formación · Arquitectura de soluciones</sub></p>
