---
name: ap-bewertung
description: Unterstützt bei der FMEA-Risikobewertung mit Schwere (S), Auftreten (O) und Entdeckung (D) sowie der Ableitung von RPZ und Aufgabenpriorität (AP, Hoch/Mittel/Niedrig) nach AIAG-VDA. Auslösen, wenn der Nutzer eine Fehlerkette bewerten, S/O/D einschätzen, RPZ berechnen, AP bestimmen oder Risiken priorisieren möchte. Für Workshop-Moderation siehe fmea-moderation, für den Aufbau einer PFMEA-Struktur siehe pfmea-erstellen.
---

# AP-Bewertung (S / O / D → RPZ & AP)

Hilft, FMEA-Fehlerketten konsistent zu bewerten. Details:
[Risikobewertung](../../../Wissen/FMEA-Engineering/Risikobewertung-S-O-D-AP.md).

> ⚠️ **Wichtig:** Verbindlich sind die jeweils gültigen **Bewertungskataloge** (AIAG-VDA-
> Handbuch bzw. firmenspezifisch). Diese Einschätzungen sind eine **Hilfestellung**, kein
> Ersatz für den freigegebenen Katalog. Firmenspezifika:
> `Wissen/Schaeffler/Schaeffler-FMEA-Praxis.md`.

## Vorgehen

1. **Fehlerkette aufnehmen:** Fehlerfolge (FE), Fehlerart (FM), Fehlerursache (FC).
2. **S (1–10):** Schwere der schwersten Folge. 9–10 = Sicherheit/Gesetz.
   *S sinkt nur durch Designänderung.*
3. **O (1–10):** Auftreten der Ursache unter Berücksichtigung der Vermeidung.
   *O sinkt durch bessere Vermeidung.*
4. **D (1–10, invers):** Entdeckung vor Auslieferung. 1 = sicher entdeckt, 10 = nicht.
   *D sinkt durch wirksamere (möglichst automatische) Entdeckung.*
5. **RPZ:** S × O × D (1–1000) — nur als Zusatzindikator.
6. **AP bestimmen:** über die AIAG-VDA-AP-Logik (S dominiert) → **Hoch / Mittel / Niedrig**.
7. **Priorisieren:** zuerst AP-Hoch, dann -Mittel; Maßnahmen mit Verantwortlichem + Termin.
8. **Neubewertung** nach Wirksamkeitsnachweis.

## Faustregeln zur AP-Logik (vereinfacht)

- **S = 9–10** mit relevantem O **oder** D → tendenziell **AP Hoch**.
- Mittlere S mit hohem O → eher **Mittel/Hoch**.
- Niedrige S **und** niedrige O → eher **Niedrig**.
- Im Zweifel die **offizielle AP-Tabelle** heranziehen, nicht schätzen.

## Ausgabeformat (Vorschlag)

```
FE: …  | S = _
FM: …
FC: …  | O = _ (Vermeidung: …)  | D = _ (Entdeckung: …)
→ RPZ = S×O×D = _   | AP = Hoch/Mittel/Niedrig
Empfohlene Maßnahme: …  (senkt S/O/D?)  | Verantw.: …  | Termin: …
```

## Referenzwissen

- `Wissen/FMEA-Engineering/Risikobewertung-S-O-D-AP.md`
- `Wissen/FMEA-Engineering/FMEA-MSR.md` (dort S/F/M statt S/O/D)
