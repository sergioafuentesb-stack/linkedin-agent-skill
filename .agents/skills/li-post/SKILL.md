---
name: li-post
description: Redacta publicaciones para LinkedIn a partir de una idea concreta, con opciones de apertura, voz propia y revisión de estilo. Úsala cuando pidan una publicación, un gancho o convertir una idea en un borrador para LinkedIn.
---

# li-post

Convierte una idea real en un borrador que suene a la persona. No publiques nada.

## Antes de redactar

1. Busca `voice.md` en el contexto proporcionado por la persona o en `~/.claude/linkedin/voice.md` si es accesible. Si no está disponible, pide tres publicaciones propias y deriva una guía provisional en la conversación. No escribas archivos personales sin petición explícita.
2. Lee `hooks.json` de esta carpeta y selecciona fórmulas que encajen de verdad.
3. Si la idea es vaga, pregunta en un solo bloque qué ocurrió, a quién afectó y qué coste o resultado tuvo. No rellenes huecos con invenciones.

## Estructura

- Primera línea: gancho breve que funcione en la vista previa móvil.
- Segunda línea: desarrolla la promesa del gancho.
- Cuerpo: párrafos breves separados por espacio.
- Giro: una línea que cambie el marco de lectura.
- Cierre: una pregunta concreta o una instrucción, no ambas.

Como referencia, apunta a 900–1.300 caracteres para una publicación de texto, sin alargar por cumplir una cifra.

## Proceso

1. Ofrece tres ganchos basados en fórmulas distintas de `hooks.json` y recomienda uno con una razón breve.
2. Redacta la publicación completa sobre ese gancho.
3. Revisa con `li-human` y muestra los hallazgos pertinentes. No presentes una puntuación heurística como prueba de que un texto pasará detectores externos.
4. Presenta el borrador final en un bloque listo para copiar y señala los datos que falten.

## Criterios

- Una idea por publicación.
- Prefiere evidencia concreta a adjetivos. Si falta una cifra, pregunta o déjala marcada como pendiente; nunca la inventes.
- Evita el cebo de interacción genérico.
- Como máximo tres hashtags pertinentes.
- No incluyas enlaces en el cuerpo; si hace falta, sugiere añadirlo en un comentario.
- No publiques, programes ni registres contenido. La persona decide y publica manualmente.
