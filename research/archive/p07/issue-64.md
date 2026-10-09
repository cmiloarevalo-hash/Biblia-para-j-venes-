---
archive_schema: p00-github-source-v1
source_repo: cmiloarevalo-hash/Lago-1
source_issue: 64
source_type: issue_body
source_comment_id: null
source_url: "https://github.com/cmiloarevalo-hash/Lago-1/issues/64"
source_created_at: 2026-10-08T23:19:48Z
snapshot_date: 2026-10-08 (America/Santiago)
source_branch_head: f1026a7057335ff352d07a466b8e1169b3a0e070
review_status: "REWORK / OPEN"
source_body_sha256: 0f571ded5ef87b234e606338b884f1edfac8bdf8d481ca6b9a85e0d51dc7ec8b
source_body_characters: 16568
---
<!-- BEGIN_EXACT_GITHUB_BODY -->
# P07 — Viabilidad de una nueva Biblia católica en español contemporáneo, original y jurídicamente reutilizable

## Parent / antecedentes y estado
- Parent: #58 (R02); impacto en #61 (infraestructura multi-Biblia).
- P06 #63: `ACCEPT/CLOSED` research — BIA/LPD prioritarias, ninguna edición moderna con redistribución íntegra offline demostrada.
- **TIPO:** INVESTIGACIÓN JURÍDICO-EDITORIAL + FACTIBILIDAD TÉCNICA + PLAN DE TRADUCCIÓN ORIGINAL.
- **DECISIÓN SUPERVISOR:** ACCEPT para investigación **solamente**; NO autoriza traducir/modernizar corpus íntegro, usar textos protegidos como insumo masivo, importar, publicar, distribuir, abrir PR ni generar APK.
- Base inicial: `main @ f1026a7057335ff352d07a466b8e1169b3a0e070` (reverificar HEAD al entrar).

## Objetivo del Human
Evaluar si La U puede disponer de **su propia Biblia católica completa**, fiel al significado y contexto bíblico, pero en **español de Chile/Latinoamérica del siglo XXI comprensible para jóvenes, catequistas y pastoral**, con derechos suficientes para distribuir **todos los libros offline en APK Android**, legalmente y con estatus eclesial apropiado.

El Human pregunta si es posible actualizar RV1909 u otra traducción vieja libre, o consultar 3–4 Biblias contemporáneas con copyright para construir una versión nueva. **No asumir que la mezcla/reformulación de 3–4 traducciones modernas evita derechos de autor.** Investigar precisamente los límites legales y proponer rutas legítimas.

## Preguntas y líneas de investigación obligatorias
### A. Derecho positivo: Chile + distribución internacional
- Consultar textos oficiales vigentes: Ley chilena 17.336, derechos de traducción/adaptación, dominio público, obras derivadas, autoría y derechos morales, edición digital, excepciones de cita/docencia, términos y territorios; Convenio de Berna y principales países de distribución (Chile, España, EE. UU., otros relevantes) con diferencias explícitas.
- Distinguir **texto bíblico antiguo/subyacente**, traducción histórica, **edición/revisión moderna**, anotaciones/paratexto, base de datos estructurada/digitalización, marcas y maquetación; una edición gratuita online/eBook/API no otorga permiso de empaquetado offline.
- Estudiar licencias abiertas reales: CC0, CC BY, CC BY-SA, NC, ND, share-alike y atribución; exactamente qué autorizan para una edición modernizada, distribución APK gratis/comercial, publicaciones multiterritoriales.
- Para traducciones protegidas **BIA, LPD, Biblia Latinoamérica, DHH católica, Biblia de Jerusalén, RVR1960**: cuándo es legítima consulta comparativa limitada para análisis y cuándo una adaptación, ensamblaje, reexpresión automatizada o ingestión de textos completos exige autorización previa. No sugerir umbral mágico de “% de palabras cambiadas”.
- Consultar reglas del servicio IA/terceros para carga de contenidos protegidos, registro de fuentes, confidencialidad, autoría y potencial semejanza no intencional. La creación mediante IA no garantiza que exista un derecho de autor propio sobre todo el resultado; investigar requisitos de contribución humana donde proceda.
- Definir prácticas preventivas (cadena de custodia, fuente limpia, no usar corpus modernos no licenciados como entrada, revisión independiente de coincidencias), **sin prometer que pruebas automatizadas certifican ausencia de infracción**.
- Distinguir orientación informativa de asesoría legal formal; contratar abogado/autoridades solo previa autorización del Human.

