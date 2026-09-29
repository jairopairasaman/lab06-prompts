# Biblioteca de prompts — Laboratorio 06

## Prueba N — [Nombre de la técnica]
**Herramienta:** ChatGPT / Claude / Gemini
**Prompt:**
> (pegar aquí el prompt utilizado)
**Resultado (resumen):** ...
**Observaciones:** ...

El prompt estructurado sí incluyó el asunto, respetó el límite de palabras, incluyó el curso de diseño de Interfaces y la cantidad exacta de días.

Asunto: Solicitud de prórroga para la entrega del informe final - Diseño de Interfaces

Estimado/a profesor/a,

Le escribo en representación de mi equipo para el curso de Diseño de Interfaces. Debido a que dos integrantes han estado enfermos esta semana, nuestro ritmo de trabajo se vio afectado. Para garantizar un documento con la calidad adecuada, le solicitamos de manera respetuosa una prórroga de 3 días para la entrega de nuestro informe final.

Si usted lo considera viable, le proponemos presentar el informe el lunes 5 de octubre de 2026. Agradecemos mucho su tiempo y comprensión, y quedamos atentos a su respuesta.

Atentamente,

[Tu nombre]

## Rúbrica de evaluación


| Criterio   | Descripción                                   | Puntaje (1-5) |
| ---------- | --------------------------------------------- | :-----------: |
| Relevancia | Responde exactamente lo que se pidió           |               |
| Precisión  | La información es correcta y sin inventos      |               |
| Formato    | Respeta la estructura y extensión solicitadas  |               |
| Tono       | Es adecuado para el público objetivo           |               |

## Iteraciones — [Nombre de la tarea]


| Versión | Cambio realizado en el prompt       | Puntaje total |
| ------- | ----------------------------------- | :-----------: |
| v1      | Prompt inicial sin estructura        |      /20      |
| v2      | Se agregó rol y contexto             |      /20      |
| v3      | Se definió formato y restricciones   |      /20      |

## Plantillas Reutilizables

### 1. Redacción de correo formal
```text
Actúa como {{rol}}.
Contexto: {{situación}}.
Redacta un correo dirigido a {{destinatario}} para {{objetivo}}.
Formato: asunto, saludo, cuerpo en máximo {{n}} párrafos y despedida.
Restricciones: máximo {{palabras}} palabras, tono {{tono}}.

Resume el texto delimitado por <texto></texto> en {{cantidad}} viñetas de máximo {{palabras}} palabras.
<texto>
{{texto_a_resumir}}
</texto>

