# CLAUDE.md — awesome-extremadura

## Propósito

Selección de software open source que da **soporte específico a Extremadura** — su gobierno autonómico (Junta de Extremadura), ayuntamientos, universidades, empresas, infraestructuras y patrimonio. Todo el contenido en español. El foco es Extremadura: el software debe dirigirse específicamente a esta comunidad autónoma o a sus municipios.

## Ámbito

- **2 provincias**: Badajoz, Cáceres.
- Principales ciudades: Mérida (capital), Badajoz, Cáceres, Plasencia, Don Benito, Almendralejo, Villanueva de la Serena, Navalmoral de la Mata, Zafra.
- **Universidad**: UEX (Universidad de Extremadura — campuses en Badajoz, Cáceres, Mérida, Plasencia).
- **Instituciones**: Junta de Extremadura (Juntaex), gnuLinEx (distribución Linux histórica), CENATIC (Centro Nacional de Referencia de Aplicación de las TIC, con sede en Almendralejo), AUPEX (Asociación de Universidades Populares de Extremadura).

## Criterios de inclusión

### Incluir

- Software que interactúa con la **Junta de Extremadura** o sus organismos (Sede Electrónica, Portal de Transparencia, datos abiertos).
- Herramientas para **ayuntamientos** de Extremadura (Mérida, Badajoz, Cáceres, Plasencia, etc.).
- Software de la **UEX** (Universidad de Extremadura) cuando sea específico de la región o la universidad.
- Herramientas de **datos abiertos** de Extremadura.
- Software relacionado con **gnuLinEx** (la histórica distribución Linux de la Junta de Extremadura).
- Herramientas del **CENATIC** (Centro Nacional de Referencia de Aplicación de las TIC).
- Software de **transporte** extremeño.
- Herramientas de **cartografía y SIG** específicas de Extremadura (IDEEX).
- Herramientas de **turismo y patrimonio** de la región (Mérida romana, Cáceres medieval, Guadalupe, etc.).
- Software de **energía y agua** regional.
- Proyectos de **smart cities** para ciudades extremeñas.
- Software sobre **deportes** extremeños.
- Proyectos del **sistema sanitario extremeño** (SES — Servicio Extremeño de Salud).
- Software **educativo** específico de la región (Rayuela, centros educativos).
- Herramientas de **agricultura y dehesa** extremeña (ibérico, corcho, aceite).
- Software de **meteorología** regional.
- Proyectos de **industria y empresa** extremeña.

### No incluir

- Software **genérico** que funciona en toda España sin funcionalidad específica de Extremadura — eso pertenece a awesome-spain.
- Software de **ámbito europeo** — eso pertenece a awesome-europe.
- Software de **otras comunidades autónomas** españolas.
- Software creado por extremeños que **no tiene funcionalidad específica** de la región.
- Repositorios **archivados o de solo lectura** — van a `DELETED.md`.
- Repos donde el autor indica que el proyecto está **roto, sin mantenimiento o deprecado**.
- Repos **sin README significativo** o que son claramente repos de test/experimento.
- Ejercicios de clase o trabajos académicos sin utilidad real.

### Zona gris — usar criterio

- Proyectos de la UEX que podrían ser genéricos — incluir si tienen datos o configuración específica de Extremadura.
- Software que cubre Extremadura junto con otras regiones — incluir si Extremadura es un foco principal.

## Estándares de calidad

