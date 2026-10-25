---
name: li-plan
description: Prepara un calendario semanal de contenido y una lista de interacción en LinkedIn. Úsala cuando pidan planificar publicaciones, crear un calendario o decidir qué compartir y con quién interactuar.
---

# li-plan

Prepara un plan editable; nada se programa ni se publica.

## Datos necesarios

Consulta la guía de voz y el historial reciente si la persona los proporciona o están accesibles. No supongas acceso a archivos de Claude Code. Si faltan datos, solicita en un solo bloque:

1. Qué ofrece la persona y a quién.
2. Tres o cuatro temas por los que quiere ser conocida.
3. Hechos de la semana: conversaciones, cifras, errores, trabajo realizado o aprendizajes.
4. Entre diez y veinte personas o empresas relevantes, si quiere una lista de interacción personalizada.

No inventes experiencias, contactos, métricas ni noticias. Si falta alguno de estos datos, prepara una estructura y marca los espacios pendientes.

## Publicaciones

Propón hasta cuatro publicaciones semanales, alternando prueba, opinión, enseñanza, historia y oferta. Para cada una, incluye tema, ángulo basado en un hecho real, formato de gancho correspondiente a `../li-post/hooks.json` y día/hora sugeridos.

Para audiencias B2B concentradas en una zona horaria, martes a jueves entre 7:30 y 9:30 es una hipótesis inicial, no una garantía. Usa la zona horaria de la audiencia y deja clara la incertidumbre. La calidad de la primera línea importa más que optimizar la hora.

## Interacción

Si se proporcionaron contactos, agrúpalos como alcance, pares y posibles compradores. Sugiere comentarios útiles y genuinos; no recomiendes mensajes de venta en comentarios ni contacto automatizado. Sin una lista real, deja esos espacios para completar.

## Entrega

Muestra la semana como calendario, después la lista de interacción y finalmente el siguiente paso para convertir un espacio en borrador con `li-post`. No escribas `~/.claude/linkedin/plan.md` desde esta skill: entrega el contenido en la conversación para que la persona decida dónde guardarlo.
