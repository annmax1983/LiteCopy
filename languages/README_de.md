# LiteCopy

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | Deutsch | [日本語](README_ja.md) | [Français](README_fr.md)

Eine schlanke Browser-Erweiterung, die native Textauswahl, Rechtsklick-Menü und Kopier-Tastenkürzel auf jeder Website wiederherstellt.

> Chromium-basiert · Manifest V3 · Kostenlos unbegrenzt kopieren · Premium: Website-Regeln geräteübergreifend

---

## Warum LiteCopy?

Schon mal versucht, Text von einer Website zu kopieren, aber konntest ihn nicht auswählen, Rechtsklick war blockiert, oder Strg+C hat nichts gemacht? LiteCopy behebt das alles mit einem Klick.

| Vorteil | Details |
|---------|---------|
| 🔓 **Ein-Klick-Aktivierung** | Native Textauswahl sofort wiederherstellen — kein Seiten-Neuladen nötig |
| ♾️ **Kostenlos & unbegrenzt** | Kopieren, Auswählen und Rechtsklick so oft wie gewünscht — kein Tageslimit, kein Zähler |
| 🔄 **Website-Regeln geräteübergreifend** | Premium synchronisiert die aktivierten Websites über die integrierte Kontosynchronisierung des Browsers (Chrome Sync / Edge Sync) |
| 🔒 **Lokal konzipiert** | Das Entsperren läuft lokal mit `activeTab` + `scripting`; der Website-Zugriff dient nur den Seiten, die du aktivierst |
| ⚡ **Leichtgewichtig** | Keine Frameworks, keine Laufzeitabhängigkeiten |
| 🌍 **6 Sprachen** | Englisch, Chinesisch, Spanisch, Deutsch, Japanisch, Französisch |
| 🚫 **Kein Tracking** | Keine Analytik, keine Telemetrie. Der Entwickler hat keinen Server, der deinen Verlauf oder deine Website-Liste speichert |
| 🎯 **Einfacher Schalter** | Popup öffnen und Ein/Aus drücken — klarer Zustandsindikator |

---

## Funktionen

### 🆓 Kostenlos — unbegrenzt

| Funktion | Beschreibung |
|----------|--------------|
| 🔓 **Textauswahl wiederherstellen** | Stellt die Standard-Textauswahl auf Seiten wieder her, die sie deaktivieren |
| 🖱️ **Rechtsklick-Menü wiederherstellen** | Stellt das Browser-Rechtsklick-Menü auf eingeschränkten Seiten wieder her |
| ⌨️ **Tastenkürzel wiederherstellen** | Stellt Strg+C, Strg+V, Strg+A und andere Standard-Tastenkürzel wieder her |
| 🛡️ **Overlay-Interferenz beheben** | Behebt transparente Overlay-Divs, die die Textauswahl stören |
| 🔄 **Ein/Aus umschalten** | Aktivieren/Deaktivieren aus dem Popup, Seite wird bei Deaktivierung neu geladen |
| 🧠 **Gemerkte Seiten** | Aktivierte Seiten werden lokal gemerkt und beim nächsten Besuch automatisch aktiviert |
| 💬 **Toast-Benachrichtigung** | Automatisch verschwindende Benachrichtigung zeigt Aktivierungsstatus |
| 📋 **Seiteninfo kopieren** | Popup-Buttons zum Kopieren von Seitentitel, URL oder beidem |

> Alle Funktionen oben sind kostenlos und unbegrenzt — kein Tageskontingent, kein Reset.

### ⭐ Premium — Website-Regeln geräteübergreifend

| Funktion | Beschreibung |
|----------|--------------|
| 🔄 **Website-Regeln geräteübergreifend** | Aktiviere eine Website einmal, und die Regel folgt deinem Browserkonto — auf anderen angemeldeten Geräten wird sie automatisch aktiviert |
| 🔐 **Synchronisierung über das Browserkonto** | Die Liste speichert dein Browser in `chrome.storage.sync`. Kein LiteCopy-Konto, keine Kopie auf einem Entwickler-Server, kein Zugriff für den Entwickler |
| 💻 **Zugriff pro Gerät** | Website-Berechtigungen des Browsers lassen sich nicht synchronisieren. Klicke auf einem neuen Gerät bei der synchronisierten Website einmal auf Aktivieren, um den Zugriff zu erteilen — die Regel ist bereits gespeichert |
| 🧭 **Manuelle Synchronisierung** | Mit **Jetzt synchronisieren** in den Einstellungen holst du die aktuelle Liste jederzeit aus deinem Browserkonto |

