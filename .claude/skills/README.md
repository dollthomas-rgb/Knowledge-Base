# Claude-Code-Skills

Dieser Ordner enthält **echte Claude-Code-Skills**. Claude lädt sie in jeder Session in
diesem Repo automatisch und nutzt sie, wenn eine Aufgabe zur `description` eines Skills passt.

## Aufbau

```
.claude/skills/
├── README.md            ← diese Datei
└── <skill-name>/
    └── SKILL.md         ← Definition des Skills (Pflicht)
```

## SKILL.md-Format

Jede `SKILL.md` beginnt mit YAML-Frontmatter:

```markdown
---
name: skill-name
description: Was der Skill tut und wann er greifen soll (konkrete Auslöser nennen).
---

# Inhalt / Anleitung des Skills
```

- **name:** muss zum Ordnernamen passen, klein, mit Bindestrich.
- **description:** das wichtigste Feld – Claude entscheidet anhand der Beschreibung, ob der
  Skill zur aktuellen Aufgabe passt. Beschreibe **was** und **wann**.

## Neuen Skill anlegen

Nutze die Vorlage [`../../Vorlagen/Skill-Vorlage.md`](../../Vorlagen/Skill-Vorlage.md) und
lege den neuen Ordner hier ab. Siehe `beispiel-skill/` als funktionierendes Beispiel.
