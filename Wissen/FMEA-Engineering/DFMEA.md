---
titel: DFMEA – Design-FMEA
erstellt: 2026-06-01
tags: [fmea, dfmea, design, konstruktion]
---

# DFMEA – Design-/Konstruktions-FMEA

Die **DFMEA** analysiert potenzielle Fehler, die ihre Ursache im **Produktdesign** haben.
Ziel ist ein Design, das seine Funktionen unter allen vorgesehenen Bedingungen zuverlässig
und robust erfüllt.

## Betrachtungsgegenstand

- **Produkt, Baugruppe, Bauteil** und deren **Merkmale** (Geometrie, Werkstoff, Toleranzen).
- Fehlerursachen liegen in **Konstruktionsentscheidungen** (Auslegung, Werkstoffwahl,
  Toleranzen, Schnittstellen), **nicht** in der Fertigung (das ist [[PFMEA]]).

## Fehlerkette in der DFMEA

- **Fehlerfolge (FE):** Auswirkung auf Funktion, Folgesystem, Endkunden, Gesetz/Norm → **S**
- **Fehlerart (FM):** z. B. Bruch, Verformung, Verschleiß, Funktionsverlust, Leckage
- **Fehlerursache (FC):** z. B. zu gering dimensioniert, falscher Werkstoff, Toleranzkette

## P-Diagramm (Parameter-Diagramm)

Werkzeug zur robusten Funktionsanalyse. Es ordnet einer Funktion zu:

- **Eingangsgrößen** (Inputs / Signale)
- **Steuerbare Faktoren** (Control Factors – Design-Parameter)
- **Störgrößen** (Noise Factors): Streuung, Umwelt, Alterung, Wechselwirkung, Nutzung
- **Soll-Ausgang** (Ideal Response) und **Fehlfunktionen** (Error States)

→ Hilft, **Störgrößen** und daraus resultierende Fehlerarten systematisch zu finden.

## Vermeidung & Entdeckung in der DFMEA

- **Vermeidung (→ O):** Auslegungsregeln, Berechnung/Simulation (FEM), bewährte Konzepte,
  Sicherheitsfaktoren, Design Guidelines.
- **Entdeckung (→ D):** Design-Verifikation, **DVP&R** (Design Verification Plan & Report),
  Tests, Prüfstände, Berechnungen, Design-Reviews.

## Typischer Ablauf (nach [[AIAG-VDA-7-Schritte]])

1. Umfang & Team (5T), Boundary-/Blockdiagramm
2. Strukturbaum des Produkts
3. Funktionen/Anforderungen + P-Diagramm
4. Fehlerketten (FE/FM/FC)
5. Bewertung [[Risikobewertung-S-O-D-AP|S/O/D → AP]]
6. Maßnahmen (Designänderung > Vermeidung > Entdeckung), Neubewertung
7. Dokumentation, Übergabe an [[PFMEA]] & Verifikation

## Schnittstelle zur PFMEA

DFMEA-Ergebnisse liefern **besondere Merkmale** (Special Characteristics) und Eingaben für
die [[PFMEA]]: Was das Design verlangt, muss der Prozess sicher herstellen.

## Ergänzung: FMEA-MSR

Für Fehler, die erst **im Betrieb** auftreten und durch Diagnose/Überwachung abgefangen
werden, ergänzt die [[FMEA-MSR]] die DFMEA (relevant u. a. für Functional Safety / ISO 26262).

## Verwandte Notizen

- [[FMEA-Grundlagen]] · [[AIAG-VDA-7-Schritte]] · [[PFMEA]] · [[FMEA-MSR]] · [[Risikobewertung-S-O-D-AP]]
