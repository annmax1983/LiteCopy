# LiteCopy

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | Deutsch | [日本語](README_ja.md) | [Français](README_fr.md)

Eine schlanke Browser-Erweiterung, die native Textauswahl, Rechtsklick-Menü und Kopier-Tastenkürzel auf jeder Website wiederherstellt.

> Chromium-basiert · Manifest V3 · Minimale Berechtigungen · Kostenlose + Premium-Stufen

---

## Warum LiteCopy?

Schon mal versucht, Text von einer Website zu kopieren, aber konntest ihn nicht auswählen, Rechtsklick war blockiert, oder Strg+C hat nichts gemacht? LiteCopy behebt das alles mit einem Klick.

| Vorteil | Details |
|---------|---------|
| 🔓 **Ein-Klick-Aktivierung** | Native Textauswahl sofort wiederherstellen — kein Seiten-Neuladen nötig |
| 🔒 **Minimale Berechtigungen** | `activeTab` + `scripting` + `storage` — nichts über das Feature hinaus |
| ⚡ **Leichtgewichtig** | Keine Frameworks, keine Laufzeitabhängigkeiten |
| 🌍 **6 Sprachen** | Englisch, Chinesisch, Spanisch, Deutsch, Japanisch, Französisch |
| 🚫 **Kein Tracking** | Keine Analytik, keine Telemetrie. Kostenlose Stufe sendet null Daten; Premium-Aktivierung verifiziert nur eine Geräte-ID + deinen Schlüssel gegen api.annmax1983.com |
| 🎯 **Einfacher Schalter** | Popup öffnen und Ein/Aus drücken — klarer Zustandsindikator |

---

## Funktionen

### 🆓 Kostenlos (100 Kopien/Tag)

| Funktion | Beschreibung |
|----------|--------------|
| 🔓 **Textauswahl wiederherstellen** | Stellt die Standard-Textauswahl auf Seiten wieder her, die sie deaktivieren |
| 🖱️ **Rechtsklick-Menü wiederherstellen** | Stellt das Browser-Rechtsklick-Menü auf eingeschränkten Seiten wieder her |
| ⌨️ **Tastenkürzel wiederherstellen** | Stellt Strg+C, Strg+V, Strg+A und andere Standard-Tastenkürzel wieder her |
| 🛡️ **Overlay-Interferenz beheben** | Behebt transparente Overlay-Divs, die die Textauswahl stören |
| 🔄 **Ein/Aus umschalten** | Aktivieren/Deaktivieren aus dem Popup, Seite wird bei Deaktivierung neu geladen |
| 💬 **Toast-Benachrichtigung** | Automatisch verschwindende Benachrichtigung zeigt Aktivierungsstatus |
| �📋 **Seiteninfo kopieren** | Popup-Buttons zum Kopieren von Seitentitel, URL oder beidem |

> **Limit der kostenlosen Stufe:** 100 Kopien pro Tag. Aktivierung ist immer kostenlos — jede Kopie, die du auf einer aktivierten Seite machst, zählt zum Tageslimit. Der Zähler setzt um Mitternacht (Ortszeit) zurück. Seiteninfo-Buttons (Titel/URL) sind immer kostenlos und zählen nicht mit.

### ⭐ Premium (Lizenz erforderlich — Unbegrenzt)

| Funktion | Beschreibung |
|----------|--------------|
| ♾️ **Unbegrenzte Kopien** | Kein Tageslimit — so viel kopieren wie gewünscht |
| 📤 **Einstellungen exportieren/importieren** | Einstellungen sichern und wiederherstellen (demnächst) |

> 💡 Einmaliger Kauf oder monatliches Abonnement. [Lizenz erhalten →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Preise

| Plan | Preis | Details |
|------|-------|---------|
| Kostenlos | $0 | 100 Kopien/Tag, alle Kernfunktionen |
| Einzellizenz monatlich | $2.99/Monat | Unbegrenzte Kopien für LiteCopy |
| Einzellizenz lebenslang | $9.99 | Einmalige Zahlung, dauerhafter Zugang |
| Komplettpaket monatlich | $3.99/Monat | Alle VKT-Erweiterungen, unbegrenzt |
| Komplettpaket lebenslang | $19.99 | Alle VKT-Erweiterungen, dauerhaft |

Siehe [VKT Preise](https://www.annmax1983.com/pricing.html) für Details.

---

## Vorschau

<p align="center">
  <img src="icons/icon128.png" alt="LiteCopy Symbol" width="80">
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

**Seiteninfo kopieren:**
- Symbol klicken → Popup öffnet sich
- Buttons verwenden, um Seitentitel, URL oder beides zu kopieren

**Nutzung prüfen:**
- Die Nutzungsleiste oben zeigt deine tägliche Kopienanzahl
- Kostenlose Nutzer: 100 Kopien/Tag, Reset um Mitternacht
- Premium-Nutzer: ⭐ Unbegrenzt

---

## Datenschutz

- ✅ **Keine Analytik** — Kein Tracking, keine Telemetrie
- ✅ **Kostenlose Stufe: null Netzwerk-Anfragen** — Alles passiert lokal; nichts wird gesendet, es sei denn, du aktivierst Premium
- ✅ **Minimale Berechtigungen** — `activeTab` + `scripting` + `storage`, plus der Lizenz-API-Host
- ✅ **Kein Seiten-Speicher** — Keine Blacklist/Whitelist, keine Seitenvorlieben gespeichert
- ✅ **Nur Lizenzverifizierung** — Bei Aktivierung einer Premium-Lizenz wird eine minimale Geräte-ID und dein Lizenzschlüssel zur Verifizierung an `api.annmax1983.com` gesendet. Ohne Lizenzaktivierung werden keine Daten gesendet.

---

## Urheberrechtshinweis

Dieses Tool stellt nur grundlegende browser-interne Textverarbeitungsfunktionen für das persönliche Lernen, die Referenz und das Offline-Lesen wieder her. Alle Text-, Bild- und Inhaltsrechte der Website gehören dem ursprünglichen Autor und Website-Betreiber. Nutzer dürfen dieses Tool nicht für kommerzielle Vervielfältigung, massenhaftes Crawling, Inhaltsweiterverbreitung oder andere urheberrechtsverletzende Handlungen verwenden. Alle rechtlichen Folgen aus missbräuchlicher Nutzung trägt allein der Nutzer.

---

## Quellcode-Hinweis

> ⚠️ **Dieses Repository veröffentlicht keinen Quellcode.** Es enthält nur Nutzerdokumentation, Versionshinweise und Support-Ressourcen. Die Erweiterung wird ausschließlich über den Chrome Web Store vertrieben. Es werden keine Offline-Installationspakete oder Endbenutzer-Quellcodes bereitgestellt.

---

## Lizenz

Copyright © 2026 LiteCopy. Alle Rechte vorbehalten.

---

## ❤️ Support

Wenn dir LiteCopy hilft, unterstütze das Projekt gerne!

**[👉 Hier unterstützen](https://ko-fi.com/annmax?ref=litecopy)**