### B. Cuatro rutas comparadas: matriz de LEGALIDAD + CALIDAD + VIABILIDAD
1. **Modernización de texto efectivamente en dominio público:** RV1909, Torres Amat original u otras versiones católicas históricas; titularidad, plazo/fallecimientos, jurisdicciones, revisiones y fuente digital reutilizable, derecho moral, límites de traducir desde una traducción antigua, riesgos de arrastrar lecturas arcaicas y textos ausentes. RV1909 solo 66 libros: NO pretender canon católico por cambiar lenguaje; faltan siete libros y adiciones griegas a Ester y Daniel / Baruc 6.
2. **Nueva traducción independiente desde hebreo/arameo/griego** (incluyendo NT y deuterocanónicos/griego de Ester y Daniel) con edición base original cuya licencia digital sea apta. Investigar ediciones críticas y fuentes textuales para cada bloque; que la antigüedad de la lengua no convierta una edición crítica moderna o digitalización en PD automáticamente. Necesidad de expertos filológicos y pastoral.
3. **Adaptación licenciada de traducción moderna**: negociar permiso expreso con titulares para modernizar, corregir, versionar, publicar y redistribuir corpus entero offline, separando notas. Identificar documentación contractual necesaria, sin contactar/firmar en nombre del Human.
4. **Contenido formativo original basado en hechos/referencias** (guías, explicaciones, trivias) como **producto distinto de una traducción bíblica íntegra**; mantener etiquetas honestas y no vender paráfrasis originales como Biblia completa.

### C. Factibilidad católica y lingüística
- Canon católico íntegro 73 libros, versión de Tobías/Judit/Sirácida/Macabeos etc., adiciones Ester/Daniel, Carta de Jeremías y coherencia de numeración/versificación; fuentes hebreas/griegas/arameas/latinas específicas y diferencias doctrinales.
- Verificar requisitos oficiales de **aprobación eclesiástica para publicar traducciones de la Escritura** (Código de Derecho Canónico c. 825) y diferencia entre aprobación para publicación/devoción, uso pastoral y textos litúrgicos. ¿Quién debe aprobar, proceso plausible, notas necesarias, criterios de fidelidad, autoridad regional? No afirmar imprimátur ni autorización eclesial que no exista.
- Objetivo lingüístico: español moderno chileno/latinoamericano, sin `vosotros/he aquí/mas/recibiere` cuando sea evitable y sin perder precisión, género literario, poesía, metáforas, nombres y doctrinas. Definir políticas para expresiones culturales, significados ambiguos, notas, estilo, nivel de lectores 12–25 y docentes, responsabilidad humana.
- Piloto futuro **solo tras nuevo ACCEPT**: muestras pequeñas de pasajes elegidos, desde textos permitidos, revisión de filólogo bíblico/teólogo católico/editor español + facilitadores juveniles y usuarios; pruebas de comprensión, exactitud, originalidad y riesgo de parecido indebido. No redactar corpus ahora.

### D. Costos, tiempos y decisión Go/No-go
- Costeo y duración en escenarios prudentes **estimaciones justificadas, no cifras inventadas** para 73 libros: revisión superficial de PD, traducción original profesional, licencia y adaptación, y alternativa “licenciar Biblia moderna BIA/LPD tal cual”; riesgo doctrinal, carga humana/IA, dependencia de titular y camino de aprobación.
- Lista de 3–4 versiones modernas relevantes **para análisis editorial comparativo legítimo**, NO como base para ensamblar su expresión literal.
- Tabla de derechos/documentos exigidos para fuente limpia, contrato de titulares, aprobación eclesial, canon íntegro, fuentes/formatos y APK offline internacional.
- Clasificar cada ruta: `VIABLE CON EVIDENCIA`, `VIABLE SUJETA A DERECHOS/EXPERTOS`, `NO APROBADA`, `NO RECOMENDADA`, con hechos/inferencias/no verificado.
- Recomendación final que priorice comprensión juvenil + fidelidad católica + no infringir derechos; **comparar costo total de elaborar una Biblia propia frente a licenciar una traducción moderna que ya existe**.

## Fuente oficial orientativa — verificar vigencia/alcance, NO sustituye investigación
- Chile Ley 17.336: https://www.bcn.cl/leychile/navegar?idNorma=28933
- Código de Derecho Canónico c.825: https://www.vatican.va/archive/cod-iuris-canonici/esp/documents/cic_libro3_cann822-832_sp.html
- WIPO/Berna: https://www.wipo.int/wipolex/en/legislation/details/10110
- Creative Commons licencias: https://creativecommons.org/cc-licenses/
- US Copyright Office derivados/compilaciones: https://www.copyright.gov/circs/circ14.pdf
- US Copyright Office IA/autoría humana (2025): https://copyright.gov/newsnet/2025/1060.html
- Evidencia anterior de traducciones: #63 P06-A [comentario](https://github.com/cmiloarevalo-hash/Lago-1/issues/63#issuecomment-6070775770).

