---
titel: Geschäftsmodell & Pricing
erstellt: 2026-06-02
tags: [business, pricing, geschäftsmodell, monetarisierung]
---

# 💶 Geschäftsmodell & Pricing

> **Kernstück des Konzepts.** Hier wird festgelegt, **wie** verpackt, bepreist und
> abgerechnet wird, damit aus der FMEA-App planbar 10.000–20.000 €/Monat werden.
> Siehe Gesamtbild in [[00-SaaS-Konzept-MOC]].

## Leitprinzip: value-based, nicht cost-based

Der Preis orientiert sich am **Nutzen/Risiko**, nicht an Hosting-Kosten:

- Externe FMEA-Moderation kostet schnell **1.000–2.000 €/Tag**.
- Etablierte FMEA-Software (APIS IQ-FMEA, Plato SCIO, Siemens) ist **teuer, schwergewichtig,
  schulungsintensiv** und oft jährlich vier- bis fünfstellig.
- **Positionierung der App:** *schnell, KI-gestützt, AIAG-VDA-konform, bezahlbar* — die
  „leichte" Alternative für Freelancer und KMU, die kein 5-stelliges Tool brauchen.

## Das hybride Modell (3 Erlösquellen)

| Quelle | Was | Marge | Geschwindigkeit | Skaliert? |
| --- | --- | --- | --- | --- |
| **Service** | Done-with-you-FMEA (Festpreis) | hoch | sofort | nein (zeitgebunden) |
| **Abo (SaaS)** | App-Zugang, monatlich/jährlich | hoch | mittel | ja |
| **Add-ons** | Schulung, Vorlagen, Audit-Export | mittel | mittel | teilweise |

> Logik: **Service finanziert den Start**, das **Abo trägt langfristig**. Über die Zeit wird
> Service teurer/selektiver, der wiederkehrende Umsatz übernimmt.

## SaaS-Preisstufen (Startannahme)

| Stufe | Preis/Monat | Für wen | Kernumfang |
| --- | --- | --- | --- |
| **Solo / Freelancer** | **49 €** | Einzel-Freelancer | 1 Nutzer, KI-Assistent, Vorlagen, Export (PDF/Excel) |
| **Team / KMU** ⭐ | **149–199 €** | kleine Teams, KMU | 3–5 Nutzer, gemeinsame FMEA-Projekte, Bewertungskataloge |
| **Business** | **ab 499 €** | Mittelstand | Mehr-Projekt, Rollen/Rechte, Audit-Export, Support-SLA |
| **Done-with-you** | **2.000–5.000 € / Projekt** | alle | Du erstellst/moderierst die FMEA, App als Werkzeug |

- ⭐ **Empfohlener Anker:** Die mittlere Stufe wird visuell als „beliebt" hervorgehoben
  (klassisches 3-Stufen-Pricing lenkt zur Mitte).
- **Jahreszahlung:** ~2 Monate gratis (≈ 17 % Rabatt) → bessere Liquidität, geringere Churn.
- **Founding-Customer-Deal:** Erste 10 Kunden erhalten einen Lifetime-/Dauerrabatt gegen
  Referenz, Testimonial und Feedback. Beschleunigt den Start massiv (siehe
  [[Go-to-Market-90-Tage]]).

## Abrechnung (technisch schlank)

- **Stripe** für Subscriptions & Seats (Standard, schnell integriert, SCA/USt-fähig).
- Zuerst nur das Nötigste: Checkout, monatlich/jährlich, Kündigung im Self-Service.
- Service-Projekte separat per Rechnung (Anzahlung 50 % bei Auftrag).
- **USt beachten:** Bei Überschreiten der Kleinunternehmergrenze ist USt auszuweisen —
  Preise dann **netto** kommunizieren (B2B). Siehe [[Rechtsform-und-Steuern]].

## Wege zu 10–20k€/Monat (drei Mixe)

| Mix | Service | Abo | Summe |
| --- | --- | --- | --- |
| **A – service-lastig (schnell)** | 3× 5.000 € = 15.000 € | 10× 150 € = 1.500 € | **16.500 €** |
| **B – ausgewogen** | 2× 5.000 € = 10.000 € | 30× 150 € = 4.500 € | **14.500 €** |
| **C – SaaS-lastig (skaliert)** | 1× 4.000 € = 4.000 € | 80× 130 € = 10.400 € | **14.400 €** |

> **Realismus:** Bei 10 Std./Woche sind 2–3 Service-Projekte/Monat ambitioniert, aber
> machbar, wenn die App die Erstellung beschleunigt. Mix A/B ist der **schnelle Start**,
> Mix C das **Jahresziel**.

## Unit Economics (grobe Orientierung)

- **Variable Kosten/Abo-Kunde:** v. a. KI-/API-Kosten + Hosting → niedrig (einstellig €/Monat).
  → hohe Bruttomarge (Achtung: KI-Kosten pro FMEA überwachen, ggf. Fair-Use-Limits je Stufe).
- **CAC (Akquisekosten):** anfangs vor allem **Zeit** (Content, Outreach), kaum Werbebudget.
- **Churn senken:** Jahrespläne, echte Workflow-Einbindung (FMEA-Projekte „leben" in der App),
  Export-/Audit-Funktionen als Bindung.

## Offene Entscheidungen (in Pilotphase klären)

- Genaue Preispunkte und Seat-Grenzen je Stufe (mit echten Kunden testen).
- Fair-Use-/Nutzungslimits für KI-Funktionen (Schutz der Marge).
- Trial vs. Freemium vs. „Demo + Founding-Deal" (Empfehlung: kein dauerhaftes Freemium,
  stattdessen 14-Tage-Trial oder geführte Demo).

## Verwandte Notizen

- [[00-SaaS-Konzept-MOC]] · [[Zielgruppen-und-Positionierung]] · [[Go-to-Market-90-Tage]]
- [[Rechtsform-und-Steuern]] · [[App-Status-und-Produktluecken]] · [[Risiken-und-Annahmen]]