> 💡 Einmaliger Kauf oder monatliches Abonnement. [Lizenz erhalten →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Vorschau

<p align="center">
  <img src="../assets/favicon.png" alt="LiteCopy Symbol" width="80">
</p>

---

## Unterstützte Browser

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Vollständig unterstützt |
| Microsoft Edge | ✅ Vollständig unterstützt |
| Andere Chromium-basierte Browser | ✅ Sollte funktionieren |

---

## Installation

1. Öffne die Erweiterungsseite deines Browsers:
   - **Chrome**: `chrome://extensions/`
   - **Edge**: `edge://extensions/`
2. Aktiviere den **Entwicklermodus** (Schalter oben rechts)
3. Klicke auf **Entpackte Erweiterung laden** und wähle den Ordner `lite-copy`
4. Das LiteCopy-Symbol erscheint in deiner Toolbar

---

## Verwendung

1. Besuche eine beliebige Website, die Kopieren oder Textauswahl blockiert
2. Klicke auf das **LiteCopy**-Symbol in deiner Toolbar — das Popup öffnet sich
3. Klicke auf **Aktivieren** — Textauswahl wird sofort wiederhergestellt
4. Zum Deaktivieren: Popup erneut öffnen und **Deaktivieren** klicken (die Seite wird neu geladen, um das ursprüngliche Verhalten wiederherzustellen)

> **Hinweis:** Einige browser-seitig eingeschränkte Seiten (`chrome://`, der Chrome Web Store usw.) können nicht verändert werden. Das Popup zeigt einen Fehler an.

**Website-Regeln und Synchronisierung (Premium):**
- Aktiviere eine Website auf einem Gerät — die Regel wird dem synchronisierten Speicher deines Browserkontos hinzugefügt
- Auf einem anderen Gerät mit demselben Browserkonto erscheint die Website als gespeicherte Regel; klicke einmal auf **Aktivieren**, um die Website-Berechtigung dieses Geräts zu erteilen
- Öffne die **Einstellungen**, um die Anzahl synchronisierter Websites zu sehen, und nutze **Jetzt synchronisieren** für eine sofortige Aktualisierung

**Seiteninfo kopieren:**
- Symbol klicken → Popup öffnet sich
- Buttons verwenden, um Seitentitel, URL oder beides zu kopieren

---

## Datenschutz

- ✅ **Keine Analytik** — Kein Tracking, keine Telemetrie
- ✅ **Kostenlose Funktionen: null Netzwerk-Anfragen** — Alles passiert lokal; nichts wird gesendet, es sei denn, du aktivierst Premium
- ✅ **Gezielte Berechtigungen** — `activeTab` + `scripting` + `storage` führen das Entsperren aus, dazu Website-Zugriff, der ausschließlich dem Einfügen auf aktivierten Seiten dient, und der Lizenz-API-Host
- ✅ **Website-Liste standardmäßig lokal** — Wird LiteCopy auf einer Seite aktiviert, wird die Domain in `chrome.storage.local` gemerkt. Die Liste wird nie an den Entwickler gesendet
- ✅ **Premium-Sync nutzt dein Browserkonto** — Mit aktiver Lizenz wird die Liste zusätzlich in `chrome.storage.sync` gespiegelt, der Kontosynchronisierung deines Browser-Anbieters. Der Entwickler hat keinen Zugriff und erhält keine Kopie. Wird die Lizenz entfernt, stoppt die Synchronisierung; lokale Regeln funktionieren weiter
- ✅ **Nur Lizenzverifizierung** — Bei Aktivierung einer Premium-Lizenz wird eine minimale Installations-ID und dein Lizenzschlüssel zur Verifizierung an `api.annmax1983.com` gesendet. Ohne Lizenzaktivierung werden keine Daten gesendet

---

## Urheberrechtshinweis

Dieses Tool stellt nur grundlegende browser-interne Textverarbeitungsfunktionen für das persönliche Lernen, die Referenz und das Offline-Lesen wieder her. Alle Text-, Bild- und Inhaltsrechte der Website gehören dem ursprünglichen Autor und Website-Betreiber. Nutzer dürfen dieses Tool nicht für kommerzielle Vervielfältigung, massenhaftes Crawling, Inhaltsweiterverbreitung oder andere urheberrechtsverletzende Handlungen verwenden. Alle rechtlichen Folgen aus missbräuchlicher Nutzung trägt allein der Nutzer.

---

## Quellcode-Hinweis

> ⚠️ **Dieses Repository veröffentlicht keinen Quellcode.** Es enthält nur Nutzerdokumentation und Support-Ressourcen. Die Erweiterung wird ausschließlich über den Chrome Web Store vertrieben. Es werden keine Offline-Installationspakete oder Endbenutzer-Quellcodes bereitgestellt.

---

## Datenschutzrichtlinie

Vollständige Details in der [Datenschutzrichtlinie](../privacy-policy.html) — kostenlose Funktionen arbeiten vollständig offline ohne Netzwerkanfragen.

---

## Lizenz

Copyright © 2026 LiteCopy. Alle Rechte vorbehalten.

---

## ❤️ Support

Wenn dir LiteCopy hilft, unterstütze das Projekt gerne!

**[👉 Hier unterstützen](https://ko-fi.com/annmax?ref=litecopy)**
