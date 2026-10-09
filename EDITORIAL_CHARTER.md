# EDITORIAL_CHARTER — regla de fidelidad textual inviolable

**Estado: STANDBY — DOCUMENTARY ARCHIVE ONLY.** Esta carta establece el **límite** para una fase futura que todavía **NO está autorizada**. Fuente: [#1 decisión Human](https://github.com/cmiloarevalo-hash/Biblia-para-j-venes-/issues/1), [P07 R03 metodología](research/archive/p07/comments/6071174267.md), [P06 investigación](research/archive/p06/SNAPSHOT_MANIFEST.md). No es un permiso para traducir.

## Regla sustantiva
**Se puede actualizar la expresión lingüística cuando sea necesario y esté justificado, pero jamás cambiar el significado, desfigurar el contexto ni introducir interpretaciones nuevas como si fueran Escritura.** La adecuación a lectores jóvenes **no** autoriza añadir/suprimir ideas, moralizar, armonizar discrepancias, trivializar metáforas, corregir supuestos errores teológicos o reconstruir acontecimientos no descritos.

Preservar rigurosamente: **quién habla y a quién**, personas/identidades/referentes, relaciones de agencia, tiempo y aspecto verbal, **afirmaciones y negaciones**, condiciones, mandatos, promesas, relaciones de causa y consecuencia, orden narrativo, citas dentro de citas, imágenes, repeticiones, ritmo/estructura poética, ironía, género literario, límites del discurso y **ambigüedades presentes en la fuente**. Cambios de sentido, omisiones materiales, nuevas lecturas doctrinales o soluciones automáticas a variantes = **BLOCK**.

## Separación de contenidos (propuesta de modelo futuro; no existe corpus ahora)
- `scripture_text`: únicamente texto controlado autorizado que superó revisión bíblica/editorial. En P00 no se crea.
- `editorial_notes`: explicaciones y aplicaciones nuevas **claramente rotuladas, fuera del texto sagrado**.
- `source_critical_notes`: incertidumbres, variantes textuales, decisiones sobre originales, traducciones indirectas, problemas de puntuación y versificación, con identificador/procedencia.
- `pastoral_resources`: trivia, canciones, guías de facilitación P06 como recursos separados que no sustituyen versículos.

## Reglas de evidencia y detención
1. Solo obras/ediciones cuya base legal, fuente digital exacta y licencias aplicables sean **positivamente verificadas** o contratos realmente suscritos y aceptados por titular. No combinar 3–4 traducciones modernas protegidas para producir texto “nuevo”. No cargar corpus completo protegido en IA.
2. Por cada futura unidad: `source_id, source_sha256, book_id, chapter, source_verse_label, source_language/reference, exact context, change category, linguistic reason, version hash, reviewer 1, reviewer 2, decision`. Los **dos revisores humanos independientes** serán al menos bíblico/exegético y editorial español Chile/LatAm, con asesor legal según fuente.
3. Si una fuente es dudosa en licencia, sentido, variante textual, segmentación, tradición griega/Ester/Daniel o atribución: **STOP, conservar variantes y elevar decisión**; no permitir que IA “resuelva”.
4. Prueba posterior con jóvenes/docentes voluntarios y medidas de comprensión, **nunca** inferir fidelidad de “me gustó leerlo” ni reducir evaluación a corrector ortográfico o similitud.
5. No presentar un recurso como oficialmente aprobado por iglesia sin aval correspondiente; distinguir canon/orden, texto legal y reconocimiento eclesiástico. Una edición independiente puede explicitar sus fuentes sin simular aprobación.

**P00 no redacta ni adapta ningún versículo.** El Supervisor deberá emitir autorización explícita posterior, con dossier de fuente limpia y plan de QA humano, antes de cualquier muestra.
