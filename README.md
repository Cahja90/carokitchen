# CaroKitchen

Familien-Vorrats-App — PWA und Android. Bald im **Google Play Store**.

## Was das ist

CaroKitchen hilft Haushalten, Vorräte, Einkauf und einfache KI-Unterstützung
unter einem Dach zu halten: Produkte erfassen, Haushalt teilen, per Sprache
bedienen, Listen synchron halten sowie einfach ein Foto des Kassenbons machen
und die KI übernimmt das Ganze als eine Liste.

Aktuell: stabile App-Version in Vorbereitung für den Store-Release.
Quellcode bleibt vor dem Launch privat.

## Status

- [x] Produkt & Kernfunktionen ausgearbeitet  
- [x] Android-Variante (Kotlin / Jetpack Compose)  
- [x] Web/PWA-Variante (React, Cloudflare)  
- [ ] Veröffentlichung im **Google Play Store** (in Arbeit)  

## demo

Der Link gilt 24 Stunden und lässt höchstens 50 Leute rein. Jede Adresse testet einmal. Danach ist der Test zu. Ohne diesen Link bleibt die Demo zu.

[CaroKitchen Demo](https://carokitchen-demo.cahja90.workers.dev/?probe=1794732007923.7cebea56d92191e417a2b5cd6c9987470e79ab7153623545088f16d0d64fe4b7)

So geht ein Tag:

1. Demo öffnen
2. `einen tag testen` wählen
3. Vorrat, Einkauf, Planer und Mehr ansehen
4. nach 24 Stunden ist der Test zu

Die echte App und ihre Haushalte sind eine andere Adresse. Der Produktionscode bleibt privat.

## Stack (Überblick)

| Teil | Technik |
|------|---------|
| Android | Kotlin, Jetpack Compose |
| PWA | React, Vite, Cloudflare Workers / D1 |
| KI | serverseitig (Keys nie im Client) |

## ansicht

![vorrat mit ablauf-warnung und kühlschrank: senf, butterschmalz, kaffeesahne, ketchup](screenshots/vorrat.png)

![einkauf, liste zu kaufen: aufschnitt, brot, klopapier, knödel, küchenrolle, obst, tabak hülsen](screenshots/einkauf.png)

![planer mit kartoffelbrei, spätzle und linsen, markiert was da ist und was fehlt](screenshots/planer.png)

![zutaten aus dem vorrat ankreuzen, knopf gerichte vorschlagen](screenshots/planer-zutaten.png)

![haushalt test mit code und schränke von kühlschrank bis vorratsschrank](screenshots/mehr-haushalt.png)

![schränke mit feld neuer schrank und schalter ki-sprachausgabe](screenshots/mehr-schraenke.png)

## Kontakt / Portfolio

Mehr Projekte: [github.com/Cahja90](https://github.com/Cahja90)

---

*Showcase-Repo — ohne Quellcode bis zum Store-Launch.*
