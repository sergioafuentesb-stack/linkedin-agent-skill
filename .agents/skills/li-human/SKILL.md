---
name: li-human
description: Revisa y edita borradores para corregir caracteres invisibles, puntuación tipográfica y expresiones gastadas; también explica señales estructurales y las limitaciones de su puntuación heurística. Úsala si piden humanizar o revisar un texto y antes de mostrar borradores de LinkedIn.
---

# li-human

Usa los scripts incluidos en esta carpeta cuando estén disponibles:

```bash
python3 .agents/skills/li-human/humanize.py borrador.txt --report
python3 .agents/skills/li-human/detect.py borrador.txt
python3 .agents/skills/li-human/detect.py original.txt revisado.txt
```

También puedes pasar texto por entrada estándar. Lee `slop.json` para ver el léxico, sustituciones y señales estructurales configuradas. No cambies el léxico sin petición expresa.

## Correcciones automáticas

Los scripts eliminan ciertos caracteres invisibles, normalizan algunos signos tipográficos y sustituyen expresiones del léxico. Revisa la salida: una sustitución automática puede alterar el sentido o la voz.

## Señales que requieren criterio

El detector señala patrones como estructuras retóricas repetidas, preguntas de una palabra, exceso de hashtags, cebo de interacción, emoji y longitud uniforme. No reescribas automáticamente si eso cambia el significado. Propón cambios manuales y conserva la voz de la persona.

## Puntuación y límites

El panel mide variación de longitud, especificidad, densidad de expresiones del léxico, huella tipográfica y señales de voz. Son heurísticas locales, no detectores externos ni garantía de que un texto sea aceptado como humano. No afirmes que un texto es «indetectable» ni lo optimices para evadir una evaluación académica o de seguridad.

## Flujo

1. Guarda el borrador en un archivo temporal fuera del repositorio, o usa entrada estándar si no se debe persistir.
2. Ejecuta `humanize.py` y revisa el informe.
3. Reescribe a mano las señales estructurales que correspondan, sin añadir hechos.
4. Ejecuta `detect.py` antes y después si la comparación resulta útil.
5. Devuelve el texto revisado y describe brevemente los cambios y límites. No muestres solo una puntuación.
