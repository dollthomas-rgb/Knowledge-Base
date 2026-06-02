---
titel: PFMEA – Prozess-FMEA
erstellt: 2026-06-01
tags: [fmea, pfmea, prozess, produktion]
---

# PFMEA – Prozess-FMEA

Die **PFMEA** analysiert potenzielle Fehler im **Herstell- und Montageprozess**. Ziel ist
ein Prozess, der die geforderten Produktmerkmale **robust und wiederholbar** erzeugt.

## Betrachtungsgegenstand

- **Prozessschritte / Arbeitsgänge** (z. B. Drehen, Härten, Fügen, Montieren, Prüfen).
- Fehlerursachen liegen in den **Prozesseinflussgrößen**, oft strukturiert über die
  **6M** (Ishikawa):
  **M**ensch, **M**aschine, **M**aterial, **M**ethode, **M**itwelt (Umwelt), **M**essmittel.

## Fehlerkette in der PFMEA

- **Fehlerfolge (FE):** Auswirkung beim nächsten Prozessschritt, im Werk, beim Kunden,
  Endnutzer oder bzgl. Gesetz/Norm → **S**
- **Fehlerart (FM):** Abweichung des Produktmerkmals am Prozessschritt (z. B. Maß außerhalb
  Toleranz, fehlendes Teil, falsche Position, Verunreinigung)
- **Fehlerursache (FC):** Prozessbezogen, meist nach 6M (z. B. falsche Maschineneinstellung,
  Werkzeugverschleiß, vertauschtes Material, fehlende Vorrichtung)

## Vermeidung & Entdeckung in der PFMEA

- **Vermeidung (→ O):** **Poka Yoke** (Fehlervermeidung durch Konstruktion der Vorrichtung),
  Prozessfähigkeit (Cpk), Standardisierung, Schulung, Wartungspläne.
- **Entdeckung (→ D):** Inline-/Endprüfung, Sensorik, SPC, Sichtkontrolle, Funktionsprüfung.
  Automatische Entdeckung vor menschlicher; Vermeidung ist besser als Entdeckung.

## Wichtige Verknüpfungen

- **Eingang:** besondere Merkmale & Anforderungen aus der [[DFMEA]].
- **Ausgang:** **Control Plan / Produktionslenkungsplan** und **Arbeits-/Prüfanweisungen**
  setzen die PFMEA-Maßnahmen in den laufenden Prozess um.
- **Flussdiagramm (Process Flow):** Basis für den Strukturbaum der Prozessschritte.

## Typischer Ablauf (nach [[AIAG-VDA-7-Schritte]])

1. Umfang & Team (5T), Prozess-Flussdiagramm
2. Strukturbaum: Prozess → Prozessschritte → 6M-Einflüsse
3. Funktionen je Schritt (Prozessfunktion + Produktmerkmal)
4. Fehlerketten (FE/FM/FC)
5. Bewertung [[Risikobewertung-S-O-D-AP|S/O/D → AP]]
6. Maßnahmen (Prozessänderung/Poka Yoke > Vermeidung > Entdeckung), Neubewertung
7. Dokumentation, Übergabe in Control Plan

## Verwandte Notizen

- [[FMEA-Grundlagen]] · [[AIAG-VDA-7-Schritte]] · [[DFMEA]] · [[Risikobewertung-S-O-D-AP]] · [[FMEA-Moderation]]
