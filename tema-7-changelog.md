# Tema 7 — Registro de cambios (changelog)

> Ley 39/2015 (LPACAP): el procedimiento administrativo y los recursos administrativos.

---

## v1.3 — 2026-10-06 — Revisión de diagramas

**Motivo**: barrido de los diagramas de los 40 temas tras la revisión jurídica y de normas.

### Cambios

- Revisión visual de todos los diagramas, captura a captura (la medición automática no detecta contraste, flechas mal dirigidas ni textos pegados al borde): corregidos textos que se salían de su caja o del lienzo, cajas que se tocaban, flechas que no llegaban a su destino y textos con poco contraste. Sin cambios de contenido.

---

## v1.2 — 2026-10-01 — Revisión jurídica

**Estado**: revisión jurídica aplicada; texto contrastado con el BOE consolidado (Ley 39/2015, Ley 40/2015, Constitución, Ley 7/1985 y Ley 22/2006; consulta 01/10/2026).

### Cambios de la revisión

- §3.3: «Eficacia (art. 103 CE): la actuación se orienta al resultado» (se suprime «no al rito por el rito»).
- §3.4 «La buena administración como principio transversal» eliminada entera (Carta de Derechos Fundamentales de la UE, fuera del enunciado del temario), con su caja; también las preguntas 26 y 27 del test y el bloque correspondiente del diagrama D3, que pasa a tres bloques.
- §3.2: se suprimen «Garantizan que la prueba y la deliberación se hagan con todas las garantías:» y «Es la garantía estrella del procedimiento.»; los incisos (art. 76) y (art. 82) se mantienen.
- §4.2: «Términos y plazos» sin la valoración sobre la «regla del cronómetro».
- §5.3: eliminada la caja de oficio favorable / desfavorable / a solicitud.
- §6.1: requisitos de validez con la redacción nueva («Para que sean válidos, se han de cumplir estos requisitos: que sean dictados por órgano competente (art. 34)…»).
- §7.1: suprimida la frase sobre la *reformatio in peius* en la resolución de los recursos.
- §7.3: «se interpone contra los actos que pongan fin a la vía administrativa (art. 123.1), ante el mismo órgano que dictó el acto».
- §8.3: eliminada la regla mnemotécnica de los «unos».
- Diagrama D1: deja de sugerir que la Ley 40/2015 se estudia en el Tema 7; los títulos de la Ley 39/2015 cuelgan expresamente de esa ley y la Ley 40/2015 figura como norma de apoyo (texto, conectores y `aria-label`).
- Fuentes: eliminadas la referencia al material de partida, la nota sobre erratas de ese material y la tabla Tier 2; el temario oficial BOAM 10.032 pasa a Tier 1. Validación: eliminada la referencia al material de partida y reformulado el punto sobre plazos de interposición contra actos presuntos.

### Reglas generales

- **Cajas**: «Dato clave examen» → «Dato clave»; «Ejemplo Ayto Madrid» → «Ejemplo de aplicación en el Ayto»; «Referencia cruzada» → «Relación con otros temas» (HTML, `.md` y `build_t7.py`). La leyenda ya no promete aparición en el test oficial; marcas en línea `[DATO CLAVE EXAMEN]` eliminadas y `[REFERENCIA CRUZADA: …]` → `[Relación con otros temas: …]`.
- **Citas de artículos**: «artículo» cuando la cita forma parte de la oración (§1.1, §2.3, §3, §5.2, §7.2, §8.1, casos, validación, diagramas); los paréntesis de inciso se mantienen.
- **Reflexiones eliminadas** fuera de las cajas (§2.1, §2.2, §2.3, §3.1, §5.2, §5.3, §6.4, §7.1) y **promesas sobre el examen** (leyenda, índice, validación).
- **Correcciones normativas** contra el BOE: doble silencio en el art. 24.1, **párrafo tercero** (antes «2.º»); excepciones al silencio estimatorio con el Derecho internacional y las razones imperiosas de interés general; efectos del silencio con la redacción del art. 24.2-4; art. 25.1 literal; cita del art. 24.3.b) literal; art. 77.2 (la prueba no se abre «porque lo pida el interesado»); arts. 79.1 y 80.2-3 (plazo de informes en el 80.2; el 80.3 permite suspender el plazo si el informe preceptivo no llega); art. 84.1 y art. 88.1, 88.2 y 88.5 (antes «88.5-6»); art. 94.4; art. 44 (sin «Tablón Edictal Único»); art. 45.1; art. 49.1; arts. 99 y 100; art. 112.1 completo y 112.3; art. 117.2 («cuando concurra», no «especialmente»); art. 118.1; art. 119.2; art. 124 (acto presunto; silencio de la reposición por los arts. 24.1 y 123.2); art. 125.1.b) y c) literales; art. 126.1 (inadmisión) y 126.3 (plazo de resolución), antes «126.2» y «126.1»; **lesividad: 4 años desde que se dictó el acto** (art. 107.2), no desde la notificación; art. 106.1 (órgano consultivo); la Ley 40/2015 no derogó la Ley 30/1992 (lo hace la disposición derogatoria única de la Ley 39/2015); definición de procedimiento tomada del preámbulo (apartado II); **fin de la vía administrativa en el ámbito local: art. 52.2 LBRL y art. 53 de la Ley 22/2006** (antes «disposición adicional 15.ª LBRL», que regula otra materia); **Ley 22/2006: BOE núm. 159 de 05/07/2006** (antes «núm. 182 de 01/08/2006»).
- **Test**: 150 preguntas mantenidas, con los mismos bloques; 11 sin cambios, 6 con cambios solo en distractores o referencia y 133 ajustadas al texto literal del precepto (enunciado, respuesta o distractores no verosímiles), de ellas unas 30 sustituidas por otra pregunta literal del mismo epígrafe (preguntas de concepto doctrinal, de buena administración, de *reformatio in peius* en recursos y de definiciones que no están en la ley). Respuestas correctas reequilibradas en el `.md` (50/50/50). Las 20 pedagógicas, revisadas y ajustadas al literal (P2 solo en la forma de citar el artículo).
- **Casos prácticos** 1-6 alineados con los cambios anteriores (en el caso 2, el informe del servicio en responsabilidad patrimonial es preceptivo, art. 81.1).

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
