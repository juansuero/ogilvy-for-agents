# Ogilvy Practice Lab

![Icono de Ogilvy Practice Lab](assets/icon.png)

Un conjunto de 23 skills para investigar, crear y revisar comunicación comercial. Ayuda a trabajar en posicionamiento, textos, webs, propuestas, captación y experimentos con hechos y límites explícitos.

Es un proyecto independiente inspirado en selecciones de *Ogilvy on Advertising*. No es un producto oficial ni está respaldado por Ogilvy. Las instrucciones están en inglés y las respuestas siguen el idioma de la solicitud.

## Cómo utilizarlo

El repositorio contiene un paquete de plugin basado en skills. `plugin.json` es el manifiesto portable y `.codex-plugin/plugin.json` proporciona compatibilidad con Codex. La instalación y la activación de esta versión en cada entorno aún requieren comprobación.

Ejemplos de uso:

- «Revisa solo este titular. Conserva los hechos y no inventes resultados: [texto]».
- «Analiza esta propuesta comercial y señala qué promesas necesitan pruebas: [propuesta]».
- «Tenemos muchas visitas y pocas consultas. Ayúdame a identificar hipótesis con estos datos: [datos]».

Para una consulta amplia, `ogilvy-advisor` ayuda a elegir el procedimiento. Para una tarea concreta se puede seleccionar la skill correspondiente en `skills/`. Cada skill incluye sus propias referencias y una plantilla opcional.

## Alcance y límites

- Los procedimientos cubren estrategia, creatividad, copy, comunicación con clientes, captación y aprendizaje.
- Las referencias representan selecciones de los 20 capítulos; no son una cobertura exhaustiva ni incluyen el libro completo. Los estudios y resultados históricos citados no se han verificado de forma independiente.
- Una recomendación basada en un principio del libro no demuestra que una campaña vaya a funcionar. Las afirmaciones sobre un cliente necesitan sus propias pruebas.
- Una auditoría comercial de una web no certifica su SEO, seguridad, accesibilidad o rendimiento.
- Crear un borrador no autoriza su envío, publicación ni gasto. El plugin no incluye servidor, acceso automático a datos ni integración con Alchemy.

## Estado de la beta

La versión `0.2.0` se importó desde el plugin privado de ChatGPT. `evals/regression-v0.2.jsonl` contiene 15 casos preparados; no se presentan como pruebas ejecutadas. La selección automática de skills y la ejecución en una instalación real siguen pendientes de validación.

La base se exportó del release `pluginrel_6af070d395fc8191a3c570985a1eb852`, creado el 8 de noviembre de 2026; los metadatos de autoría y el icono se han actualizado y los localizadores textuales se han sustituido por referencias de capítulo y sección en el repositorio. Los cambios hechos directamente en ChatGPT no se sincronizan automáticamente con este repositorio.

## Estructura

- `skills/`: instrucciones, principios seleccionados y plantillas por tarea.
- `evals/`: casos de regresión propuestos.
- `plugin.json` y `.codex-plugin/`: manifiestos del plugin.

## Autoría y licencia

Creado por Juan Suero, fundador de Veltas. Las aportaciones originales se distribuyen bajo [MIT](LICENSE). [NOTICE.md](NOTICE.md) explica la atribución y los derechos de terceros.
