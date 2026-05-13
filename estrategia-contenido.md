name: estrategia-contenido

descripción: Crea estrategias de contenido para marcas y creadores en redes sociales. Usar SIEMPRE que el usuario mencione: estrategia de contenido, plan de contenido, calendario editorial, qué publicar en redes, contenidos para Instagram, TikTok, LinkedIn, Threads o YouTube, pilares de contenido, plan de publicaciones, o cualquier variante de ayúdame a planificar mis redes. También activar cuando el usuario diga no sé qué publicar o dame ideas de contenido.

---

# Estrategia de contenido

## Objetivo
Generar una estrategia de contenido breve, accionable y lista para ejecutar, con validación del usuario antes de la entrega final.

---

## Flujo de trabajo

### Paso 1 — Recolección de contexto
1. Identifica el perfil del usuario o la marca.
2. Identifica la audiencia objetivo.
3. Identifica temas base o pilares de contenido.
4. Si faltan datos críticos, haz máximo 2 preguntas juntas.
5. Si el usuario no define objetivo, asigna uno: crecer, autoridad, venta o educación.

---

### Paso 2 — Preguntar formato de entrega

Antes de generar, preguntar:

> ¿En qué formato quieres recibir tu estrategia?
>
> A) Word (DOC) ← recomendado  
> B) PDF  
> C) Página en Notion  
> D) Presentación en Canva  
>
> Si no respondes, se entregará en DOC por defecto.

---

### Paso 3 — Borrador para validación

Esperar confirmación o ajustes del usuario.

---

### Paso 4 — Generación final

Una vez validado el borrador, generar la tabla completa y entregar en el formato elegido.

---

## Defaults

- Duración: 2 semanas.
- Cantidad: 10 contenidos.
- Cobertura: lunes a viernes.
- Redes: Instagram, TikTok y Threads (ajustar si el usuario especifica otras).
- Formato de entrega: DOC (si el usuario no elige).

---

## Pilares de contenido (opciones base)

- Educación — enseña algo útil.
- Inspiración — motiva o genera conexión emocional.
- Entretenimiento — genera engagement, humor, relatable.
- Posicionamiento — muestra autoridad o prueba social.
- Venta — convierte, oferta, urgencia.
- Comunidad — fomenta participación o identidad de tribu.

---

## Criterios para el hook

- Máximo 10 palabras.
- Debe generar tensión, curiosidad o identificación inmediata.
- Evitar frases genéricas: "Te cuento", "Hoy te hablo de", "En este post".
- Evitar que suene a IA: nada de "Descubre cómo", "Todo lo que necesitas saber".
- Formatos válidos: pregunta provocadora, dato sorprendente, afirmación polémica, promesa concreta.
- No repetir el mismo formato de hook dos veces en la misma tabla.

---

## Criterios para el ángulo

- Cada fila debe tener un ángulo distinto.
- Opciones:
  - caso real
  - error común
  - comparación
  - dato contraintuitivo
  - proceso paso a paso
  - opinión fuerte
  - historia personal
  - tendencia

---

## Criterios para el formato

- No repetir el mismo formato más de 3 veces en 10 contenidos.
- Opciones válidas:
  - Carrusel
  - Video corto
  - Reel con texto
  - Story interactiva
  - Post estático
  - Talking head
  - Meme
  - Encuesta
  - Hilo
  - BTS

---

## Criterios para el CTA

- No repetir el mismo CTA más de 2 veces en la tabla.
- Opciones:
  - Guarda este post
  - Compártelo con alguien que lo necesita
  - ¿Tú qué harías?
  - Cuéntame en comentarios
  - Sígueme para la parte 2
  - Etiqueta a alguien
  - Visita el link en bio
  - Responde con una palabra

---

## Columnas de la tabla final

| Red social | Objetivo | Tema | Pilar | Ángulo | Hook | Formato | CTA |

---

## Reglas

- Sin saludos ni presentación.
- Sin explicaciones largas ni relleno.
- Máximo 2 preguntas juntas si faltan datos.
- Si el usuario pide más de 10 contenidos, avisar antes por posible consumo alto de tokens.
- Revisar coherencia entre objetivo, tema, hook, formato y CTA antes de entregar.
- Si no hay branding definido, no mencionarlo — la tabla no lo requiere.
- Para entrega en DOC: usar la skill `docx` para generar el archivo.
- Para entrega en PDF: generar el DOC primero, luego convertir con la skill `pdf`.
- Para entrega en Notion o Canva: notificar al usuario que debe copiar la tabla manualmente.

---

## Ejemplo de salida

| Red social | Objetivo | Tema | Pilar | Ángulo | Hook | Formato | CTA |
|---|---|---|---|---|---|---|---|
| Instagram | Autoridad | Branding personal | Posicionamiento | Error común | 3 errores que destruyen tu marca personal | Carrusel | Guarda este post |
| TikTok | Crecer | Productividad con IA | Educación | Herramienta poco conocida | Nadie en tu industria usa esto todavía | Video corto | Sígueme para la parte 2 |
| Threads | Comunidad | Opinión del sector | Entretenimiento | Opinión fuerte | El contenido "de valor" ya no funciona | Hilo | ¿Tú qué harías? |

Mostrar en el chat solo los 10 temas + hooks antes de generar la tabla completa.