**Mismo listón que [awesome-spain](https://github.com/GeiserX/awesome-spain):**

- **No repos archivados**: si se descubre archivado tras la inclusión, mover a `DELETED.md` inmediatamente.
- **No repos extremadamente sin mantenimiento**: al menos un commit en los últimos 3 años, salvo que sea un proyecto claramente estable/completo.
- **No repos rotos**: si el README dice «deprecated», «no longer maintained», «use X instead» o similar — no incluir. Mover a `DELETED.md` si ya está listado.
- **Estrellas mínimas**: preferir repos con al menos unas pocas estrellas, pero herramientas nicho excepcionales con 0-1 estrellas pueden incluirse si cubren un hueco importante.
- **Verificar cada repo** antes de añadir: comprobar `archived`, `pushed_at`, `stargazers_count` vía `gh api repos/owner/name`.

## Formato de entrada

```markdown
- [Nombre](https://github.com/owner/repo) [![Stars](...)](stargazers) [![Last Commit](...)](commits) [![Language](...)](repo) [![License](...)](LICENSE) [![Tag](...)](url) - Descripción que empieza en mayúscula y termina con punto.
```

Las insignias se generan automáticamente. Para contribuir, basta con añadir la entrada en formato simple:

```markdown
- [Nombre](https://github.com/owner/repo) - Descripción que empieza en mayúscula y termina con punto.
```

- La descripción **no debe empezar con el nombre** del proyecto.
- Máximo una línea por entrada.
- Entradas en **orden alfabético** dentro de cada categoría.
- Categorías en **orden alfabético** en el índice y en el cuerpo del documento.
- Entradas en `DELETED.md` también en **orden alfabético** dentro de cada sección.

## Verificación antes de añadir

Antes de incluir un repositorio, comprobar:

- **Existe y es público**: el enlace de GitHub funciona y el repo no es privado.
- **No está archivado o de solo lectura**: si archivado, va a `DELETED.md` (sección «Archivados»).
- **No está deprecado**: comprobar si el README dice «deprecated», «unmaintained», «broken», «use X instead».
- **Actividad razonable**: al menos un commit en los últimos 3 años, salvo que sea un proyecto estable/completo.
- **No es un duplicado**: cruzar con `README.md` y `DELETED.md`.
- **Calidad mínima**: tiene documentación (README) y no es un repositorio vacío o de test.

## Pull requests y contribuciones

- Las PRs deben usar la plantilla en `.github/PULL_REQUEST_TEMPLATE.md`.
- **Obligatorio**: incluir en la PR la **URL del servicio, API o institución extremeña** a la que el software da soporte.
- Plantillas de issues disponibles para sugerir proyectos (`anadir-proyecto.md`) y solicitar retirada (`retirar-proyecto.md`).

## Estructura

- Secciones con `##`, subsecciones con `###`.
- Índice de contenido al principio entre comentarios `<!--lint disable/enable awesome-list-item-->`.
- Al final: sección Contribuir, Nota y Descargo de responsabilidad (como párrafos en negrita, no encabezados ##).

## Temas prohibidos

No se aceptan proyectos relacionados con: pornografía, contenido NSFW, loterías o apuestas, religión, política partidista.

## Difusión

- Notificar a los propietarios de repos abriendo un issue titulado «Listado en awesome-extremadura» con un breve mensaje en español (tuteo) ofreciendo retirar si lo prefieren. Solo 1 issue por organización/usuario — no spamear repos del mismo propietario.
- Publicar en comunidades extremeñas tras alcanzar masa crítica.
- Enviar PR a [sindresorhus/awesome](https://github.com/sindresorhus/awesome) tras 30 días desde la creación del repo.

## Aprendizajes

- Extremadura tiene una historia extraordinaria con el software libre gracias a **gnuLinEx** (2004), una de las primeras distribuciones Linux impulsadas por un gobierno en el mundo. Sin embargo, la presencia actual en GitHub es muy limitada.
- La Junta de Extremadura **no tiene organización GitHub** oficial (a diferencia de la CARM en Murcia con `carm-es`).
- **CENATIC** (Centro Nacional de Referencia de TIC, en Almendralejo) fue un referente de software libre, pero no tiene repos públicos.
- **AUPEX** no tiene presencia en GitHub.
- **IE-Extremadura** es una organización con repos ODS (Objetivos de Desarrollo Sostenible) para Extremadura.
- La **UEX** no tiene organización GitHub oficial. Los repos son de profesores/estudiantes individuales. `mhaut/Templates` es el más útil (plantillas LaTeX).
- Las búsquedas por ciudades (Badajoz, Cáceres, Mérida) producen pocos resultados. Mérida se confunde con Mérida (México/Venezuela).
- La mayoría de repos con "extremadura" son ejercicios de clase, proyectos de turismo genéricos o repos vacíos.
- `cahergil/Farmacias` tiene 5 estrellas pero dice "Deprecated!" en la descripción — va a DELETED.md.
- `dondanndy/ExtCOVIDdata` es el dataset mejor documentado con datos CSV de la Junta por núcleo de población.
- `CarlosGamer98YT/gnuLinEx` es una revitalización moderna (2026) de gnuLinEx sobre Debian 13 Trixie.
- GitLab no tiene repos significativos sobre Extremadura.

*Generated by [LynxPrompt](https://lynxprompt.com) CLI*
