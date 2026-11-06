# Seguimiento de preguntas

Este archivo conserva el estado de la revisión antes de reconstruir el resto del banco.

## Nivel 2 — aprobadas y preservadas

- [x] **Temperatura:** ¿En muchos modelos generativos, qué suele producir una temperatura más alta?
- [x] **Ventana de contexto:** ¿Qué es la ventana de contexto de un modelo de lenguaje?
- [x] **Inferencia:** ¿Qué significa realizar una inferencia con un modelo de IA?
- [x] **Embeddings:** ¿Para qué sirven los embeddings?
- [x] **RAG:** ¿Qué busca lograr RAG al responder?
- [x] **Few-shot:** ¿Qué es un ejemplo few-shot dentro de un prompt?
- [x] **Multimodalidad:** ¿Qué significa que un modelo sea multimodal?

## Nivel 2 — incorporadas para la prueba

- [x] ¿Qué significa *context rot* cuando trabajamos con conversaciones o documentos muy extensos?
- [x] Si una API de IA es *stateless*, ¿por qué la aplicación debe reenviar el historial necesario en cada solicitud y cómo afecta eso al consumo de tokens?
- [x] ¿Cómo se diferencian los tokens de entrada, de salida y almacenados en caché al calcular el costo de una solicitud?
- [x] Si una aplicación envía las mismas instrucciones largas en muchas consultas, ¿para qué sirve el *prompt caching*?
- [x] En un contexto muy largo —por ejemplo, cercano a un millón de tokens—, ¿en qué posiciones suelen recuperar mejor la información muchos modelos?
- [x] ¿Qué es una *prompt injection* indirecta y cómo puede llegar al modelo desde una página web o un documento aunque el usuario no haya escrito una instrucción maliciosa?

## Niveles pendientes

- [x] **Nivel 1:** 12 preguntas implementadas con opciones, respuestas y explicaciones.
- [x] **Nivel 2:** 13 preguntas implementadas con opciones, respuestas y explicaciones.
- [ ] **Nivel 3:** postergado y oculto durante la primera prueba.

## Nivel 1 — preguntas aprobadas

1. [x] **Conservada:** En una herramienta de IA, ¿qué es un prompt?
2. [x] ¿Qué es un token y cómo se relaciona con la cantidad de texto que enviás y recibís?
3. [x] ¿Por qué el mismo prompt puede producir respuestas diferentes aunque no cambie el pedido?
4. [x] **Conservada:** ¿Qué es una “alucinación” de un modelo de IA?
5. [x] ¿Qué diferencia hay entre continuar una tarea en el mismo chat y comenzar una conversación nueva?
6. [x] ¿Qué significa pedirle a una IA una salida estructurada y cuándo conviene usar una tabla, CSV o JSON?
7. [x] ¿Qué diferencia hay entre un límite de mensajes, un límite de tokens y un saldo de créditos?
8. [x] ¿Qué diferencia hay entre alcanzar un límite temporal de uso y agotar la cuota incluida en un plan?
9. [x] ¿Qué diferencia hay entre pagar una suscripción mensual a una aplicación de IA y pagar el consumo de una API?
10. [x] ¿Qué conviene comparar, además del precio, para saber si un plan de IA sirve para el uso real de una persona o un equipo?
11. [x] Si una tarea requiere varios pasos, ¿por qué conviene definir verificaciones intermedias en lugar de pedir únicamente el resultado final?
12. [x] ¿Qué diferencia hay entre que una IA diga que realizó una acción y que realmente la ejecute mediante una herramienta conectada?

## Criterios acordados

- Priorizar conocimientos técnicos aplicables al uso cotidiano de IA.
- Evitar preguntas centradas en entrenamiento o creación de modelos.
- Evitar preguntas triviales o con respuesta demasiado evidente.
- Usar distractores técnicos, plausibles y parecidos entre sí.
- Durante la reconstrucción, presentar primero solo las preguntas, sin opciones de respuesta.
- La primera prueba del juego usará solamente los niveles 1 y 2; el Nivel 3 queda postergado.
- Después de cualquier respuesta, debe identificarse la opción correcta y mostrarse una explicación clara.
