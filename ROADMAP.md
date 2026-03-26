# Mobile Forensics Lab - Roadmap

Esta hoja de ruta organiza el desarrollo del proyecto **Mobile Forensics Lab**, desde la preparación inicial hasta la gestión de contribuciones y mantenimiento continuo. 


```mermaid
flowchart TD
    F0[Fase 0: Preparación del proyecto 📌]
    F1[Fase 1: Contribuciones y comunidad 🤝]
    F2[Fase 2: Automatización ⚙️]
    F3[Fase 3: Contribuciones 🤝]
    F4[Fase 3: Documentación y experiencia educativa 📚]
    F5[Fase 4: Laboratorios 🧪]
    F6[Fase 5: Versionado y releases 🏷️]
    F7[Fase 6: Portal educativo y visibilidad 🌐]
    F8[Fase 7: Mantenimiento 🔧]

    F0 --> F1 --> F2 --> F3 --> F4 --> F5 --> F6 --> F7 -> F8
```


## Fase 0: Preparación del proyecto 📌

- [ ] Definir alcance de `Mobile-Forensics-Lab`. 
- [ ] Definir estructura inicial del proyecto.
- [ ] Crear estructura inicial de carpetas. 
- [ ] Configurar README inicial. 
- [ ] Definir licencias para la documentación, laboratorio, código, y otros recursos. 
- [ ] Configurar badges iniciales en README. 


## Fase 1: Contribuciones y comunidad 🤝

- [ ] Crear templates para labs, casos de estudio y guías. 
- [ ] Crear `CONTRIBUTING.md` con:
    - Cómo crear labs, casos de uso yguías nuevas, y proponer datasets.
    - Cómo documentar scripts.
    - Estilo Markdown y documentación.
    - Proceso de Pull Request. 
- [ ] Crear `CODE_OF_CONDUCT.md`.
- [ ] Configurar plantillas de Issues y Pull Requests en `.github/`.
- [ ] Crear sistema de etiquetado para Issues.
- [ ] Definir roles: `mantenedor`, `colaborador`, `reviewer`.


## Fase 2: Automatización ⚙️

- [ ] Crear herramientas para validación local. 
- [ ] Workflow de validación de Markdown (`validate-markdown.yml`)
- [ ] Workflow de generación de PDF único de `docs/` (`build-docs-pdf.yml`)
- [ ] Workflow para publicar PDF en Release automáticamente (`docs-release.yml`)
- [ ] Workflow opcional para generar HTML de docs y publicar en GitHub Pages
- [ ] Configurar badges necesarios en README:
    - Build ✅
    - PDF disponible 📄
    - Docs online 🌐
    - License 🛠
    - Stars ⭐
    - Release 📦


## Fase 3: Documentación y experiencia educativa 📚

- [ ] Crear ruta de aprendizaje. 
- [ ] Completar `docs/` con:
    - Fases del análisis forense Android
    - Fundamentos técnicos
    - Buenas prácticas
    - Formatos para registro del proceso forense. 
- [ ] Revisar que la documentación sea comprensible y motivadora para el aprendizaje.
    - Revisión por pares y expertos. 
    - Realizar ajustes necesarios.  
- [ ] Generar PDF y HTML de documentación base.
- [ ] Lanzamieto versión estable de la documentación. 


## Fase 4: Laboratorios 🧪

- [ ] Crear ruta inicial de laboratorios prácticos. 
- [ ] Creación de primeros 3 laboratorios prácticos. 
- [ ] Creación de guías. 
- [ ] Creación de Issues para contribución. 


## Fase 5: Versionado y releases 🏷️

- [ ] Cada versión estable de `docs/` → PDF único → Release en GitHub.
- [ ] Labs se mantienen actualizables independientemente.
- [ ] Añadir badge de última release en README.
- [ ] Mantener historial de releases para estudiantes y colaboradores.


## Fase 6: Portal educativo y visibilidad 🌐

- [ ] Configurar branding.
- [ ] Publicar HTML de docs en GitHub Pages.
- [ ] Promocionar proyecto en:
    - Grupos de estudiantes y académicos
    - Foros de seguridad y forense móvil
    - Redes sociales, académcias y técnicas. 
- [ ] Incentivar contribuciones externas con “issues beginner” o “good first lab”


## Fase 7: Mantenimiento continuo 🔧

- [ ] Revisar workflows de Actions regularmente.
- [ ] Actualizar PDF y HTML con cambios en docs.
- [ ] Revisar PRs y contribuciones de la comunidad.
- [ ] Añadir nuevos labs, datasets y casos de estudio.
- [ ] Monitorear badges y visibilidad del proyecto.
- [ ] Actualización periódica de README del proyecto y secciones. 