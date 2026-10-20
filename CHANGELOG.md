# Changelog

*English first · [Español más abajo](#español)*

## English

### 0.1.3 · 2026-10-20

The web walkthrough has its own navigation ([workbench issue #2](https://github.com/SandraAcevedoA/serie-discernimiento-humano-creatividad-mediadaxAI---workbench/issues/2)). The panel index at the bottom (1 Creatividad · 2 Proceso · 3 Mediación · 4 Criterio) is now a set of links, followed by a direct jump to the lab. Panels 02–04 have an «inicio» link back to panel 01. The lab's stage bar has a «grounding» link back to panel 01, and «Volver al grounding» now goes to panel 01 instead of the last panel. On narrow screens the same links appear below the panel text. The text of the panels and the lab is unchanged.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| The web walkthrough in this repository is the one published at `themultiverse.school/x/pensamiento-creatividad`. | The contents of `<body>` in `interactive/recorrido-web/index.html` not appearing verbatim in the public page. | Text comparison against an anonymous request to the public page, 2026-10-20. | PASS |
| From every panel you can reach each of the four panels, the lab and (from panels 02–04) panel 01, and the lab's stage bar leads back to panel 01. | Any of the four new scripted checks failing. | Scripted run in Chromium at 1440, 1024 and 500 px wide, 2026-10-20. | PASS |
| The rest of the walkthrough still works opened as a local file: panels navigate, the last panel enters the lab, the lab runs from start to closing, answers persist, and there is no horizontal overflow on a narrow screen. | Any of the other 42 scripted checks failing. | Same run, 2026-10-20. | PASS |

### 0.1.2 · 2026-10-12

`LICENSE` added: CC BY-NC-SA 4.0, the same license as the series. `README.md` states it, together with the free use granted to The Multiverse School and Liz Howard.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| `LICENSE` is the official CC BY-NC-SA 4.0 legal code, unmodified, and the same file as in the series repository. | Any byte differing from `creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt` or from the `LICENSE` of `serie-discernimiento-creatividad`. | Byte comparison against both, 2026-10-12. | PASS |

### 0.1.1 · 2026-10-12

The syllabus now follows the published web walkthrough: the four grounding panels are Creatividad, Proceso, Mediación and Criterio, with the two cases the panels show; each lab stage uses the step names of the web; the closing includes reclaiming the work and the bridge to chapter 2. The vocabulary gains an annex by modality (image, sound and music, voice, object and design, creative writing) and its introduction describes the current workshop. The 200 qualities are unchanged.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| `curriculum/syllabus.md`, `resources/vocabulario-critico.md` and `resources/make-it-yours-es.md` are the documents published on the school's HedgeDoc. | Any byte differing from the `/download` of the HedgeDoc page linked for each file in `README.md`. | Byte comparison against anonymous downloads, 2026-10-12. | PASS |
| The 200 numbered qualities in the vocabulary are the same as in 0.1.0. | Any numbered row differing in its English term, its Spanish version or its question. | Scripted comparison of the 200 rows against the 0.1.0 file, 2026-10-12. | PASS |
| Every quality the syllabus names for image, text and sound has an entry in the vocabulary annex. | A term from those three lists in stage 2 of the syllabus with no matching entry. | Scripted search, 2026-10-12. | PASS |
| The syllabus names the same four panels and the same three lab stages as the web walkthrough. | A panel or stage title in `curriculum/syllabus.md` that does not appear in `interactive/recorrido-web/index.html`, or the reverse. | Scripted comparison of titles, 2026-10-12. | PASS |

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

### 0.1.3 · 2026-10-20

El recorrido web tiene navegación propia ([issue #2 del workbench](https://github.com/SandraAcevedoA/serie-discernimiento-humano-creatividad-mediadaxAI---workbench/issues/2)). El índice de paneles de abajo (1 Creatividad · 2 Proceso · 3 Mediación · 4 Criterio) ahora son enlaces, seguidos de un salto directo al laboratorio. Los paneles 02 a 04 tienen un enlace «inicio» que vuelve al panel 01. La barra de etapas del laboratorio tiene un enlace «grounding» que vuelve al panel 01, y «Volver al grounding» ahora lleva al panel 01 en vez del último panel. En pantallas angostas los mismos enlaces aparecen bajo el texto del panel. El texto de los paneles y del laboratorio no cambia.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| El recorrido web de este repositorio es el publicado en `themultiverse.school/x/pensamiento-creatividad`. | Que el contenido de `<body>` de `interactive/recorrido-web/index.html` no aparezca literal en la página pública. | Comparación de texto contra una petición anónima a la página pública, 2026-10-20. | PASS |
| Desde cada panel se llega a cada uno de los cuatro paneles, al laboratorio y (desde los paneles 02 a 04) al panel 01, y la barra de etapas del laboratorio vuelve al panel 01. | Que falle alguna de las cuatro comprobaciones automatizadas nuevas. | Recorrido automatizado en Chromium a 1440, 1024 y 500 px de ancho, 2026-10-20. | PASS |
| El resto del recorrido sigue funcionando abierto como archivo local: los paneles avanzan, el último panel entra al laboratorio, el laboratorio corre de inicio a cierre, las respuestas persisten y no hay desborde horizontal en pantalla angosta. | Que falle alguna de las otras 42 comprobaciones automatizadas. | El mismo recorrido, 2026-10-20. | PASS |

### 0.1.2 · 2026-10-12

Se agrega `LICENSE`: CC BY-NC-SA 4.0, la misma licencia de la serie. `README.md` lo declara, junto con el uso libre que se entrega a The Multiverse School y a Liz Howard.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| `LICENSE` es el texto legal oficial de CC BY-NC-SA 4.0, sin modificar, y el mismo archivo del repositorio de la serie. | Cualquier byte distinto de `creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt` o del `LICENSE` de `serie-discernimiento-creatividad`. | Comparación byte a byte contra ambos, 2026-10-12. | PASS |

### 0.1.1 · 2026-10-12

El syllabus ahora sigue el recorrido web publicado: los cuatro paneles de grounding son Creatividad, Proceso, Mediación y Criterio, con los dos casos que muestran los paneles; cada etapa del laboratorio usa los nombres de los pasos de la web; el cierre incluye reclamar el trabajo y el paso al capítulo 2. El vocabulario suma un anexo por modalidad (imagen, sonido y música, voz, objeto y diseño, texto creativo) y su introducción describe el workshop actual. Las 200 cualidades no cambian.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| `curriculum/syllabus.md`, `resources/vocabulario-critico.md` y `resources/make-it-yours-es.md` son los documentos publicados en el HedgeDoc de la escuela. | Cualquier byte distinto del `/download` de la página de HedgeDoc enlazada para cada archivo en `README.md`. | Comparación byte a byte contra descargas anónimas, 2026-10-12. | PASS |
| Las 200 cualidades numeradas del vocabulario son las mismas que en la 0.1.0. | Cualquier fila numerada que difiera en su término en inglés, su versión en español o su pregunta. | Comparación automatizada de las 200 filas contra el archivo de la 0.1.0, 2026-10-12. | PASS |
| Cada cualidad que el syllabus nombra para imagen, texto y sonido tiene una entrada en el anexo del vocabulario. | Un término de esas tres listas de la etapa 2 del syllabus sin entrada correspondiente. | Búsqueda automatizada, 2026-10-12. | PASS |
| El syllabus nombra los mismos cuatro paneles y las mismas tres etapas de laboratorio que el recorrido web. | Un título de panel o de etapa en `curriculum/syllabus.md` que no aparezca en `interactive/recorrido-web/index.html`, o al revés. | Comparación automatizada de títulos, 2026-10-12. | PASS |

### 0.1.0 · 2026-10-12

Primera versión: el material del workshop que ya es público en The Multiverse School, reunido en un solo lugar. Syllabus, recorrido web y los dos recursos que usa la sesión. Todavía sin archivo de licencia.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| `curriculum/syllabus.md`, `resources/vocabulario-critico.md` y `resources/make-it-yours-es.md` son los documentos publicados en el HedgeDoc de la escuela. | Cualquier byte distinto del `/download` de la página de HedgeDoc enlazada para cada archivo en `README.md`. | Comparación byte a byte contra descargas anónimas, 2026-10-12. | PASS |
| El recorrido web de este repositorio es el publicado en `themultiverse.school/x/pensamiento-creatividad`. | Que el contenido de `<body>` de `interactive/recorrido-web/index.html` no aparezca textualmente en la página pública. | Comparación de texto contra una petición anónima a la página pública, 2026-10-12. | PASS |
| El recorrido funciona abierto como archivo local: los paneles navegan, el último panel entra al laboratorio, el laboratorio corre de inicio a cierre, las respuestas persisten y no hay desborde horizontal en teléfono. | Que falle alguna de las 42 comprobaciones automatizadas. | Recorrido automatizado en Chromium a 1440 px y 400 px de ancho, 2026-10-12. | PASS |
| Todos los links externos de `README.md` abren sin iniciar sesión. | Que alguna de esas URLs responda algo distinto de 200 a una petición anónima. | Petición HTTP anónima a cada URL, 2026-10-12. | PASS |
