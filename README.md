# LOOP CRUSH — iPhone Web-App

Diese Dateien sind die installierbare PWA-Version von LOOP CRUSH.

## Veröffentlichung
Die App muss über HTTPS ausgeliefert werden, damit Safari den Service Worker und die Installation unterstützt.
Ein einfacher Weg ist GitHub Pages:

1. Ein GitHub-Repository für LOOP CRUSH anlegen.
2. Alle Dateien aus diesem Ordner in das Repository hochladen (index.html muss im Hauptverzeichnis liegen).
3. In den Repository-Einstellungen unter Pages die Veröffentlichung aus dem Branch `main`, Ordner `/ (root)` aktivieren.
4. Die erzeugte HTTPS-Adresse in Safari auf dem iPhone öffnen.
5. Teilen → „Zum Home-Bildschirm“ → „Als Web-App öffnen“ aktivieren, falls angezeigt.

## Audio-Hinweise
Die App verwendet Web Audio im Browser. Auf dem iPhone zuerst in Safari öffnen und einmal auf PLAY tippen, damit iOS den Audio-Kontext freigibt. WAV und MP3 sind die sichersten Importformate; weitere Formate hängen von der iOS-Version und dem Safari-Decoder ab. Lokale Dateien werden nicht hochgeladen.
