---
titel: AIAG-VDA 7-Schritte-Methode
erstellt: 2026-06-01
tags: [fmea, aiag-vda, methode, 7-schritte]
---

# AIAG-VDA 7-Schritte-Methode

Mit dem gemeinsamen **AIAG-VDA FMEA-Handbuch** wurden die früheren AIAG- (US) und VDA-
(DE) Ansätze zu einer **harmonisierten 7-Schritte-Methodik** zusammengeführt. Sie gilt
für [[DFMEA]] und [[PFMEA]] (mit Ergänzung [[FMEA-MSR]]).

## Überblick der 7 Schritte

| # | Schritt | Kern |
| --- | --- | --- |
| 1 | **Planung & Vorbereitung** | Umfang abstecken, Team, Termine, Tools (5T) |
| 2 | **Strukturanalyse** | System in Elemente zerlegen (Strukturbaum) |
| 3 | **Funktionsanalyse** | Funktionen & Anforderungen je Element (Funktionsnetz) |
| 4 | **Fehleranalyse** | Fehlerketten: Folge – Art – Ursache |
| 5 | **Risikoanalyse** | Bewertung [[Risikobewertung-S-O-D-AP|S/O/D]], Maßnahmen-Status, **AP** |
| 6 | **Optimierung** | Maßnahmen festlegen, umsetzen, neu bewerten |
| 7 | **Ergebnisdokumentation** | Ergebnisse kommunizieren & festhalten |

## Schritt 1 – Planung & Vorbereitung

Definiert den Rahmen über die **5T**:

- **InTent** – Zweck/Ziel der FMEA
- **Timing** – Termine, Meilensteine (FMEA früh, parallel zur Entwicklung)
- **Team** – interdisziplinär (Entwicklung, Produktion, Qualität, ggf. Lieferant/Kunde)
- **Tasks** – die 7 Schritte als Aufgabenplan
- **Tools** – Methode, Software, Bewertungskataloge

Weitere Werkzeuge: **Boundary-/Blockdiagramm** (Systemgrenze, Schnittstellen),
Lastenheft/Anforderungen, Lessons Learned aus Vorgänger-FMEAs.

## Schritt 2 – Strukturanalyse

Zerlegung des Betrachtungsumfangs in einen **Strukturbaum** mit i. d. R. drei Ebenen:

- **Systemelement / übergeordnet** (Fokus-Element)
- **Betrachtetes Element**
- **Untergeordnete Elemente / Prozessschritte**

Liefert die Hierarchie, an der Funktionen und Fehler aufgehängt werden.

## Schritt 3 – Funktionsanalyse

Jedem Strukturelement werden **Funktionen und Anforderungen** zugeordnet (positiv,
messbar formuliert). Verknüpfung zu einem **Funktionsnetz** (übergeordnete Funktion ←
Funktion ← Teilfunktion). In der DFMEA unterstützt das **[[DFMEA|P-Diagramm]]**.

## Schritt 4 – Fehleranalyse

Aus jeder Funktion wird der zugehörige **Fehler** abgeleitet. Die **Fehlerkette** verbindet
drei Ebenen:

- **Fehlerfolge (FE, Failure Effect)** – Auswirkung auf höherer Ebene / beim Kunden → **S**
- **Fehlerart (FM, Failure Mode)** – wie sich der Fehler am betrachteten Element zeigt
- **Fehlerursache (FC, Failure Cause)** – Auslöser auf unterer Ebene → **O** und **D**

> Faustregel: *Folge* = Sicht des Kunden, *Art* = Sicht des betrachteten Elements,
> *Ursache* = Sicht des untergeordneten Elements/Prozessschritts.

## Schritt 5 – Risikoanalyse

- Zuordnung der aktuellen **Vermeidungsmaßnahmen** (wirken auf die Ursache → **O**) und
  **Entdeckungsmaßnahmen** (entdecken Ursache/Art → **D**).
- Bewertung mit **S** (Schwere), **O** (Auftreten), **D** (Entdeckung), je 1–10.
- Ermittlung der **Aufgabenpriorität AP** (Hoch/Mittel/Niedrig). Details und Logik:
  [[Risikobewertung-S-O-D-AP]].

## Schritt 6 – Optimierung

Für Risiken mit Handlungsbedarf (v. a. **AP = Hoch**, dann Mittel) werden Maßnahmen
definiert — Reihenfolge der Wirksamkeit:

1. **Design-/Prozessänderung**, die die Fehlerursache eliminiert (senkt **S** oder **O**).
2. **Erhöhung der Vermeidung** (senkt **O**).
3. **Verbesserte Entdeckung** (senkt **D**) — schwächste Option, da der Fehler entsteht.

Jede Maßnahme erhält **Verantwortlichen** und **Termin**; nach Umsetzung erfolgt die
**Neubewertung** (S/O/D, AP).

## Schritt 7 – Ergebnisdokumentation

Zusammenfassung und **Kommunikation** der Ergebnisse (intern, an Management, Kunde,
Lieferant): Umfang, identifizierte Hochrisiken, ergriffene Maßnahmen, verbleibendes
Restrisiko. Überführung relevanter Punkte in **Control Plan**, Arbeits- und Prüfanweisungen.

## Verwandte Notizen

- [[FMEA-Grundlagen]] · [[DFMEA]] · [[PFMEA]] · [[Risikobewertung-S-O-D-AP]] · [[FMEA-Moderation]]
