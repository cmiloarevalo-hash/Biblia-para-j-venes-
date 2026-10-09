---
archive_schema: p00-github-source-v1
source_repo: cmiloarevalo-hash/Lago-1
source_issue: 61
source_type: issue_body
source_comment_id: null
source_url: "https://github.com/cmiloarevalo-hash/Lago-1/issues/61"
source_created_at: 2026-10-08T18:22:30Z
snapshot_date: 2026-10-08 (America/Santiago)
source_branch_head: f1026a7057335ff352d07a466b8e1169b3a0e070
review_status: "HISTORICAL — RC02 non-corpus engineering"
source_body_sha256: 3d9a36689008b13b46f1a41b7610028135fcaf42c5b73e9e2728d9bac34db999
source_body_characters: 4866
---
<!-- BEGIN_EXACT_GITHUB_BODY -->
## Parent
Issue #58 — R02 “Calma viva y funciones personales”.

## Objective
Avanzar el desarrollo de RC02 desde el estado actual de `main` hasta una APK candidata instalable, usando **GitHub/web como plano principal de desarrollo** y dejando la prueba física final en teléfono como gate humano.

Baseline inicial:
`main @ f1026a7057335ff352d07a466b8e1169b3a0e070`

## Execution model
Implementación continua por waves, con checkpoint durable al final de cada una. No esperar revisión humana entre waves salvo bloqueo real o decisión material.

Orden autorizado:

### B — Calma viva v2
- reemplazar dominancia verde por identidad cálida rosa/malva/peach/lavanda;
- mantener calma, serenidad, ánimo y pureza;
- light/dark;
- preservar legibilidad y contraste;
- mantener shell usable con texto grande;
- no cambiar corpus/search semantics.

### C — Notas y destacados
- notas locales por referencia canónica;
- editar/eliminar nota;
- destacados con colores suaves;
- Biblioteca muestra Notas + Destacados;
- orden canónico libro/capítulo/versículo;
- persistencia local SQLite;
- sin cuentas/nube.

### D — Palabra del día
- catálogo curado positivo/alentador;
- selección determinista por fecha local;
- categorías como esperanza, paz, amor, fortaleza, gratitud, propósito, amistad, perdón, consuelo;
- excluir del feature diario pasajes predominantemente violentos/Condenatorios/desesperanza/muerte/lamento;
- no eliminar ni censurar esos textos del corpus general;
- CTA para abrir pasaje.

### E — Recordatorio local real
- implementar notificación local real en Android;
- best-effort, sin prometer exact alarm;
- preferencia local configurable;
- tocar notificación abre la app/pasaje cuando sea razonablemente soportado;
- permisos y estados claros.

### F — Música / Spotify
- primera versión por deep links, sin SDK complejo;
- categorías mínimas: Calma y oración, Ánimo, Alabanza, Adoración, Jóvenes;
- degradación segura si Spotify no está instalado;
- no convertir Spotify en dependencia obligatoria del core.

### G — Preparación de corpus privado / segunda Biblia
- NO subir textos bíblicos completos nuevos a GitHub;
- preparar arquitectura/importador para corpus local/privado;
- mantener RV1909 actual sólo como baseline técnico mientras se migra;
- no integrar RVR1960/NTV u otra traducción con copyright sin fuente/licencia legítima;
- separar translation / book coverage / canon profile / versification;
- si no existe corpus legítimo disponible, dejar la infraestructura lista y reportar bloqueo de contenido, no inventar datos.

### H — Search v2
- mejorar ranking/filtros sin romper:
  - 100 temas;
  - A–Z;
  - free-form separado;
  - whole-term;
  - `amor` no debe matchear `llamó`;
- cualquier mejora debe seguir explicable/determinista;
- no LLM/vector API runtime.

### I — RC02 release candidate
- `npm ci`
- tests
- typecheck
- Expo dependency check
- Android export/smoke
- prebuild/build release según workflow existente
- generar APK por GitHub Actions
- publicar artifact + SHA256 + exact HEAD
- preparar paquete de QA para instalación en teléfono.

## Development plane
El desarrollo se ejecuta en GitHub/web:
- Issues;
- commits/branches/PR cuando corresponda;
- GitHub Actions;
- artifacts;
- evidencia durable.

Local/ADB/emulador es opcional y auxiliar. Si no está disponible, no bloquea coding/CI/APK; sólo el gate que requiera evidencia runtime específica.

## Physical-device gate
La aceptación física final de RC02 se hará en el teléfono del Human, como en versiones anteriores.

El emulador es opcional para acelerar diagnóstico, no requisito canónico.

## Authorized Scope
Write:
- `apps/bible-topic-explorer/**`
- comentarios/evidencia en este Issue y #58
- workflow/CI existente sólo si es necesario para producir/verificar RC02, sin rediseñar el workflow canónico

Read-only:
- README.md
- .project/* salvo lectura
- evidencia histórica salvo lectura

Do not modify:
- README.md
- .project/*
- historias/EXP-01
- paths no relacionados

## Frozen invariants
Preservar:
- funcionamiento offline básico;
- navegación Android actual;
- safe areas;
- 100 temas;
- separación A–Z / free-form;
- whole-term;
- regresión `amor` / `llamó`;
- save/unsave existente;
- identidad técnica/package salvo decisión explícita;
- README exacto.

## Stop conditions
STOP y reportar sólo si:
- se requiere una decisión material de producto;
- se requiere incorporar contenido bíblico sin licencia/fuente legítima;
- una migración destructiva de historial Git se vuelve necesaria;
- un cambio fuera de scope es imprescindible;
- CI/build expone un defecto que impide continuar.

## Handoff final
Publicar:
- baseline;
- final HEAD;
- waves completadas;
- archivos cambiados;
- tests exactos;
- CI/build;
- artifact APK;
- SHA256;
- limitaciones;
- qué queda para prueba física.

Terminar exactamente con:
`READY FOR SUPERVISOR RC02 REVIEW`