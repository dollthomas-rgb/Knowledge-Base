---
titel: FMEA-MSR – Monitoring & System Response
erstellt: 2026-06-01
tags: [fmea, msr, monitoring, functional-safety]
---

# FMEA-MSR – Monitoring and System Response

Die **FMEA-MSR** ist eine **Ergänzung zur [[DFMEA]]** für Fehler, die erst **im Betrieb
beim Endkunden** auftreten und durch **Diagnose/Überwachung** erkannt und durch eine
**Systemreaktion** in einen sicheren oder geregelten Zustand überführt werden.

Besonders relevant für **mechatronische/elektronische Systeme** und **Funktionale
Sicherheit** (z. B. ISO 26262).

## Grundidee

Betrachtet die Kette **Ursache → Überwachung → Reaktion → Restfolge** während des Betriebs:

- Tritt eine Fehlerursache auf, soll ein **Sensor/Diagnose** sie **erkennen**.
- Das **System reagiert** (z. B. Warnung, Notlauf, Abschaltung).
- Dadurch wird eine schwere Fehlerfolge auf eine **abgemilderte Folge** reduziert.

## Bewertung (statt O/D)

Die MSR nutzt eine angepasste Bewertung:

| Größe | Bedeutung |
| --- | --- |
| **S** | Schwere der (ursprünglichen) Fehlerfolge — wie in der [[Risikobewertung-S-O-D-AP|DFMEA]] |
| **F** (Frequency) | Häufigkeit/Expositionsdauer des Auslösers im Betrieb |
| **M** (Monitoring) | Wirksamkeit von Überwachung **und** Systemreaktion, den Fehler abzufangen |

Daraus wird — analog — eine **Aufgabenpriorität (AP)** abgeleitet.

## Abgrenzung

| | DFMEA | FMEA-MSR |
| --- | --- | --- |
| Entdeckung **wann** | vor Auslieferung (Entwicklung/Test) | **im Betrieb** beim Kunden |
| Kennzahlen | S, O, D | S, F, M |
| Ziel | Fehler vermeiden/entdecken | Fehler **diagnostizieren & sicher reagieren** |

## Verwandte Notizen

- [[DFMEA]] · [[Risikobewertung-S-O-D-AP]] · [[AIAG-VDA-7-Schritte]] · [[FMEA-Glossar]]
