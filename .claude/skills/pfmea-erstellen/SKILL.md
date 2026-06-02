---
name: pfmea-erstellen
description: Hilft, eine Prozess-FMEA (PFMEA) strukturiert aufzubauen — von Prozess-Flussdiagramm über Struktur- und Funktionsanalyse bis zu Fehlerketten (Fehlerfolge/-art/-ursache) nach 6M. Auslösen, wenn der Nutzer eine PFMEA neu erstellen, Prozessschritte analysieren, Fehlerursachen nach Mensch/Maschine/Material/Methode/Mitwelt/Messmittel sammeln oder eine PFMEA-Tabelle befüllen möchte. Für DFMEA das Design-Pendant sinngemäß anwenden; für Bewertung den Skill ap-bewertung nutzen.
---

# PFMEA erstellen

Begleitet den Aufbau einer [Prozess-FMEA](../../../Wissen/FMEA-Engineering/PFMEA.md) nach
den [AIAG-VDA-7-Schritten](../../../Wissen/FMEA-Engineering/AIAG-VDA-7-Schritte.md).

## Vorgehen

1. **Umfang & Flussdiagramm:** Prozessschritte (Arbeitsgänge) auflisten und in der
   Reihenfolge des Process Flow erfassen.
2. **Strukturanalyse:** je Prozessschritt die **6M**-Einflüsse als untergeordnete Elemente
   (Mensch, Maschine, Material, Methode, Mitwelt, Messmittel).
3. **Funktionsanalyse:** je Schritt die Prozessfunktion **und** das zu erzeugende
   Produktmerkmal (messbar) benennen.
4. **Fehleranalyse – Fehlerkette je Schritt:**
   - **Fehlerfolge (FE):** Auswirkung beim nächsten Schritt / im Werk / beim Kunden → S
   - **Fehlerart (FM):** Merkmalsabweichung (Maß, Position, fehlendes Teil, Verunreinigung)
   - **Fehlerursache (FC):** nach 6M (z. B. Werkzeugverschleiß, falsche Einstellung)
5. **Maßnahmen zuordnen:** Vermeidung (Poka Yoke, Prozessfähigkeit) → O; Entdeckung
   (Inline-/Endprüfung, SPC) → D.
6. **Bewerten:** mit Skill `ap-bewertung` (S/O/D → AP).
7. **Übergabe:** AP-Hoch/Mittel-Maßnahmen in **Control Plan** und Arbeits-/Prüfanweisungen.

## Vorlage Tabellenkopf (zur Übernahme in FMEA-Software/Excel)

| Prozessschritt | Funktion/Merkmal | FE (Folge) | S | FM (Art) | FC (Ursache, 6M) | Vermeidung | O | Entdeckung | D | AP | Maßnahme | Verantw. | Termin |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|

## Referenzwissen

- `Wissen/FMEA-Engineering/PFMEA.md`, `.../DFMEA.md`, `.../Risikobewertung-S-O-D-AP.md`
- Firmenspezifika: `Wissen/Schaeffler/Schaeffler-FMEA-Praxis.md`
