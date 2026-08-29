# pablo-exegesis-robbins

> **Parte del set `Hermes2-` de [PabloRuizD](https://github.com/PabloRuizD).** Esta skill fue generada con asistencia de Hermes2 para uso del agente personal de Pablo Ruiz Danegger (Instituto Técnico UNT Tucumán).

📂 **Categoría:** 🕊 Religiones y Filosofía
🏷️ **Tipo:** Wrapper (fork simbólico)

## Descripción

Analyse socio-rhétorique des textes bibliques (méthode de Vernon Robbins). Utilisez ce skill lorsque l'utilisateur demande une analyse "synchronique", une "analyse socio-rhétorique", l'étude des "textures" du texte (interne, socio-culturelle, idéologique), ou cherche à comprendre comment la forme littéraire d'un récit biblique subvertit les normes sociales, religieuses et de pouvoir (honneur/honte, pureté).

## Origen

- **Upstream:** https://github.com/ronanguilloux/skill-theo
- **Autor del port:** Pablo Agustín Ruiz Danegger con Hermes2 (agosto 2026)
- **Propósito:** marcar y disponibilizar esta skill para el agente personal Hermes2, en una cuenta separada para evitar confusión con otros repos de Pablo.

## Instalación

### Opción A — Descarga directa

```bash
git clone https://github.com/PabloRuizD/Hermes2-pablo-exegesis-robbins.git
mkdir -p ~/.hermes/skills/pablo-exegesis-robbins
cp -r Hermes2-pablo-exegesis-robbins/* ~/.hermes/skills/pablo-exegesis-robbins/
```

### Opción B — Como submódulo

```bash
mkdir -p ~/.hermes/skills/pablo-exegesis-robbins
git submodule add https://github.com/PabloRuizD/Hermes2-pablo-exegesis-robbins.git ~/.hermes/skills/pablo-exegesis-robbins/source
```

## Estructura

```
pablo-exegesis-robbins/
├── SKILL.md           # Definición técnica (frontmatter YAML + cuerpo Markdown)
├── README.md          # Este archivo
├── LICENSE            # Licencia MIT
└── .gitignore
```

Si la skill incluye datos locales (textos, corpus, datasets), los encontrarás en subcarpetas dentro del repo según se defina en `SKILL.md`.

## Uso

Una vez instalada en `~/.hermes/skills/pablo-exegesis-robbins/`, el agente Hermes2 carga automáticamente la skill y la activa cuando tu pedido contenga los triggers listados en `SKILL.md`.

Ejemplo:
```
Usuario: "<algún trigger de la skill>"
Hermes2: invoca la skill, carga references/, ejecuta scripts/ si aplica.
```

## Licencia

- **Código (SKILL.md, README.md, scripts propios):** MIT — ver `LICENSE`.
- **Datos del upstream (si aplica):** ver la sección "Origen" arriba; cada upstream mantiene su propia licencia (CC-BY, CC-BY-SA, ODbL, MIT, o Public Domain según el caso).

## Aviso

Esta skill fue generada con asistencia de IA. Verificar los outputs antes de uso en producción. Para correcciones o ampliaciones, abrir un issue en el repositorio.

---

*Generado: 2026-08-29 · Hermes2 para Pablo Ruiz Danegger*
