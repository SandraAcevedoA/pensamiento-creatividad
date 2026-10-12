# Changelog

*English first · [Español más abajo](#español)*

## English

### 0.1.0 · 2026-10-12

First version: the workshop material that is already public at The Multiverse School, gathered in one place. Syllabus, web walkthrough and the two resources the session uses. No license file yet.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| `curriculum/syllabus.md`, `resources/vocabulario-critico.md` and `resources/make-it-yours-es.md` are the documents published on the school's HedgeDoc. | Any byte differing from the `/download` of the HedgeDoc page linked for each file in `README.md`. | Byte comparison against anonymous downloads, 2026-10-12. | PASS |
| The web walkthrough in this repository is the one published at `themultiverse.school/x/pensamiento-creatividad`. | The contents of `<body>` in `interactive/recorrido-web/index.html` not appearing verbatim in the public page. | Text comparison against an anonymous request to the public page, 2026-10-12. | PASS |
| The walkthrough works opened as a local file: panels navigate, the last panel enters the lab, the lab runs from start to closing, answers persist, and there is no horizontal overflow on a phone. | Any of the 42 scripted checks failing. | Scripted run in Chromium at 1440 px and 400 px wide, 2026-10-12. | PASS |
| Every external link in `README.md` opens without logging in. | Any of those URLs returning something other than 200 from an anonymous request. | Anonymous HTTP request to every URL, 2026-10-12. | PASS |

---

## Español

### 0.1.0 · 2026-10-12

Primera versión: el material del workshop que ya es público en The Multiverse School, reunido en un solo lugar. Syllabus, recorrido web y los dos recursos que usa la sesión. Todavía sin archivo de licencia.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| `curriculum/syllabus.md`, `resources/vocabulario-critico.md` y `resources/make-it-yours-es.md` son los documentos publicados en el HedgeDoc de la escuela. | Cualquier byte distinto del `/download` de la página de HedgeDoc enlazada para cada archivo en `README.md`. | Comparación byte a byte contra descargas anónimas, 2026-10-12. | PASS |
| El recorrido web de este repositorio es el publicado en `themultiverse.school/x/pensamiento-creatividad`. | Que el contenido de `<body>` de `interactive/recorrido-web/index.html` no aparezca textualmente en la página pública. | Comparación de texto contra una petición anónima a la página pública, 2026-10-12. | PASS |
| El recorrido funciona abierto como archivo local: los paneles navegan, el último panel entra al laboratorio, el laboratorio corre de inicio a cierre, las respuestas persisten y no hay desborde horizontal en teléfono. | Que falle alguna de las 42 comprobaciones automatizadas. | Recorrido automatizado en Chromium a 1440 px y 400 px de ancho, 2026-10-12. | PASS |
| Todos los links externos de `README.md` abren sin iniciar sesión. | Que alguna de esas URLs responda algo distinto de 200 a una petición anónima. | Petición HTTP anónima a cada URL, 2026-10-12. | PASS |
