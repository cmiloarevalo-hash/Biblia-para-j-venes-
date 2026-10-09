---
archive_schema: p00-github-source-v1
source_repo: cmiloarevalo-hash/Lago-1
source_issue: 63
source_type: issue_body
source_comment_id: null
source_url: "https://github.com/cmiloarevalo-hash/Lago-1/issues/63"
source_created_at: 2026-10-08T22:25:49Z
snapshot_date: 2026-10-08 (America/Santiago)
source_branch_head: f1026a7057335ff352d07a466b8e1169b3a0e070
review_status: "ACCEPTED (P06 research scope only)"
source_body_sha256: 9026fd5ad815bc06a136431a7aa94f22c214a65845af39e8043861f2378f6acd
source_body_characters: 19884
---
<!-- BEGIN_EXACT_GITHUB_BODY -->
## Tipo
RESEARCH / CONTENT-LICENSING GATE — NO IMPLEMENTATION

## Parent
- #58 — R02 “Calma viva y funciones personales”
- #61 — RC02 implementation batch
- #62 — RC02 definition/readiness ACCEPT

## Objetivo

Determinar, con evidencia verificable y fuentes primarias cuando sea posible, **qué Biblia católica en español puede usar La U de forma legal, completa y adecuada para lectores actuales**, priorizando:

1. **canon católico completo**;
2. **español moderno y fácil de comprender**;
3. **calidad y reconocimiento en contexto católico**;
4. **derechos compatibles con redistribución dentro de una APK Android offline**;
5. **fuente digital íntegra y verificable**;
6. **versificación/canon técnicamente integrables**.

La investigación debe responder especialmente a la preocupación del Product Owner:

> RV1909 usa vocabulario y giros antiguos que hoy dificultan la comprensión. RVR1960 también conserva lenguaje tradicional, aunque el público protestante suele estar más acostumbrado. Para la ruta católica se busca una experiencia contemporánea, clara y natural, no una Biblia arcaizante sólo porque sea libre.

## Preguntas de investigación obligatorias

### A. ¿Existe una Biblia católica moderna realmente libre/abierta?

Buscar y clasificar candidatos en español bajo categorías separadas:

- **Dominio público verificable**
- **Licencia abierta explícita** (CC0, CC BY, CC BY-SA u otra que permita redistribución de texto íntegro)
- **Uso gratuito pero NO redistribuible**
- **Copyright / licencia comercial o permiso escrito requerido**
- **Estado incierto / no verificable**

No confundir:
- “gratis en una web/app” con “libre para redistribuir”;
- imprimátur/aprobación eclesial con licencia de copyright;
- dominio público del texto fuente bíblico con dominio público de una traducción moderna.

### B. Candidatos mínimos a investigar

Como mínimo investigar, sin asumir conclusión:

- Biblia de la Iglesia en América (BIA)
- Biblia Latinoamérica / Latinoamericana
- Biblia de Jerusalén (edición latinoamericana / ediciones vigentes)
- Sagrada Biblia de Navarra / EUNSA
- Biblia de la Conferencia Episcopal Española
- Dios Habla Hoy con Deuterocanónicos / edición católica, si existe una edición exacta relevante
- Biblia El Libro del Pueblo de Dios / Biblia del Pueblo de Dios
- Biblia Torres Amat
- Nácar-Colunga
- Bover-Cantera
- cualquier otra edición católica en español con evidencia seria de licencia abierta o dominio público

Si aparecen alternativas mejores, agregarlas.

### C. Comparación lingüística / facilidad de lectura

Para cada candidato viable o relevante, evaluar:

- fecha/época de traducción o revisión;
- español peninsular vs latinoamericano;
- vocabulario arcaico;
- uso de “vosotros”, “habéis”, “he aquí”, “mas”, “empero”, etc.;
- sintaxis larga o invertida;
- equivalencia formal vs dinámica/funcional;
- nivel de lectura aproximado, **sin inventar métricas**;
- claridad para un lector católico joven/adulto actual;
- naturalidad en Chile/Latinoamérica;
- fidelidad percibida / propósito editorial;
- notas/introducciones: distinguir si son parte de la licencia o contenido separado.

Usar ejemplos breves de pasajes comparables cuando la licencia/fair use lo permita, sin reproducir extensamente texto protegido.

