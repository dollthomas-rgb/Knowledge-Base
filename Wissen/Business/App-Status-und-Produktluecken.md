---
titel: App-Status & Produktlücken
erstellt: 2026-06-02
tags: [business, produkt, app, roadmap, annahmen]
---

# 🧩 App-Status & Produktlücken

> ⚠️ **Annahmen-Notiz.** Das App-Repo `dollthomas-rgb/-fmeageneric` war beim Erstellen dieses
> Konzepts **nicht einsehbar** (nicht im Session-Scope). Die Punkte hier sind **Hypothesen**
> und werden präzisiert, sobald der Code gelesen werden kann.

## So wird das Repo zugänglich gemacht

1. In den **Repository-/Environment-Settings** dieser Session `dollthomas-rgb/-fmeageneric`
   zusätzlich freigeben.
2. Ggf. **neue Session** für dieses Repo starten (der Scope einer laufenden Session ist fix).
3. Danach: Code-Review → diese Notiz mit echtem Stand füllen.

## Checkliste: Ist die App verkaufsbereit? (zu validieren)

| Bereich | Frage | Status |
| --- | --- | --- |
| **Hosting/Live** | Ist die App deployed und öffentlich erreichbar? | ❓ |
| **Auth** | Gibt es Registrierung/Login (Mehrnutzer)? | ❓ |
| **Billing** | Ist Stripe/Abo angebunden (Self-Service-Kauf)? | ❓ |
| **Mehrnutzer/Teams** | Können Teams gemeinsam an einer FMEA arbeiten? | ❓ |
| **FMEA-Kern** | Struktur-/Funktions-/Fehleranalyse, S/O/D, RPZ, AP vorhanden? | ❓ |
| **KI-Funktionen** | Sind die Skills (`ap-bewertung`, `pfmea-erstellen`) integriert? | ❓ |
| **Export** | PDF/Excel-Export AIAG-VDA-konform (Formblatt)? | ❓ |
| **Datenschutz** | DSGVO-konform, EU-Hosting, AVV möglich? | ❓ |
| **Rollen/Rechte** | Für Business-Stufe nötig (Audit, Freigaben)? | ❓ |

## Minimal verkaufsbarer Funktionsumfang (Annahme)

Damit die App **kostenpflichtig** verkauft werden kann, braucht es mindestens:

1. **Login + Bezahlung** (Stripe-Abo, Self-Service).
2. **Eine vollständige FMEA von Anfang bis Export** durchführbar.
3. **Vorzeigbarer, AIAG-VDA-konformer Export** (das ist oft das Kaufargument beim Kunden).
4. **Datenschutz-Basics** (Datenschutzerklärung, AVV, EU-Hosting).

Alles darüber (Teams, Rollen, KI-Komfort) ist **Upsell-/Differenzierungspotenzial** für die
höheren Stufen aus [[Geschaeftsmodell-und-Pricing]].

## Empfohlener Tech-Hebel (falls Ausbau nötig)

- **Supabase** (Auth + Postgres + Storage) und **Vercel** (Hosting) — beides steht in dieser
  Umgebung als Integration bereit und hält den Wartungsaufwand bei 10 Std./Woche klein.
- **Claude-API** als KI-Engine; die vorhandenen [[Skills-Referenz|Skills]]-Logiken als
  Vorlage für die FMEA-Assistenzfunktionen wiederverwenden.

## Verwandte Notizen

- [[00-SaaS-Konzept-MOC]] · [[Roadmap-und-Umsetzung]] · [[Geschaeftsmodell-und-Pricing]] · [[Risiken-und-Annahmen]]
