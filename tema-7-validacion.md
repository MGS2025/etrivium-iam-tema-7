# Tema 7 — Checklist de Validación

> **Título oficial**: Ley 39/2015 (LPACAP): el procedimiento administrativo y los recursos administrativos. Concepto, naturaleza y principios generales. Fases del procedimiento. Los recursos administrativos: concepto y clases.
> **Versión**: 1.0 — Pendiente de validación
> **Fecha**: 2026-06-25
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es la **Ley 39/2015 (LPACAP)** en su versión consolidada.
- [ ] No se ha aportado material de cliente más allá del índice (`TEMA_07.docx`); el contenido se ha desarrollado desde el texto oficial del BOE.
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[LPACAP, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo de la Ley 39/2015, de la Ley 40/2015 o de la Constitución.

## 2. Estructura del contenido

- [ ] El `tema-7-indice.md` refleja fielmente la estructura de `tema-7-contenido.md`.
- [ ] Las secciones cubren: contexto/estructura de la Ley, concepto y naturaleza, principios, las cuatro fases (iniciación, ordenación, instrucción, terminación), el silencio, el acto administrativo (validez, eficacia, nulidad/anulabilidad), los tres recursos y la revisión de oficio.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayto de Madrid / IAM están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico (datos sensibles)

- [ ] Plazo supletorio para resolver: **3 meses**; tope legal **6 meses** salvo ley/UE [art. 21].
- [ ] Cómputo de plazos por **días hábiles** (excluidos sábados, domingos y festivos); inicio el día siguiente; meses/años de fecha a fecha [art. 30].
- [ ] Subsanación de solicitudes: **10 días (+5)**; efecto: desistimiento [art. 68].
- [ ] Informes: regla general **facultativos y no vinculantes** [art. 80].
- [ ] Audiencia **10-15 días** [art. 82]; información pública **≥ 20 días** [art. 83]; prueba **10-30 días** [art. 77].
- [ ] Silencio a solicitud: regla **positivo**, con las cinco excepciones del art. 24.1; **doble silencio** en alzada → estimatorio.
- [ ] Silencio de oficio: favorable **negativo**; desfavorable/sancionador **caducidad** [art. 25].
- [ ] Nulidad de pleno derecho: supuestos tasados del **art. 47** (incompetencia manifiesta por materia/territorio, contenido imposible, prescindir total del procedimiento…).
- [ ] Anulabilidad: cualquier infracción del ordenamiento, incluida la **desviación de poder** [art. 48]; defecto de forma solo anula si impide el fin o causa indefensión.
- [ ] Recurso de **alzada**: actos que no agotan la vía, superior jerárquico, **obligatorio**, interposición 1 mes (expreso), resolución **3 meses** [arts. 121-122].
- [ ] Recurso de **reposición**: actos que agotan la vía, mismo órgano, **potestativo**, interposición 1 mes (expreso), resolución **1 mes** [arts. 123-124].
- [ ] Recurso **extraordinario de revisión**: actos firmes, **cuatro causas tasadas**, plazo **4 años** (error de hecho) / **3 meses** (resto) [art. 125].
- [ ] Revisión de oficio de actos nulos: **art. 106** (sin plazo, dictamen favorable del órgano consultivo); declaración de lesividad de anulables: **art. 107** (4 años + contencioso).

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-7-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.
- [ ] El CSS de cada SVG está aislado por `scope_svg` en el generador (evita la colisión global de clases descubierta en el Tema 5).

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid / IAM.
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se priorizan los datos numéricos memorísticos (plazos, efectos del silencio, supuestos de nulidad).

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), con pestañas y motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencia cruzada al **Tema 1** (arts. 103, 105, 106, 9.3 CE) coherente.
- [ ] Referencia al **Tema 2** (Administración Local; órgano competente y fin de la vía administrativa) coherente.
- [ ] Referencia al **Tema 6** (interesados, derechos y registros como presupuesto del procedimiento) coherente.
- [ ] Referencia al **Tema 5** (procedimiento sancionador/disciplinario) coherente.
- [ ] Referencia al **Tema 8** (ejecutividad y apremio sobre el patrimonio en la recaudación de ingresos de derecho público) coherente.

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar (Jesús)

1. **⚠️ Dos erratas detectadas en el índice del cliente (`TEMA_07.docx`)**. El esqueleto indica:
   - Para el recurso de **alzada**: *"plazo (1 mes si expreso / 3 meses si silencio)"*.
   - Para el recurso de **reposición**: *"plazo (1 mes si expreso / 1 mes si silencio negativo)"*.
   Ambos plazos de "silencio" corresponden a la **derogada Ley 30/1992**. La **Ley 39/2015 vigente** (arts. 122.1 y 124.1) establece que, cuando el acto es **presunto**, el recurso puede interponerse **en cualquier momento** a partir del día siguiente a aquel en que se produzcan los efectos del silencio. **El contenido se ha redactado conforme a la ley vigente.** → Confirmar que se mantiene el criterio de la ley vigente (recomendado) y, si se desea, añadir una nota didáctica al margen sobre el cambio respecto de la Ley 30/1992.

2. **Alcance del tema**. El enunciado oficial se ciñe al procedimiento y los recursos, pero se ha incluido —por coherencia pedagógica y porque es materia recurrente en el test— una sección sobre el **acto administrativo** (validez, eficacia, notificación y, sobre todo, **nulidad/anulabilidad**, arts. 47-48) y otra sobre la **revisión de oficio** (arts. 106-111), que el índice del cliente sí contempla. → Confirmar que la profundidad de estas dos secciones es la adecuada para C1.

3. **Frontera con el Tema 6**. Los **interesados** (arts. 3-12), los **derechos** (art. 13) y los **registros** (arts. 16-17) se tratan en el Tema 6; aquí solo se citan como presupuesto. Los **términos y plazos** (arts. 29-33), aunque sistemáticamente están en el Título II, se han desarrollado en este Tema 7 por ser la "regla del cronómetro" de las fases. → Confirmar este reparto.

4. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 8 pestañas (con pestaña Índice)**, replicando el formato de los Temas 1-5.

5. **Balanceo automático A/B/C** mediante permutación determinista en `build_t7.py`.

### Puntos a vigilar (datos volátiles)

- El **sentido del silencio** en muchos procedimientos concretos del Ayuntamiento de Madrid (licencias, autorizaciones de dominio público) depende de la **ley sectorial** aplicable; los ejemplos del tema señalan la regla general y la excepción, pero conviene reverificar la norma sectorial concreta antes de cada convocatoria.
- La determinación de **qué órganos del Ayuntamiento de Madrid agotan la vía administrativa** (Alcalde, Junta de Gobierno, Pleno, órganos de los distritos) se rige por la **Ley 22/2006 de Capitalidad** y la **DA 15.ª LBRL**; los ejemplos del tema son orientativos.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
