---
name: li-profile
description: Evalúa y mejora un perfil de LinkedIn con una rúbrica de 12 partes. Úsala si la persona pide puntuar u optimizar su perfil, reescribir el titular o la sección «Acerca de», o comparte su perfil para recibir comentarios.
---

# li-profile

Un perfil responde «¿por qué debería escribirle a esta persona?» en pocos segundos. No accedas a LinkedIn ni edites el perfil en nombre de la persona.

## Datos de entrada

Solicita el titular, «Acerca de», cargo actual y las dos experiencias anteriores más recientes, además de saber si tiene banner y sección «Destacado». Una captura de la tarjeta superior basta para una primera evaluación. Si falta información, evalúa solo lo disponible e indica lo que falta; no inventes datos.

## Evaluación

Lee `rubric.json` junto a este archivo. Puntúa los 12 criterios sobre 100, muestra una tabla con la justificación por criterio y el total. Sé franco y específico.

## Mejoras

Ordena las propuestas por puntos perdidos. Entrega bloques listos para copiar:

1. **Titular (máximo 220 caracteres):** tres opciones con qué haces, para quién, evidencia y un siguiente paso. No inventes resultados.
2. **Primeras dos líneas de «Acerca de»:** quién recibe ayuda y qué cambia. Evita frases genéricas o biografías en tercera persona.
3. **Cuerpo de «Acerca de»:** problema del lector, cómo ayudas, evidencia real y siguiente paso; procura menos de 1.400 caracteres.
4. **Destacado:** recomienda tres elementos posibles: mejor publicación, evidencia del trabajo y vía de contacto.
5. **Experiencia:** una línea de alcance y de dos a tres logros medibles por cargo. No fabriques métricas.
6. **Banner:** una frase de posicionamiento y una vía de contacto.

Incluye una nueva puntuación estimada y explica qué puntos requieren elementos que no se pueden crear con texto, como recomendaciones o historial de publicaciones. Si la persona solicita humanización, usa `li-human` con criterio y explica los límites de sus heurísticas.

## Formato

Presenta primero la tabla de puntuación y después las propuestas en orden de prioridad. Nada se guarda ni publica en LinkedIn; la persona aplica los cambios.
