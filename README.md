# 5-thieves

Ein 30-Tage-Training nach John Izzos *The Five Thieves of Happiness*.
Morgens die Absicht, abends der Rückblick — und nach 30 Tagen eine Auswertung,
welcher Dieb dich tatsächlich bestohlen hat.

A 30-day training based on John Izzo's *The Five Thieves of Happiness*.
Set the intention in the morning, review in the evening, and after 30 days see
which thief actually stole from you.

Läuft unter / Live at: **<https://happy.reb00t.io>**

## Die fünf Diebe / The five thieves

| DE | EN |
|---|---|
| **K**ontrolle | Control |
| **E**itelkeit | Conceit |
| **B**egehren | Coveting |
| **A**nhäufung | Consumption |
| **B**equemlichkeit | Comfort |

Die deutsche Merkhilfe ist **KEBAB**. Im Englischen fangen alle fünf mit C an,
darum gibt es dort keine.

## Was es bewusst nicht tut / Deliberate non-features

- keine Streaks, keine Punkte, keine Belohnungen — eine gamifizierte Version
  dieser Übung wäre Begehren und Anhäufung im Kostüm
- kein Konto, kein Server, kein Tracking; alles liegt im `localStorage`
- keine Push-Notifications; zwei wiederkehrende Erinnerungen in der
  Erinnerungen- oder Kalender-App mit Link auf die Seite erledigen das besser
- „Tag 12 von 30" zählt eingetragene Tage, nicht Kalendertage. 30 Tage dürfen
  45 dauern.

## Laufen lassen / Running it

Es ist eine einzelne HTML-Datei ohne Build-Schritt.

```
python3 -m http.server 8000
# http://localhost:8000
```

## Deployment

GitHub Pages: Settings → Pages → Branch `main`, Ordner `/ (root)`.

Für den Home-Bildschirm auf iOS: Seite in Safari öffnen → Teilen →
„Zum Home-Bildschirm". Dafür werden `icon-192.png` und `icon-512.png`
im Wurzelverzeichnis gebraucht.

## Struktur

```
index.html      alles: Markup, Styles, Logik, beide Sprachen
manifest.json   PWA-Manifest
```

## Lizenz

Apache-2.0. Die Idee der fünf Diebe stammt von John Izzo; dieses Repo enthält
keinen Text aus dem Buch.
