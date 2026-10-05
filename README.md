# CV — Pedro Giovanni Ricra Figueroa

Repositorio de currículum: plantilla base reutilizable + CV real actualizado. Sin código, sin dependencias, sin build.

## Descripción

- `CV - plantilla.docx`: plantilla genérica para puestos tecnológicos (datos, resumen, habilidades, experiencia, proyectos, educación, certificaciones). Con instrucciones y placeholders para duplicar y adaptar.
- `CV - RFPG.docx`: CV completo de Pedro Giovanni Ricra Figueroa — Estudiante de Ingeniería de Sistemas (IX ciclo, UNU), Desarrollo de Software.

Contacto: +51 922 149 396 · pedro.ricra.figueroa@gmail.com · Pucallpa, Perú · [GitHub](https://github.com/TeVerde29) · [LinkedIn](http://www.linkedin.com/in/pedro-giovanni-ricra-figueroa-971a20433)

> Nota: este repo no tiene `.github/copilot/` ni `copilot-instructions.md`. Este README se generó desde el contenido real de los `.docx`.

## Stack tecnológico

Repositorio:

- Documentos Word `.docx`, editables en Microsoft Word / LibreOffice / Google Docs.
- Sin lenguajes, frameworks, dependencias, build ni tests.

Perfil descrito en `CV - RFPG.docx`:

- Lenguajes: Java, Python, TypeScript, JavaScript, SQL.
- Frontend: Angular, HTML5, CSS3, Figma, Balsamiq.
- Backend/APIs: Node.js, Spring Boot, REST, Postman, Swagger UI.
- Datos: MySQL, SQL Server, JSON.
- Testing: Selenium IDE, pruebas funcionales, Python + Google Colab.
- Herramientas: Git, GitHub, Docker, Docker Compose, Electron, Leaflet.js, Chart.js, SheetJS, jsPDF.

## Arquitectura del repositorio

```text
CV/
├── CV - plantilla.docx   # plantilla genérica (fuente para nuevas versiones)
└── CV - RFPG.docx        # CV real, versión fuente actualizada
```

Flujo simple: duplicar plantilla → adaptar → exportar a PDF. `CV - RFPG.docx` es la referencia de contenido completo.

## Requisitos

- Editor `.docx`: Microsoft Word (recomendado), LibreOffice Writer o Google Docs.
- Sin instalación ni configuración adicional.

## Uso

1. Duplica `CV - plantilla.docx` para una nueva postulación.
2. Reemplaza `[PLACEHOLDERS]`, elimina secciones que no apliquen.
3. Edita `CV - RFPG.docx` solo como versión fuente del perfil real.
4. Exporta a PDF para postular (Word: Archivo → Exportar → PDF).

## Estructura del contenido

Plantilla (`CV - plantilla.docx`):

- Datos de contacto, resumen profesional (3-5 líneas), habilidades por bloques (lenguajes, software, datos/IA, cloud/DevOps, QA/seguridad, herramientas/metodologías), experiencia, proyectos, educación, idiomas, certificaciones.

CV real (`CV - RFPG.docx`):

- Resumen: Ingeniería de Sistemas IX ciclo, full-stack y testing, Scrum.
- Experiencia: Practicante OTI-UNU (04/2025–07/2025) — sistema de Posgrado, modelo de datos, metodología de pruebas en 5 etapas para AURA, 25 funcionalidades en 8 módulos automatizadas, 12 fallos documentados, registro biométrico.
- Educación: Ingeniería de Sistemas, UNU, 2022–actualidad.
- Certificaciones: CONEIMERA — 1er puesto programación competitiva UNTELS 2024, participación académica UNT 2025.

## Proyectos destacados

1. **Sistema de Reporte de Incidencias UNU (2025)** — web full-stack para incidencias del campus. Módulo estudiante (registro/consulta/edición con foto, tipo y ubicación). Stack: Angular, Node.js, MySQL. [Código](https://github.com/TeVerde29/Reportes_UNU) · [Demo](https://reportes-unu.vercel.app/).
2. **Asignador Heurístico de Redes Logísticas (2026)** — optimización almacén-zona sobre mapa real, distancias por calle + fallback, KPIs de costo/distancia/utilización. Stack: JS Vanilla, Leaflet.js, HTML, CSS, JSON. [Código](https://github.com/TeVerde29/Asignador-Heuristico-de-Redes-Logisticas) · [Demo](https://teverde29.github.io/Asignador-Heuristico-de-Redes-Logisticas/).
3. **RotaStock Plus (2026)** — escritorio offline para almacén: FIFO, semaforización, ABC/XYZ, plan de compras, conteos auditables, PDF/Excel, backups automáticos. Stack: JS Vanilla, Electron, Chart.js, SheetJS, jsPDF. [Código](https://github.com/TeVerde29/RotaStock-Plus) · [Instalador v2.0.0](https://github.com/TeVerde29/RotaStock-Plus/releases/tag/v2.0.0).

## Flujo de trabajo

- Rama principal: `main`.
- Cambio típico: editar `.docx` → revisar en Word → commit → push.
- Mantén `CV - RFPG.docx` como fuente de verdad; no bifurques el historial en múltiples CVs dentro del repo.
- Commits en español, imperativos, tipo `docs(cv): ...`.

## Estándares de edición

- Español, conciso, sin faltas; fechas `MM/AAAA`, ubicación `Ciudad, País`.
- Experiencia/proyectos con 2-4 bullets: qué + impacto + stack/herramientas + enlaces verificables.
- No dejar `[PLACEHOLDERS]` en versiones finales ni datos de contacto de ejemplo.
- Nombres de archivo con versión/fecha si generas variantes: `CV-RFPG-2026-02.pdf`.

## Tests

No aplica. Verificación manual: abrir el `.docx`, comprobar paginación en 1-2 páginas, enlaces clicables y exportación limpia a PDF.

## Contribución

Repo personal. Para sugerencias: abre un issue o PR con el cambio propuesto en el `.docx` y el motivo (puesto objetivo, sección afectada).

## Licencia

Sin licencia definida. Contenido personal de Pedro Giovanni Ricra Figueroa. La plantilla puede reutilizarse como base propia; no se garantiza uso libre por terceros.