## Protocolo de entrada y ejecución
**IMPLEMENTER: RESEARCH/PLANNING ONLY.** Antes de decidir/executar leer workflow canónico en orden `.project/CONTEXT.md`, `.project/WORK_STATE.md`, `.project/IMPLEMENTER_PROTOCOL.md`; parent #58, #61, P06 #63 y este Work Item con todos sus comentarios. Reconstruir desde GitHub; ENTRY CHECKPOINT con rol, HEAD, autoridad, work item, outputs, input leído, límites, blockers y ausencia de dependencia de chat privado.

**Writable**: comentarios y evidencias en **este Issue solamente**. **Read-only/forbidden**: app, `.project/*`, README, workflows, historias, otros Issues salvo lectura. No PR, no código, no descarga/ingestión masiva de ediciones protegidas, no corpus, no entregar texto de nueva Biblia, no cambios CI ni APK. No contactar titulares, autoridades o especialistas en nombre del Human sin autorización; documentar rutas/contactos y formularios.

**Evidencia obligatoria:** fuentes primarias, URLs, fechas/vigencia, país/edición/licencia exactos; hechos/inferencias/desconocidos, contradicciones, prioridades/alternativas y límites; informe robusto, publicarlo por comentarios secuenciales de forma durable. Sin pedir autorización para cada subinvestigación.

## Salida y gate
Publicar `P07_ORIGINAL_CATHOLIC_BIBLE_LEGAL_FEASIBILITY` + `P07_TRANSLATION_SOURCE_AND_METHOD_MATRIX` + `P07_PRODUCT_COST_RISK_COMPARISON` + `P07_SUPERVISOR_DECISION_PACKET`: resultados, 4 rutas clasificadas, recomendación y tareas/gates posteriores.

Última línea exacta:
`READY FOR SUPERVISOR P07 REVIEW`

**Ningún derecho de explotación, aprobación eclesiástica, legalidad de traducción, permiso de publicación o resultado de implementación se concede por el cierre de esta investigación.** RC02 #61 continúa conforme a su autorización previa **no dependiente de corpus**.


---

## CAMBIO DE PRIORIDAD DEL HUMAN — P07: BIBLIA CLARA, INDEPENDIENTE Y LEGAL (2026-10-08)
**Esta decisión más reciente del Human SUPERSEDE toda interpretación de los requisitos anteriores de P07 que imponga aprobación eclesiástica o afiliación católica como condición imprescindible.** El objetivo principal es **una versión bíblica legible en español del siglo XXI, correcta, libre de infracción y redistribuible íntegra offline en La U**. Debe ser útil a jóvenes, educadores y pastoral, aunque la edición final **no sea confesional ni tenga aprobación de una iglesia**. No reclamar falsamente aprobación, imprimátur, asociación institucional o uso litúrgico.

### Decisión estratégica del Supervisor
Investigar **primero y con mayor profundidad** la modernización/revisión responsable de una **fuente española cuyo texto y edición digital se comprueben realmente libres**, con contraste desde originales bíblicos legales y revisión humana. La fuente de partida preferida para comprobar es **RV1909** disponible en eBible como Public Domain (66 libros). Referencia metodológica real: **World English Bible**, originada en actualización de *American Standard Version* 1901, documentada con revisión humana y en dominio público. Existe WEB con orden católico y materiales deuterocanónicos en inglés; su uso se considera **comparador de método/canon**, no fuente española ya lista ni permiso para otro corpus protegido.

**SEGUNDA VÍA, simultánea y no subordinada a intereses denominacionales:** investigar una **traducción original** desde ediciones de hebreo/arameo/griego que permitan el uso requerido, evaluando tiempo, costo, especialistas y trazabilidad. **TERCERA VÍA:** negociación opcional para adaptar una traducción contemporánea protegida, sólo si mejora decisivamente tiempo/calidad y la licencia permite modificaciones y APK offline. **NO** mezclar, cargar en IA o parafrasear sistemáticamente 3–4 ediciones protegidas como supuesto modo de eludir copyright. Pueden consultarse para comparación lingüística limitada conforme a usos permitidos.

