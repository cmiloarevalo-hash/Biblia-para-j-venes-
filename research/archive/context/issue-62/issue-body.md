---
archive_schema: p00-github-source-v1
source_repo: cmiloarevalo-hash/Lago-1
source_issue: 62
source_type: issue_body
source_comment_id: null
source_url: "https://github.com/cmiloarevalo-hash/Lago-1/issues/62"
source_created_at: 2026-10-08T18:27:48Z
snapshot_date: 2026-10-08 (America/Santiago)
source_branch_head: f1026a7057335ff352d07a466b8e1169b3a0e070
review_status: "HISTORICAL — P05 ACCEPT"
source_body_sha256: a8dbf7f6d30945f8440b624cf705c64eb910c65d52b05a41c38ed8b779acd299
source_body_characters: 6557
---
<!-- BEGIN_EXACT_GITHUB_BODY -->
## Propósito

Antes de continuar con la implementación completa de RC02, cerrar las decisiones de producto que todavía están incompletas y obligar al Implementer a detectar huecos, dependencias, licencias y riesgos **antes de programar**.

Este Issue es un **formulario de definición + implementation-readiness gate**.

Parent: #58  
Implementation batch detenido: #61

---

# FORMULARIO RC02

Completar respondiendo debajo de cada campo. No hace falta usar lenguaje técnico.

## 1. Inicio / elección de Biblia

**1.1 Al abrir la app por primera vez, ¿quieres que pregunte qué tradición usar?**  
Respuesta propuesta: **Sí — Protestante / Católica**  
RESPUESTA:

**1.2 ¿Debe poder cambiarse después desde Ajustes?**  
RESPUESTA:

**1.3 Protestante**  
Traducción deseada: **Reina-Valera 1960**  
¿Confirmado?:
RESPUESTA:

**1.4 Católica**  
Debe ser una Biblia reconocida/aceptada en contexto católico y con canon católico completo.  
Traducción/edición exacta:
RESPUESTA:

**1.5 Si la traducción seleccionada no puede redistribuirse legalmente dentro del APK, ¿qué prefieres?**
- [ ] buscar otra traducción equivalente con licencia válida;
- [ ] usar contenido provisto legalmente por el propietario/licenciante;
- [ ] dejar la infraestructura lista y no publicar el corpus hasta tener licencia;
- [ ] otra:
RESPUESTA:

> Gate técnico obligatorio: para cualquier Biblia nueva se debe verificar edición exacta, canon, versificación, fuente y derecho de redistribución. El nombre de una traducción por sí solo no autoriza incluir el texto completo en el APK.

---

## 2. Notas y reflexiones durante la lectura

**2.1 Experiencia deseada**  
Propuesta:
- tocar un versículo;
- aparece una acción **“Agregar nota”**;
- se abre un cuadro/modal;
- escribir reflexión;
- Guardar / Cancelar;
- después se puede Editar / Eliminar.

¿Es eso lo que quieres?
RESPUESTA:

**2.2 ¿Una nota pertenece a un versículo o también puede abarcar varios versículos?**
RESPUESTA:

**2.3 ¿Dónde quieres volver a encontrarlas?**
- [ ] debajo del versículo;
- [ ] Biblioteca → Notas;
- [ ] ambas;
- [ ] otra:
RESPUESTA:

**2.4 ¿Notas privadas solamente en el teléfono, sin cuenta/nube por ahora?**
RESPUESTA:

**2.5 ¿Quieres destacados por color además de notas?**
RESPUESTA:

Colores/preferencia:
RESPUESTA:

---

## 3. Spotify / Música cristiana

**3.1 ¿Qué quieres que haga la primera versión?**
- [ ] mostrar playlists cristianas elegidas por nosotros;
- [ ] abrir la playlist en Spotify;
- [ ] reproducir dentro de la app;
- [ ] ambas;
- [ ] otra:
RESPUESTA:

**3.2 ¿Dónde debería aparecer Música?**
- [ ] nueva sección/pestaña principal “Música”;
- [ ] tarjeta en Hoy;
- [ ] dentro de Biblioteca;
- [ ] botón flotante/icono;
- [ ] otra:
RESPUESTA:

**3.3 Categorías deseadas**
Propuesta inicial:
- Calma y oración
- Ánimo
- Alabanza
- Adoración
- Jóvenes

Agregar/quitar:
RESPUESTA:

