# CANON_AND_VERSE_MAPPING_66_73 — matriz histórica y controles

**Archivístico, no corpus importado ni canon QA ejecutado.** Fuentes: [Catecismo §120 citado en P06](research/archive/p06/comments/6070775770.md), [P07 R01](research/archive/p07/comments/6071156028.md), [R04 original](research/archive/p07/comments/6071183124.md) **y REWORK Supervisor posterior** [6071318625](research/archive/p07/comments/6071318625.md).

| Perfil | Cobertura descriptiva | Lo que NO acredita |
|---|---|---|
| **66** | 39 libros del AT tradicional Reina-Valera + 27 NT. RV1909 `spaRV1909` es base previa histórica; no tiene 7 libros deuterocanónicos ni sus adiciones griegas completas. | **NO** es «Biblia católica completa» ni se convierte en 73 por cambio de nombre/modernización; no certifica lenguaje moderno. |
| **73** | 46 libros AT +27 NT; incluye 7 deuterocanónicos, las partes griegas de Ester/Daniel y Baruc 6/Carta de Jeremías según edición. | Índice de 73 títulos **NO** confirma toda variante/versificación/segmento ni aprobación eclesial ni licencia de fuente. |
| **76+ / ecuménico** | Pueden existir otros como 1 Esdras, Salmo 151, Oración de Manasés, 3–4 Macabeos, etc. según edición/tradición. | **NO** añadirlos al total 73 ni presentarlos automáticamente como canon católico. |

## Perfil nominal de 73 (sin números de versos)
- **Pentateuco (5):** Génesis, Éxodo, Levítico, Números, Deuteronomio.
- **Narrativa e historia (16):** Josué, Jueces, Rut, 1 Samuel, 2 Samuel, 1 Reyes, 2 Reyes, 1 Crónicas, 2 Crónicas, Esdras, Nehemías, Tobías, Judit, Ester, 1 Macabeos, 2 Macabeos.
- **Sabiduría/poesía (7):** Job, Salmos, Proverbios, Eclesiastés/Qohélet, Cantar de los Cantares, Sabiduría, Sirácida/Eclesiástico.
- **Profetas (18):** Isaías, Jeremías, Lamentaciones, Baruc (incluyendo **Carta de Jeremías** cuando se organiza Baruc 6), Ezequiel, Daniel, Oseas, Joel, Amós, Abdías, Jonás, Miqueas, Nahúm, Habacuc, Sofonías, Ageo, Zacarías, Malaquías.
- **NT (27):** Mateo, Marcos, Lucas, Juan, Hechos, Romanos, 1 Corintios, 2 Corintios, Gálatas, Efesios, Filipenses, Colosenses, 1 Tesalonicenses, 2 Tesalonicenses, 1 Timoteo, 2 Timoteo, Tito, Filemón, Hebreos, Santiago, 1 Pedro, 2 Pedro, 1 Juan, 2 Juan, 3 Juan, Judas, Apocalipsis.

**Nota de control:** esta clasificación hace 5+16+7+18 = **46** en AT y 27 en NT. **Siete títulos deuterocanónicos respecto a 39**: **Tobías (Tob), Judit (Jdt), Sabiduría (Sab/Sb), Sirácida/Eclesiástico (Si/Sir/Eclo), Baruc (Bar), 1 Macabeos, 2 Macabeos**. **Ester griego** y **Daniel griego** se controlan como *segmentos/variantes de libros ya contados*, no como libros 74–75. Carta de Jeremías, tradicionalmente **Baruc 6** o ítem separado `LJE`, no se cuenta dos veces; comprobar distribución concreta.

## Mapeos que deberán preservarse SIN INVENTARLOS
| Unidad | RV1909 fuente 66 | Fuente 73/índice eBible BLL/SBLM según Supervisor | Resultado |
|---|---|---|---|
| TOB/JDT/WIS/SIR/BAR/1MA/2MA | **NO presente** como libro propio | **INDEX VERIFIED** en BLL/SBLM según corrección. BLL: <https://ebible.org/spabll/> | `UNMAPPED / CORPUS INTEGRITY NOT RUN` |
| Ester griego `ESG` | Ester hebrea/narrativa 66, **sin adiciones griegas completas** | **INDEX VERIFIED** en BLL/SBLM y fuentes WEB Greek; ubicación griega puede variar | `UNMAPPED` — adiciones A–F vs capítulos 10–16 u otras etiquetas según edición |
| Daniel griego `DAG` | 12 capítulos tradicionales en RV1909, **no íntegros** suplementos griegos | **INDEX VERIFIED** BLL/SBLM; incluye contexto de Cántico, Susana, Bel y dragón | `UNMAPPED` — Daniel 3:24–90 / caps.13–14 según versión |
| Carta de Jeremías `LJE` / Baruc 6 | **NO** | BLL índice PDF lista **LJE separado**; verificar Baruc 6, duplicación y variantes | `UNMAPPED / DO NOT DOUBLE COUNT` |
| Extras 76+ | NO | Índices BLL pueden tener 1 Esdras, 3–4 Macabeos etc. | `EXTRA`, fuera perfil 73 salvo declaración explícita |

## Datos/método propuestos para un gate futuro (no implementados)
Cada versión **por separado**: `translation_id; canonical_book_id; source_book_id; source_label; language; source_edition; coverage_type; chapter_id; verse_start; verse_end; segment_variant; canonical_equivalence; review_status; rights_manifest_id`. Prohibido suponer que concatenar capítulos de origen da versificación válida. Si fuente de la carta está duplicada en BAR/LJE, FLAG para inspección; no hacer «deduplicación» semántica por IA.

**Estado Supervisor:** el P07 R04 original afirmaba de forma demasiado categórica falta de opción española abierta para 73; el Supervisor **REWORK** documentó lo contrario **a nivel índice**, no a nivel integridad. La matriz aquí es un control documental de **ambos** hechos, no una corrección investigativa nueva. **Sin texto bíblico redactado.**