### D. Comparación con RV1909 y RVR1960

Explicar por qué RV1909 y RVR1960 pueden sentirse más arcaicas:
- léxico;
- morfosintaxis;
- registro;
- tradición textual/editorial;
- familiaridad cultural de comunidades protestantes.

No presentar “protestante = antiguo” ni “católico = moderno” como regla universal. La comparación debe ser lingüística/editorial, no estereotípica.

### E. Canon católico real

Verificar para cada candidato:
- 73 libros o cobertura católica equivalente;
- Tobías, Judit, Sabiduría, Sirácida/Eclesiástico, Baruc, 1–2 Macabeos;
- adiciones de Ester;
- adiciones de Daniel;
- Carta de Jeremías / Baruc 6 según edición;
- orden de libros;
- diferencias de numeración/versificación relevantes.

No considerar “católica completa” una edición que sólo agregue siete libros pero omita variantes/adiciones requeridas.

### F. Licencia y redistribución

Para cada candidato, identificar:
- titular/editor;
- texto exacto/edición;
- copyright;
- territorio;
- licencia pública si existe;
- permiso de redistribución digital;
- permiso de empaquetado offline;
- atribución requerida;
- restricciones de modificación;
- restricciones comerciales/no comerciales;
- política de citas;
- contacto/licensing si requiere autorización.

Priorizar:
1. sitio oficial del editor/titular;
2. conferencia episcopal / sociedad bíblica / universidad / editorial;
3. repositorio jurídico/licencia oficial;
4. catálogos bibliográficos institucionales.

Evitar basar el veredicto legal sólo en blogs, Wikipedia, foros o copias no oficiales.

### G. Dominio público por jurisdicción

La U puede distribuirse internacionalmente, por lo que no basta con que una obra sea libre en un solo país.

Investigar:
- vigencia de copyright de traducciones antiguas;
- muerte de traductores cuando sea relevante;
- renovación/reedición;
- si una edición moderna incorpora revisiones nuevas protegidas;
- diferencia entre texto antiguo en dominio público y edición digital moderna protegida.

Si el estado varía por país, marcarlo explícitamente.

### H. Fuente digital utilizable

Para un candidato “libre”, verificar si existe:
- texto completo digital legal;
- formato estructurado o convertible;
- integridad de capítulos/versículos;
- provenance/fuente;
- hash o posibilidad de fijar hash;
- ausencia de modificaciones editoriales no autorizadas;
- compatibilidad técnica para SQLite/offline.

No proponer scraping de webs/apps protegidas.

## Entregable obligatorio

Publicar en este Issue un informe titulado:

`CATHOLIC_BIBLE_OPEN_READABILITY_RESEARCH`

Debe contener:

1. **Executive conclusion**
2. **Candidate matrix**
3. **Readability comparison**
4. **Canon completeness matrix**
5. **Rights/licensing matrix**
6. **Digital-source availability**
7. **Comparison vs RV1909 / RVR1960**
8. **Best free/open candidate**
9. **Best modern licensed candidate**
10. **Best practical recommendation for La U**
11. **Fallback plan if no modern open Catholic Bible exists**
12. **Exact sources with URLs**
13. **Confidence + unresolved questions**
14. **Implementation impact for RC02**

## Recomendación esperada

No forzar una respuesta “libre” si la evidencia demuestra que las opciones modernas reconocidas requieren licencia.

La conclusión puede ser, por ejemplo:
- “no existe una opción moderna y suficientemente libre que cumpla todo”,
si eso es lo que muestran las fuentes.

En ese caso, proponer la mejor estrategia entre:
- licencia de una edición moderna;
- usar una edición histórica libre sólo como fallback;
- mantener infraestructura lista y no prometer corpus católico hasta obtener derechos;
- otra alternativa respaldada por evidencia.

## Fuentes y verificabilidad

Cada afirmación material sobre:
- canon;
- aprobación católica;
- año/edición;
- copyright;
- licencia;
- redistribución;
- disponibilidad digital;
- características editoriales

debe tener una fuente verificable.

Distinguir claramente:
- **hecho verificado**;
- **inferencia razonada**;
- **dato no verificado**.

## Prohibiciones

- No modificar código.
- No descargar ni incorporar corpus protegidos.
- No subir textos bíblicos completos a GitHub.
- No generar APK.
- No cerrar #61.
- No declarar una Biblia “libre” sin evidencia jurídica/licenciamiento suficiente.

