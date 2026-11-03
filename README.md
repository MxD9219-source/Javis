# J.A.R.V.I.S. – Free Edition

Eine statische, iPhone-freundliche PWA ohne API-Schlüssel und ohne kostenpflichtige Dienste.

## Funktionen
- Futuristisches Dashboard und animierter Reaktorkern
- Live-Wetter über Open-Meteo (kostenlos für nichtkommerzielle Nutzung; bitte Nutzungsbedingungen beachten)
- Wetter am eigenen Standort nach Freigabe
- System-Sprachausgabe, sofern iOS/Safari verfügbar
- Browser-Sprachaufnahme, sofern der Browser sie unterstützt
- Websuche durch Öffnen einer Suchseite
- ChatGPT wird separat geöffnet; diese Website enthält keinen ChatGPT-API-Zugang
- Offline-Grundgerüst durch Service Worker

## Kostenlos veröffentlichen
GitHub Pages bietet Hosting für öffentliche Repositories im GitHub-Free-Tarif:
1. Erstelle auf GitHub ein öffentliches Repository, z. B. `jarvis-free`.
2. Lade alle Dateien dieses Ordners in das Repository hoch (im Stammverzeichnis).
3. Öffne Settings → Pages.
4. Wähle „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, dann Save.
5. Nach der Veröffentlichung öffne die angezeigte HTTPS-Adresse in Safari.

Hinweis: Ein öffentliches GitHub-Repository bedeutet, dass der Quellcode öffentlich einsehbar ist. Keine privaten Daten oder Passwörter hochladen.

## Auf dem iPhone installieren
1. Veröffentliche die Website zuerst über HTTPS.
2. Öffne die Adresse in Safari.
3. Teilen → Zum Home-Bildschirm.
4. „Als Web-App öffnen“ aktivieren (falls angezeigt) → Hinzufügen.

## Siri
Erstelle in der iPhone-App „Kurzbefehle“ einen Kurzbefehl:
1. Aktion „URL öffnen“ hinzufügen.
2. Die veröffentlichte Jarvis-Adresse eintragen.
3. Kurzbefehl „Jarvis starten“ nennen.
4. Siri: „Hey Siri, Jarvis starten“.

## Grenzen der kostenlosen Version
- Keine integrierte kostenlose ChatGPT-API. Der ChatGPT-Button öffnet ChatGPT separat.
- Keine dauerhafte Mikrofonüberwachung / kein frei definierbares „Hey Jarvis“.
- Keine automatische Hintergrund-Newsüberwachung.
- Web-Push erfordert zusätzlich einen Push-Server. Diese statische Version sendet keine Push-Nachrichten.
- iOS-Browser können Spracherkennung unterschiedlich unterstützen; Diktat über die iPhone-Tastatur ist ein Fallback.
