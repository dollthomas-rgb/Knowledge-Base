---
titel: Risikobewertung – S, O, D und Aufgabenpriorität (AP)
erstellt: 2026-06-01
tags: [fmea, bewertung, rpz, ap, severity, occurrence, detection]
---

# Risikobewertung: S, O, D und Aufgabenpriorität (AP)

In **Schritt 5** der [[AIAG-VDA-7-Schritte]] wird jede Fehlerkette mit drei Kennzahlen von
**1 bis 10** bewertet. Daraus wird die **Aufgabenpriorität (AP)** abgeleitet.

> ⚠️ Die folgenden Stufen sind **allgemein/sinngemäß** beschrieben. Verbindlich sind die
> jeweils gültigen **Bewertungskataloge** (AIAG-VDA-Handbuch bzw. firmenspezifische Tabellen,
> z. B. bei [[Schaeffler-Ueberblick|Schaeffler]]).

## S – Schwere (Severity) der Fehlerfolge

Bewertet die **Auswirkung** der schwersten Fehlerfolge (FE). Bezieht sich auf das **Produkt**.

| Stufe | Bedeutung (sinngemäß) |
| --- | --- |
| 10–9 | Sehr hoch: Sicherheit/Gesetz betroffen (mit/ohne Vorwarnung) |
| 8–7 | Hoch: Funktionsverlust / stark eingeschränkte Funktion |
| 6–4 | Mittel: Funktion eingeschränkt, Komfort-/Bedienminderung |
| 3–2 | Gering: geringe Beeinträchtigung, von Vielen/Wenigen bemerkt |
| 1 | Keine erkennbare Auswirkung |

**S wird nur durch Designänderung gesenkt**, nicht durch Prüfungen.

## O – Auftreten (Occurrence) der Fehlerursache

Bewertet die **Eintrittswahrscheinlichkeit der Ursache** unter Berücksichtigung der
**Vermeidungsmaßnahmen**.

| Stufe | Bedeutung (sinngemäß) |
| --- | --- |
| 10–9 | Sehr hoch: Auftreten quasi unvermeidbar, keine/wirkungslose Vermeidung |
| 8–6 | Hoch: häufig, schwache Vermeidung |
| 5–4 | Mäßig: gelegentlich |
| 3–2 | Gering: selten, bewährte Vermeidung |
| 1 | Auftreten praktisch ausgeschlossen (z. B. Poka Yoke) |

→ **O sinkt durch bessere Vermeidung** (robusteres Design / Prozess).

## D – Entdeckung (Detection)

Bewertet, wie gut die **Entdeckungsmaßnahme** die Ursache oder Fehlerart **vor Auslieferung**
findet. **Achtung: invers** — niedrig = gut entdeckbar.

| Stufe | Bedeutung (sinngemäß) |
| --- | --- |
| 10–9 | Keine/sehr unsichere Entdeckung; Methode wirkt nicht |
| 8–6 | Geringe Entdeckungswahrscheinlichkeit |
| 5–4 | Mäßige Entdeckung |
| 3–2 | Hohe Entdeckung, bewährte/automatisierte Prüfung |
| 1 | Fehler/Ursache wird sicher entdeckt oder kann nicht entstehen |

→ **D sinkt durch wirksamere Entdeckung** (automatisch > manuell).

## RPZ vs. AP – zwei Logiken

### RPZ (Risikoprioritätszahl) – klassisch

$$ RPZ = S \times O \times D $$

- Wertebereich **1–1000**. Höhere Zahl = höheres Risiko.
- **Kritik:** verschiedene S/O/D-Kombinationen ergeben gleiche RPZ; Schwellenwerte sind
  willkürlich; unterschätzt hohe Einzelwerte (z. B. S=10). Wird in der harmonisierten
  Methode **durch AP ersetzt**, in der Praxis teils noch ergänzend genutzt.

### AP (Aufgabenpriorität / Action Priority) – AIAG-VDA

Statt einer Multiplikation eine **logische Tabelle**, die **S, O, D** kombiniert und drei
Prioritäten vergibt:

| AP | Bedeutung |
| --- | --- |
| **Hoch (H)** | Maßnahmen erforderlich oder Begründung dokumentieren, warum keine. |
| **Mittel (M)** | Maßnahmen sollten ergriffen werden; sonst Begründung. |
| **Niedrig (L)** | Maßnahmen können ergriffen werden; keine Pflicht. |

**Logik (vereinfacht):** Hohe **Schwere (S)** dominiert — bei S=9/10 mit relevanten O/D
schnell **AP Hoch**. AP priorisiert nach **Handlungsbedarf**, nicht nach einer Zahl.
Die genaue Zuordnung erfolgt über die **AP-Tabelle** des Handbuchs.

## Vorgehen nach der Bewertung

1. Risiken nach **AP (Hoch → Mittel)** priorisieren.
2. Maßnahmen festlegen (siehe Optimierung in [[AIAG-VDA-7-Schritte]]).
3. **Neubewertung** S/O/D nach Wirksamkeitsnachweis → neues AP.

## Verwandte Notizen

- [[AIAG-VDA-7-Schritte]] · [[DFMEA]] · [[PFMEA]] · [[FMEA-MSR]] · [[FMEA-Glossar]]