## Handoff

Terminar exactamente con:

`READY FOR SUPERVISOR P06 CATHOLIC BIBLE REVIEW`

---

## P06-B — INVESTIGACIÓN PASTORAL JUVENIL Y DISEÑO DE CAPAS (SUPERVISOR ACCEPT 2026-10-08)

### Dirección de producto del Human / prioridad de aceptación
**La U está dirigida prioritariamente a jóvenes, grupos pastorales y sus docentes, catequistas y animadores.** La principal variable para escoger Biblia es la **comprensibilidad real del español del siglo XXI en Chile/Latinoamérica**, sin palabras ni construcciones arcaicas que dificulten la lectura espontánea. El reconocimiento católico, canon completo, fidelidad y autorización jurídica de redistribución offline son requisitos simultáneos. **No escoger una edición incomprensible sólo porque sea más fácil obtenerla.**

**R02 adopta investigación de ruta bíblica católica como prioridad de producto**, frente a RV1909 (lenguaje antiguo) y RVR1960 (licencia no acreditada para el corpus offline). No se está autorizando aún retirar del código el baseline RV1909, ofrecer una traducción católica concreta ni redistribuir una edición protegida. El onboarding Protestant/Catholic antes proyectado en #62 queda **pendiente de reconciliación de producto** con esta nueva prioridad: no construir una promesa de textos no disponibles.

### Actividad P06-B — Investigación profunda: actividades bíblicas para pastoral
**Autorización:** RESEARCH / PRODUCT DEFINITION ONLY, dentro de ESTE MISMO ISSUE #63. No abrir Issue adicional ni PR. Dos carriles en un único handoff: P06-A (Biblia católica clara y legal) y P06-B (pastoral juvenil/grupal).

**Pregunta central:** ¿Cómo ayudar a grupos pastorales, profesores y animadores a enseñar, comprender, conversar y recordar la Biblia y temas de la fe católica con actividades sencillas, atractivas, respetuosas, verificables y aplicables en el mundo real?

**Investigar con fuentes primarias/institucionales y manuales oficiales cuando existan:** pastoral juvenil y escolar católica, catequesis, organismos episcopales/CELAM/Vaticano, movimientos pastorales con material oficialmente publicado, pedagogía activa/aprendizaje lúdico. Fuentes secundarias solo como complemento y señaladas como tales. Diferenciar prácticas documentadas de propuestas originales; no atribuir falsa aprobación eclesial.

**Categorías mínimas:** 
1. Trivia bíblica (individual, por equipos y cooperativa; niveles de dificultad y feedback explicativo).
2. Juegos sencillos grupales sin tecnología (mímica, secuencias de relatos, memoria, tarjetas, pistas por referencia bíblica, retos colaborativos).
3. Dinámicas de lectura e interpretación contextual (personajes, parábolas, Evangelios, comunidad, oración, misericordia, servicio, discernimiento, vida cotidiana).
4. Actividades breves para comenzar/cerrar una reunión, animación y reflexión guiada, sin forzar experiencias íntimas.
5. Guías prácticas para profesores/catequistas/animadores: cómo preparar, facilitar, adaptar y evaluar comprensión, evitando convertir el juego en examen humillante.

**Entregable de investigación:** catálogo amplio y depurado de **al menos 20 actividades candidatas**, priorización de **8–12** por valor/viabilidad, y **al menos 8 fichas de actividad completamente ejecutables** (pueden solaparse con la selección). Para cada ficha: nombre, propósito espiritual y aprendizaje verificable, rango etario orientativo, tamaño de grupo, duración, materiales y costo, preparación, instrucciones paso a paso para animador, dinámica con/sin competencia, preguntas y respuestas con referencias canónicas verificables, explicación correcta, reflexión/cierre, variantes con/sin conectividad, accesibilidad/inclusión, seguridad y cuidado de menores, fuente y estatus de reutilización/adaptación. Si es creación original, identificarla claramente; no copiar páginas de manuales protegidos.

**Trivia:** crear un banco prototipo de preguntas originales, revisables y con respuestas comprobables, indicando libro/capítulo/versículo y, cuando proceda, diferencias de canon o versificación. No inventar pasajes, moralejas o lecturas doctrinales. No hacer depender las preguntas del texto íntegro de una traducción que aún no esté licenciada. Separar contenido educativo redactado originalmente de citas protegidas.

