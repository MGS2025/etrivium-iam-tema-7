# Tema 7 — Registro de cambios (changelog)

> Ley 39/2015 (LPACAP): el procedimiento administrativo y los recursos administrativos.

---

## v1.1 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~7.800 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 12-14 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.0 — 2026-06-25 (generación inicial, pendiente de validación)

**Primera versión completa del Tema 7**, generada desde el texto oficial de la Ley 39/2015 (BOE), siguiendo la estructura validada de los Temas 1-5 del bloque administrativo.

### Contenido

- 8 secciones teóricas: (1) contexto y estructura de la LPACAP y relación con el Tema 6; (2) concepto y naturaleza del procedimiento (art. 105 CE); (3) principios generales; (4) fases de iniciación, ordenación e instrucción; (5) terminación y silencio administrativo; (6) el acto administrativo (validez, eficacia, nulidad y anulabilidad); (7) los tres recursos administrativos; (8) revisión de oficio y esquema-resumen.
- 12 diagramas SVG (paleta Ayto Madrid, CSS aislado por `scope_svg`).
- 150 preguntas de test (formato examen) + 20 preguntas pedagógicas comentadas.
- 6 casos prácticos aplicados a procedimientos del Ayuntamiento de Madrid / IAM.
- 8 pestañas en `index.html` (Inicio, Índice, Contenido, Diagramas, Test, Casos, Validación, Fuentes), con motor de test y penalización 1/3.

### Decisiones de generación

- **Sin material de cliente** más allá del índice (`TEMA_07.docx`): contenido desarrollado desde el BOE.
- **Erratas del índice corregidas**: el esqueleto del cliente arrastraba los plazos de silencio de la **derogada Ley 30/1992** para alzada ("3 meses") y reposición ("1 mes"); se ha redactado conforme a la **Ley 39/2015 vigente** (interposición "en cualquier momento" si el acto es presunto, arts. 122.1 y 124.1). Anotado en `tema-7-validacion.md` para confirmación de Jesús.
- **Refs cruzadas** validadas contra el temario oficial BOAM 10.032: T1, T2, T5, T6, T8.
- **Balanceo A/B/C** automático por permutación determinista en `build_t7.py` (semilla fija).

### Pendiente

- Validación de María / Ana (IAM) y de Jesús Cuadrado (IAM).
- Confirmación de los 3 puntos abiertos en la pestaña Validación (criterio de plazos de silencio, profundidad de las secciones de acto y revisión de oficio, reparto de los términos y plazos con el Tema 6).
