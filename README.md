# Reto de IA · Tres cupos, ocho estudiantes (Riwi)

Actividad en equipo con un **caso ficticio**: ocho estudiantes de un curso de programación, tres cupos para un programa de acompañamiento. La IA puede proponer una selección, pero **el propósito y los criterios dependen de nosotros**.

## Objetivo
Ver cómo cambia la recomendación de una IA cuando se le da (o no) el propósito del programa, y aprender a revisar sus criterios, suposiciones y justificaciones.

## Contenido del repositorio
| Archivo | Para qué sirve |
|---|---|
| `README.md` | Explicación del reto y guía paso a paso |
| `prompt_reto.md` | Prompt estructurado (Fase 1, Fase 2 y análisis) que cualquier IA puede ejecutar |

## Reglas del reto
- No hay una lista oficial de tres nombres. Lo que se evalúa es la **argumentación** con la información disponible.
- La tabla **no** incluye información sobre esfuerzo, intención de abandonar ni resultados futuros.
- La **instrucción exacta** debe ser idéntica en las dos consultas.
- La Fase 2 se hace en una **conversación nueva con la misma IA**.
- El docente puede asignar el Programa A a una parte de los equipos y el B a los demás.
- La conclusión final tiene un **máximo de 150 palabras**.

## Pasos
1. **Elegir por tu cuenta** tres estudiantes y anota tu criterio, antes de usar la IA.
2. **Consulta 1 (sin programa):** envía a la IA el caso, la tabla y la instrucción exacta. Guarda la respuesta completa.
3. **Revisar en equipo la respuesta:**
   - ¿Qué interpretó por "necesitar acompañamiento"?
   - ¿Qué datos usó y cuáles dejó en segundo plano?
   - ¿Dio por cierto algo que la tabla no dice?
   - ¿Pidió información adicional? Guarda esas preguntas.
4. **Registrar** criterios, suposiciones y preguntas que vale la pena conservar. Recuerda: una explicación clara también debe sostenerse en los datos y en el propósito del programa.
5. **Recibir el programa** (A o B) que entregue el docente.
6. **Consulta 2:** abre una conversación nueva con la misma IA y envía el caso, la tabla y la misma instrucción, añadiendo la información del programa. Guarda la respuesta completa.
7. **Comparar:** ¿cambió la selección? Si cambió, explica qué dato o criterio produjo el cambio. Si no cambió, revisa si cambió la justificación.
8. **Entregar** las dos respuestas, el programa recibido y la conclusión (≤ 150 palabras).

## Estructura de la entrega
1. **Las dos consultas y respuestas completas** (sin resumir).
2. **El programa que recibió el equipo** (A o B).
3. **Una conclusión argumentada** (máximo 150 palabras).

## Plantilla de entrega
```md
## 01 Las dos consultas y respuestas completas
### Mi selección inicial (antes de usar la IA)
- Estudiantes: ...
- Criterio: ...

### Consulta 1 (sin programa)
**Instrucción enviada:** ...
**Respuesta completa de la IA:** ...

### Revisión de la respuesta 1
- Interpretación de "necesitar acompañamiento": ...
- Datos usados / en segundo plano: ...
- Cosas que dio por ciertas sin estar en la tabla: ...
- Preguntas que hizo: ...

### Consulta 2 (con programa)
**Instrucción enviada (idéntica):** ...
**Respuesta completa de la IA:** ...

### Qué cambió, qué permaneció y por qué
...

## 02 El programa que recibió el equipo
Programa (A / B): ...

## 03 Conclusión (máx. 150 palabras)
...
```

## Lista de verificación antes de entregar
- [x] Elegí tres estudiantes por mi cuenta antes de consultar a la IA.
- [x] Usé la misma IA y la misma instrucción exacta en ambas consultas.
- [x] La Fase 2 fue en una conversación nueva.
- [x] Pegué las respuestas completas, no resúmenes.
- [x] Indiqué qué programa recibimos.
- [x] Expliqué qué dato o criterio produjo el cambio (o por qué no hubo cambio).
- [x] La conclusión tiene 150 palabras o menos.
- [x] No afirmé nada sobre los estudiantes que la tabla no diga.

## Herramientas de la página
- La página tiene botones para **copiar el caso, la tabla y la instrucción** (Fase 1) y para **copiar la consulta con el programa** (Fase 2). Úsalos para no cambiar el texto.
- Tu borrador de elección se guarda solo en tu navegador.
- "Descargar borrador del equipo" genera un archivo de texto con lo que completaron. La página no envía respuestas: se presenta según indique el docente.

## Notas
- **Instrucción exacta (Fase 1 y 2):** "Selecciona a los tres estudiantes que más necesitan el acompañamiento. Justifica cada elección y explica por qué dejaste fuera a los demás."
- La tabla tiene las columnas Nota actual (0 a 5, se aprueba con 3), Asistencia y la descripción de la situación. El PDF solo muestra asistencia y descripción, así que copia las notas desde la página a `prompt_reto.md`.
- La conclusión debe responder: ¿qué necesitábamos definir nosotros para que la IA pudiera hacer una selección acorde con el propósito del programa?
