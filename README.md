# ETRIVIUM · IAM — Tema 7

**Ley 39/2015 (LPACAP): El procedimiento administrativo y los recursos administrativos**

Material de estudio para la oposición de **Técnico Auxiliar TIC (C1)** del **Ayuntamiento de Madrid**, bloque Administrativo/Jurídico.

🔗 **Material interactivo**: https://mgs2025.github.io/etrivium-iam-tema-7/

## Contenido

- **Concepto, naturaleza y principios** del procedimiento administrativo (fundamento en el art. 105 CE).
- **Las cuatro fases**: iniciación, ordenación, instrucción y terminación.
- **El silencio administrativo** (a solicitud vs de oficio).
- **El acto administrativo**: validez, eficacia, notificación, nulidad y anulabilidad.
- **Los recursos administrativos**: alzada, reposición y extraordinario de revisión.
- **La revisión de oficio**.

## Estructura del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | Material interactivo autosuficiente (8 pestañas + test) |
| `tema-7-indice.md` | Índice y conceptos clave |
| `tema-7-contenido.md` | Contenido teórico (8 secciones) |
| `tema-7-diagramas.md` | 12 diagramas SVG |
| `tema-7-test.md` | 150 preguntas + 20 pedagógicas |
| `tema-7-caso-practico.md` | 6 casos prácticos |
| `tema-7-fuentes.md` | Registro de fuentes y normas de citación |
| `tema-7-validacion.md` | Checklist de validación (María/Ana) |
| `tema-7-changelog.md` | Registro de cambios |
| `build_t7.py` | Generador del `index.html` desde los `.md` |
| `_build_css.txt` | Hoja de estilos del `index.html` |

## Regenerar el `index.html`

```bash
python3 build_t7.py
```

El `index.html` se **genera** desde los `.md` (no se edita a mano), de modo que siempre queda sincronizado con el contenido fuente.

---

© MARKETINGLOBALSEO · ETRIVIUM — Material de preparación IAM. Versión 1.0 (pendiente de validación).