### Canon/cobertura: decisión separada de denominación
Comparar con detalle:
- **66 libros**: ruta rápida sobre RV1909, pero etiquetada fielmente como edición de 66 libros, no bíblia católica íntegra.
- **73 libros**: cobertura deseable para lectores católicos e iniciativas pastorales sin exigir publicidad/aprobación confesional; identificar **siete deuterocanónicos + adiciones griegas de Ester y Daniel + Baruc/Carta de Jeremías**, fuentes legales separadas, canon/versificación y costo. Puede etiquetarse descriptivamente `Edición de 73 libros` o `Incluye deuterocanónicos` sin pretender reconocimiento eclesiástico oficial. No sumar fuentes heterogéneas sin declaración de proveniencia ni consistencia editorial.
- **76+/ecuménicas**: examinar como posibilidad de amplia cobertura y declarar exactamente alcance y diferencias sin engañar.

**Estudio religioso vs civil:** distinguir ley estatal aplicable de condiciones internas para considerarla *Biblia católica aprobada*. Canon 825 solo es gate obligatorio si se busca publicación/aprobación de edición en ámbito eclesial pertinente; investigar matices y evitar fingir que por sí solo concede derechos comerciales de copyright o que crea veto estatal universal sobre edición independiente. Si no se busca aval católico, detallar información editorial honesta que sí puede publicarse.

### Prácticas de editoriales y traductores protestantes/independientes
Investigar documentalmente cómo desarrollan y publican:
- comité de traducción / revisión exegética desde lenguas originales y textos fuente;
- modernización de obras libremente reutilizables y revisión humana (World English Bible / ASV 1901);
- gestión de licencias, titularidad de redactores humanos, QA bíblico/contextual, lecturabilidad juvenil y equipos revisores;
- procedimientos reales en Chile para publicar/distribuir: fuente libre/licencias/atribución, contratos de edición o cesión de derechos, inscripción voluntaria DDI (no confundir inscripción con permiso de utilizar la obra original), ISBN/depósito legal **solo si aplican al formato/distribución**, copyright/trademark, información al usuario, tiendas Android, distribución internacional, y conveniencia de asesoría jurídica antes de lanzamiento.
Las comunidades protestantes no están sometidas por defecto a aprobación de la Conferencia Episcopal católica, pero sí a derechos de autor y a las condiciones de publicación de sus propios proyectos.

### Matriz de decisión exigida
Comparar **costo, complejidad, plazo razonado, pureza legal de fuentes, legibilidad siglo XXI, fidelidad/trazabilidad, alcance de 66/73 libros, salida EPUB/USFM/SQLite/offline, derechos sobre versión humana+IA**. No inventar costos monetarios absolutos ni certificar derechos sin evidencia. Priorizar el camino con menor fricción y mayor control legal, no el de mayor prestigio confesional.

### Trabajo del Implementer
Actualizar/sintetizar al concluir su paquete P07 y recomendar:
1. **GO/NO-GO** de revisión RV1909 libre para piloto jurídico-editorial con pequeñas muestras autorizables en otro gate.
2. Plan específico para completar opcionalmente 73 libros con fuentes abiertas/PD válidas, incluso cuando no exista licencia global; si imposible, explicarlo.
3. Ruta alternativa traducción independiente desde idiomas bíblicos y fuentes críticas autorizadas.
4. Expediente legal/operativo de Chile e internacional; qué papeleo es realmente necesario, voluntario o condicionado a publicación comercial.
5. Papel de la IA: asistente lingüístico/sugerencias, no autoridad textual; revisión humana activa, prueba con jóvenes, control de semejanza no intrusivo y registro de procedencia.
6. Marcado honesto: sin sello institucional no atribuir “aprobada por Iglesia católica”; derechos y método deben ser informados al usuario.

**Gates vigentes:** #64 investigación-only, sin generar texto bíblico, ni PR, ni APK, ni contratos/contactos en nombre del Human. #61 continúa desarrollándose en tareas no dependientes de corpus. Termina `READY FOR SUPERVISOR P07 REVIEW`.

**Fuentes oficiales de partida:** https://www.bcn.cl/leychile/navegar?idNorma=28933 ; https://www.propiedadintelectual.gob.cl/faq ; https://www.propiedadintelectual.gob.cl/node/652 ; https://ebible.org/spaRV1909/copyright.htm ; https://ebible.org/study/content/texts/engwebpb/FR0.html ; https://ebible.org/eng-web-c/copyright.htm ; https://www.vatican.va/archive/cod-iuris-canonici/esp/documents/cic_libro3_cann822-832_sp.html ; https://www.copyright.gov/espanol/faq/uso-justo.html ; https://copyright.gov/newsnet/2025/1060.html .
