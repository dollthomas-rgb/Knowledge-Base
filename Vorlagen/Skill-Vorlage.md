# Vorlage: Neuer Claude-Code-Skill

So legst du einen neuen Skill an, den Claude in diesem Repo automatisch erkennt.

## Ablageort

```
.claude/skills/<skill-name>/SKILL.md
```

- `<skill-name>`: kurz, klein geschrieben, mit Bindestrich (z. B. `fmea-rpz-rechner`).
- Pro Skill ein eigener Ordner mit einer `SKILL.md` darin.
- Zusätzliche Dateien (Skripte, Beispiele) dürfen im selben Ordner liegen.

## Inhalt von SKILL.md

Kopiere dieses Gerüst (das `---`-Frontmatter ist Pflicht):

```markdown
---
name: skill-name
description: Was der Skill tut UND wann er genutzt werden soll. Nenne konkrete Auslöser/Trigger, damit Claude erkennt, wann er greift.
---

# Skill-Name

## Zweck

Kurze Beschreibung, was dieser Skill leistet.

## Vorgehen

1. Schritt eins
2. Schritt zwei
3. Schritt drei

## Beispiele

- Beispielhafte Anwendung
```

## Hinweise

- Die `description` ist entscheidend: Daran erkennt Claude, ob der Skill zur Aufgabe passt.
  Beschreibe **was** der Skill tut und **wann** er ausgelöst werden soll.
- Halte die `SKILL.md` fokussiert; lagere lange Referenzen in Begleitdateien aus.
