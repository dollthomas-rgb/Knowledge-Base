---
titel: Claude-Skills-Referenz
erstellt: 2026-06-01
tags: [claude-code, skills, referenz]
---

# Claude-Skills-Referenz

Katalog der **Skills, die Claude in dieser Umgebung bekannt sind** — als Nachschlagewerk.
Stand: 2026-06-01.

Es gibt zwei Arten:

1. **Slash-Command-Skills** – über `/<name>` oder durch passende Aufgaben ausgelöst. Vom
   Claude-Code-Produkt bereitgestellt (nicht als Datei im Repo).
2. **System-/Datei-Skills** – liegen unter `/mnt/skills/public/`, greifen automatisch bei
   bestimmten Dateitypen/Aufgaben.

> Eigene Skills legst du unter `.claude/skills/<name>/SKILL.md` ab — siehe [[Skill-Vorlage]].

---

## 1. Slash-Command-Skills

| Skill | Zweck / Auslöser |
| --- | --- |
| `session-start-hook` | Startup-Hooks für Claude Code on the web erstellen — z. B. damit Tests/Linter in Web-Sessions laufen. |
| `deep-research` | Tiefenrecherche: viele Web-Suchen, Quellen prüfen, Behauptungen verifizieren, zitierten Bericht erstellen. |
| `update-config` | Claude-Code-Harness über `settings.json` konfigurieren: Hooks, Berechtigungen, Umgebungsvariablen. |
| `keybindings-help` | Tastenkürzel anpassen / `~/.claude/keybindings.json` bearbeiten (Rebinds, Chords). |
| `verify` | Prüfen, ob eine Code-Änderung wirklich funktioniert, indem die App ausgeführt und das Verhalten beobachtet wird. |
| `code-review` | Aktuellen Diff auf Korrektheits-Bugs und Aufräum-Verbesserungen prüfen (`--comment`/`--fix` möglich). |
| `simplify` | Geänderten Code auf Wiederverwendung, Vereinfachung, Effizienz prüfen und Fixes anwenden (nur Qualität, keine Bug-Suche). |
| `fewer-permission-prompts` | Transkripte scannen und eine Allowlist in `.claude/settings.json` ergänzen, um Berechtigungs-Nachfragen zu reduzieren. |
| `loop` | Einen Prompt oder Slash-Command in festem Intervall wiederholt ausführen (z. B. Status pollen). |
| `claude-api` | Claude-API-/Anthropic-SDK-Apps bauen, debuggen, optimieren; inkl. Prompt-Caching und Modell-Migrationen. |
| `run` | Die App des Projekts starten und bedienen, um eine Änderung real laufen zu sehen. |
| `init` | Neue `CLAUDE.md` mit Codebase-Dokumentation initialisieren. |
| `review` | Einen Pull Request reviewen. |
| `security-review` | Sicherheits-Review der ausstehenden Änderungen auf dem aktuellen Branch. |

---

## 2. System-/Datei-Skills (`/mnt/skills/public/`)

| Skill | Zweck / Auslöser |
| --- | --- |
| `docx` | Word-Dokumente (`.docx`) erstellen, lesen, bearbeiten, umbauen (Inhaltsverzeichnis, Tabellen, Tracked Changes …). |
| `pdf` | Alles mit PDF-Dateien: erstellen, lesen, mergen/splitten, Formulare ausfüllen, OCR, Wasserzeichen, Ver-/Entschlüsseln. |
| `pdf-reading` | PDF-Inhalte lesen/extrahieren, wenn der Inhalt nicht im Kontext ist (Text, Bilder, Tabellen, Formularfelder). |
| `pptx` | PowerPoint-Präsentationen (`.pptx`) erstellen, lesen, bearbeiten, kombinieren, mit Notizen/Layouts arbeiten. |
| `xlsx` | Tabellen (`.xlsx`, `.xlsm`, `.csv`, `.tsv`) öffnen, lesen, bearbeiten, erstellen, bereinigen, formatieren, Diagramme. |
| `frontend-design` | Hochwertige Frontend-Oberflächen erstellen (Websites, Landingpages, Dashboards, React-Komponenten, Poster). |
| `file-reading` | Router: sagt, welches Werkzeug für welchen hochgeladenen Dateityp genutzt werden soll. |
| `product-self-knowledge` | Verlässliche Fakten zu Anthropics Produkten (Claude Code, Claude API, Claude.ai) nachschlagen. |

---

## Hinweise

- Die **Beschreibung** eines Skills entscheidet, wann Claude ihn nutzt. Bei eigenen Skills
  daher klar **was** und **wann** beschreiben.
- Diese Liste ist eine Momentaufnahme der Umgebung vom Erstellungsdatum; verfügbare Skills
  können je nach Session und Plugins variieren.

Verlinkt von [[Startseite]] · siehe auch [[Claude-Code]].