**3.4 ¿Las playlists serán playlists concretas elegidas por el Product Owner o el Implementer puede investigar/proponerlas para aprobación?**
RESPUESTA:

**3.5 ¿Spotify debe ser opcional y la app bíblica seguir funcionando totalmente sin Spotify?**
RESPUESTA:

> Antes de decidir “widget / botón / pestaña / reproducción embebida”, el Implementer debe comparar UX, dependencia de Spotify, login, red, SDK, políticas y fallback. No asumir SDK si un deep-link satisface el objetivo.

---

## 4. Recordatorio

Actualmente falta definir **qué recuerda**.

**4.1 ¿Qué quieres que diga/haga el recordatorio?**
Ejemplos:
- “Tu Palabra del día está lista”
- “Es un buen momento para leer la Biblia”
- “Continúa donde quedaste”
- recordar una reflexión/nota
- otro

RESPUESTA:

**4.2 Al tocarlo, ¿a dónde debería llevar?**
- [ ] Hoy / Palabra del día;
- [ ] última lectura;
- [ ] un pasaje elegido;
- [ ] pantalla principal;
- [ ] otra:
RESPUESTA:

**4.3 Frecuencia**
RESPUESTA:

**4.4 Hora elegida por el usuario o fija**
RESPUESTA:

**4.5 ¿Debe poder desactivarse completamente?**
RESPUESTA:

---

## 5. Palabra del día

**5.1 ¿Quieres mantener esta función?**
RESPUESTA:

**5.2 ¿Qué debe mostrar?**
- versículo;
- referencia;
- breve título/tema;
- botón “Leer contexto”;
- otro:
RESPUESTA:

**5.3 ¿Debe relacionarse aproximadamente con un tema del día o ser simplemente una selección positiva curada?**
RESPUESTA:

**5.4 Confirmar criterio:** para esta función diaria evitamos pasajes predominantemente violentos, condenatorios, desesperanzadores, de muerte o lamentación; esto **no elimina esos textos de la Biblia general**.
RESPUESTA:

---

## 6. “Calma viva” visual

**6.1 Confirmar dirección**
Calma + serenidad + ánimo + pureza; menos verde dominante; rosa/malva/peach/lavanda cálidos.
RESPUESTA:

**6.2 ¿Quieres conservar light y dark?**
RESPUESTA:

**6.3 ¿Alguna app/imagen/estilo que quieras usar como referencia visual?**
RESPUESTA:

---

## 7. Biblioteca

Propuesta de secciones:
- Guardados
- Notas
- Destacados
- Historial / continuar lectura

¿Qué debe incluir realmente RC02?
RESPUESTA:

Orden preferido:
RESPUESTA:

---

## 8. Buscador

**8.1 ¿Qué problemas del buscador actual quieres mejorar?**
RESPUESTA:

**8.2 ¿Quieres buscar por:**
- palabras exactas;
- temas;
- referencia;
- frases;
- libro;
- notas personales;
- otro?

RESPUESTA:

---

## 9. Qué NO quieres en RC02

Funciones, comportamientos o estilos que no deseas:
RESPUESTA:

---

# IMPLEMENTER READINESS AUDIT — obligatorio antes de código

Después de que el Product Owner complete el formulario, el Implementer debe revisar las respuestas y publicar:

1. **UNDERSTOOD** — qué producto entiende que se quiere construir.
2. **MISSING_INFORMATION** — preguntas todavía sin respuesta que realmente afecten implementación.
3. **ASSUMPTIONS_TO_AVOID** — cosas que no debe inventar.
4. **DEPENDENCIES** — librerías, APIs, Spotify, Android notifications, corpus, etc.
5. **LICENSE/RIGHTS GATES** — especialmente RVR1960 y Biblia católica elegida.
6. **DATA_MODEL_CHANGES** — notas, destacados, traducciones, preferencias.
7. **UX_MAP** — dónde vive cada función en la navegación.
8. **IMPLEMENTATION_WAVES** — orden propuesto de trabajo.
9. **VERIFICATION_PLAN** — qué puede comprobarse por tests/CI y qué necesitará prueba física.
10. **APK_POLICY** — no generar APK en cada microcambio. Generar APK sólo cuando exista un candidato que haya pasado los gates previos o cuando el APK sea necesario para resolver una duda runtime que no pueda resolverse de otro modo.

El Implementer **no comienza implementación** hasta que el Supervisor revise esta auditoría.

Cierre esperado:
`READY FOR SUPERVISOR RC02 DEFINITION REVIEW`