**Derechos y calidad:** verificar licencias de fichas, manuales, ilustraciones, preguntas y notas; que el juego sea conocido no autoriza copiar instrucciones exactas. Preferir diseño original fundamentado y referencias legítimas. Señalar incertidumbres doctrinales y puntos de validación editorial/pastoral.

**Seguridad e inclusión:** adaptar actividades a menores, voluntariedad, diversidad de capacidades y tamaños de grupo; evitar retos peligrosos, contacto físico forzado, exposición de confidencias, culpabilización pública, humillación por desconocimiento bíblico, presión emocional o recopilación de datos sensibles. Actividades presenciales accesibles y sin necesidad de cuentas, internet o Spotify.

### Menú futuro: investigación UX, NO implementación
El Human plantea un **menú hamburguesa desplegable** que abra capas adicionales sin desplazar la lectura bíblica. Investigar arquitectura de información y prototipo conceptual de:
- **Trivia bíblica**
- **Juegos para grupos pastorales**
- **Cómo dirigir una actividad**
- **Aprender y reflexionar / recursos para profesores y animadores**

Comparar el menú con las cuatro pestañas actualmente aceptadas (Hoy / Explorar / Leer / Biblioteca) y revisar navegación Back, rutas, densidad con letra grande, accesibilidad, Android, contenido offline y distinción entre uso individual vs. facilitador de grupo. Entregar propuesta de navegación + MVP escalonado + backlog posterior, **sin codificar el menú todavía**. No imponer una quinta pestaña; solicitar un gate separado del Supervisor para cualquier cambio de UX/implementación que altere #61.

### Criterios de selección bíblica reforzados (P06-A)
- Priorizar legibilidad actual y claridad pedagógica **antes de una falsa facilidad de licenciamiento**; evaluar lectura real en español chileno/latinoamericano con muestras muy breves y respetuosas del copyright.
- Incluir matriz de términos arcaicos, sintaxis, 'vosotros/habéis/he aquí/mas', frases extensas, complejidad, explicación sin conocimientos previos y comprensión para jóvenes y docentes.
- Diferenciar **mejor edición católica para la experiencia de La U**, **mejor que puede redistribuirse legalmente hoy** y **ruta práctica de licencias**. Una clase A vacía es una respuesta aceptable. No suponer que textos online, APIs o apps permiten APK offline.
- Mantener comprobación de canon católico completo, ediciones exactas, fuente digital autorizada y trazabilidad de derechos; no confundir utilidad catequética con autorización de copia.

### Handoff unificado y gates
Publicar en este #63, en orden:
1. ENTRY CHECKPOINT actualizado (tres documentos canónicos, #58/#61/#62/#63, HEAD exacto, P06-A/P06-B, permisos y exclusiones).
2. `CATHOLIC_BIBLE_OPEN_READABILITY_RESEARCH` con matrices A/B/C y recomendación editorial/legal diferenciada.
3. `PASTORAL_YOUTH_ACTIVITY_RESEARCH` con fuentes, catálogo >=20, 8–12 prioritarias, >=8 fichas listas para facilitadores, muestras de trivia, evaluación de copyright y plan de navegación/menu.
4. `INTEGRATED_PRODUCT_RECOMMENDATION`: Biblia + experiencias pastorales, orden MVP/iteraciones, dependencias de texto y riesgo; qué puede desarrollarse sin licencias.
5. Terminar exactamente `READY FOR SUPERVISOR P06 CATHOLIC BIBLE REVIEW`. Supervisor revisa **ambos carriles** antes de cerrar #63.

**Prohibiciones:** no crear Issues/PR nuevos; no escribir código ni workflow; no añadir corpus protegidos; no construir APK; no declarar juegos/trivia/aprobaciones como hechos sin respaldo. La ingeniería no dependiente de corpus de #61 sigue autorizada con las decisiones ya aceptadas; cualquier implementación nueva del menú y de juegos requiere revisión posterior del Supervisor.


---

## P06-C — Canciones para animación y convivencia pastoral

**DECISIÓN DE PRODUCTO DEL HUMAN — Prioridad de investigación, no desarrollo todavía.** Incorporar al futuro menú hamburguesa una sección visible llamada exactamente **«Canciones»**, pensada en repertorio realmente utilizado en la **pastoral juvenil católica** para **entretener, animar, integrar y acompañar actividades grupales**. No reducirla a playlists de escucha pasiva ni confundir toda música cristiana con repertorio católico pastoral.

### Trabajo autorizado al Implementer dentro del mismo Issue #63
- **Investigar a fondo** cantos y canciones apropiados para jóvenes, profesores, catequistas y animadores en parroquias, pastoral escolar y encuentros juveniles católicos de Chile/Latinoamérica. Priorizar cancioneros y repertorios de diócesis, parroquias, congregaciones/movimientos y fuentes oficiales de autores/editoriales; diferenciar uso constatado de supuestos o títulos difundidos genéricamente.
- Separar categorías de **animación/rompehielo y participación corporal voluntaria**, **convivencia y comunidad**, **cantos bíblicos o de catequesis**, **oración/reflexión**, **celebraciones y tiempos litúrgicos cuando corresponda**, aclarando cuándo una canción es apropiada para reunión pastoral y cuándo existe una regla específica para liturgia (no dar por intercambiables cantos recreativos y litúrgicos).
- Presentar catálogo documentado de **al menos 15 canciones candidatas**, con **8 recomendadas para empezar** cuando se encuentre respaldo suficiente. Por candidata: **título exacto, autor/compositor o procedencia si se verifica, contexto de uso católico realmente acreditado, género/categoría, motivo pedagógico/animación, edad/grupo/tipo de encuentro, nivel de participación, accesibilidad, fuente original, enlace oficial legítimo de escucha o compra si existe, derechos de letra/música/grabación/arreglo y estado de autorización**. Etiquetar cualquier campo desconocido.
- Para **al menos 5 fichas de uso grupal**, describir **cómo el animador puede utilizar la canción** (apertura, juego, encuentro, cierre), duración orientativa, dinámica y preparación, instrucciones **originales**, alternativas para grupos pequeños y personas con distintas capacidades, necesidad de conectividad/equipo y pauta para finalizar con reflexión cuando tenga sentido. No inventar letras, melodías, coreografías oficiales ni aprobación eclesial.
- Investigar **derechos específicos** para mostrar títulos, hipervínculos, letras completas, acordes, partituras, pistas/archivos descargables, reproducción, audio offline o uso público en encuentros; distinguir derechos de composición, letra, arreglos, interpretación/grabación y eventuales licencias de ejecución pública según lugar/territorio. Un enlace a Spotify/YouTube o reproducción gratuita NO equivale a licencia de distribución, descarga o inclusión offline en APK. **No copiar letras completas, audio, partituras, arte ni grabaciones con copyright**.
- Analizar la experiencia futura de **«Canciones» en menú hamburguesa** frente a la tarjeta Spotify existente aprobada para **Hoy**: menú como guía/repertorio para pastoral y animadores; Spotify como integración externa opcional. Evitar duplicación confusa, falta de red, inicio de sesión obligatorio o navegación invasiva. Recomendación con contenido informativo offline autorizado (nombres, metadatos propios, instrucciones originales, enlaces); no prometer audio offline sin derechos.
- Deben quedar explícitos **fuentes primarias verificables, hechos vs inferencias vs no verificado, derechos, riesgos pastorales/de menores y recomendaciones MVP vs posterior**.

### Entregable adicional y continuidad
Dentro del **mismo Issue #63**, añadir bloque `PASTORAL_CATHOLIC_SONGS_RESEARCH` al informe `PASTORAL_YOUTH_ACTIVITY_RESEARCH` y reflejarlo en `INTEGRATED_PRODUCT_RECOMMENDATION`. La futura estructura del menú debe incluir **«Canciones»** junto a Trivia, Juegos para grupos, Cómo dirigir una actividad y Aprender y reflexionar. El handoff final ya establecido sigue siendo `READY FOR SUPERVISOR P06 CATHOLIC BIBLE REVIEW`, revisando Biblia + actividades + canciones.

**Límites:** no Issue ni PR nuevo; no escribir código, corpus, multimedia, archivos de workflow ni APK. La implementación futura de esta sección requiere gate separado de Supervisor; la investigación P06 no bloquea las waves RC02 previamente autorizadas que no dependan de ella.
