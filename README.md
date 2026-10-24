# AudioBook Studio

**Hörbücher zusammenführen & taggen – verlustfrei, mit Kapiteln, ordentlich sortiert.**

AudioBook Studio ist ein Windows-Programm für alle, die Hörbücher als viele einzelne MP3-Dateien haben und daraus eine saubere Sammlung machen möchten: **eine Datei pro Buch**, mit Titel, Autor, Sprecher, Reihe, Band, Cover, Beschreibung und Kapitelmarken – automatisch in Ordnern nach Autor und Reihe abgelegt.

> Version 1.2.5 · Windows 10 (ab 1809) und Windows 11 · 17 Sprachen

---

## Download & Installation

1. Unter **[Releases](../../releases/latest)** die Datei `AudioBook-Studio-Setup-x.y.z.exe` herunterladen.
2. Setup starten – es fragt, ob für **alle Benutzer** oder **nur für dich** installiert werden soll (ohne Administratorrechte möglich).
3. Falls Windows „Der Computer wurde durch Windows geschützt“ meldet: **Weitere Informationen → Trotzdem ausführen** (das Setup ist nicht digital signiert).
4. Beim ersten Start führt ein **Einrichtungsassistent** durch alle Einstellungen.

Updates installiert das Programm auf Wunsch selbst (Hilfe → Nach Updates suchen).

---

## Funktionen

### Hörbücher erstellen
- **Verlustfrei:** Kapitel-Dateien werden bitgenau zu einer MP3 zusammengefügt – keinerlei Qualitätsverlust, in Sekunden. Optional Umwandlung in M4A/AAC, FLAC, WAV, ALAC oder AIFF.
- **Kapitelmarken** genau an den ursprünglichen Kapiteln (MP3, M4A, FLAC) – Hörbuch-Apps zeigen die Kapitel an.
- **Automatische Buch-Erkennung:** Ordner voller Kapitel werden ein Buch, fertige Einzel-MP3s bleiben eigene Bücher, mehrere Bände in einem Ordner werden getrennt.
- **Online-Suche** nach Titel, Autor, Sprecher, Reihe, Band, Cover, Genre, Jahr und Beschreibung (Audible, iTunes, Google Books, Deutsche Nationalbibliothek, Open Library).
- **Buchprofil prüfen** vor und nach der Verarbeitung – Buch für Buch mit „Weiter“, Änderungen landen direkt in der Datei.
- **Parallele Verarbeitung** mit Live-Fortschritt, Restzeit, Pause und Abbruch.
- **Archive** (ZIP, RAR, 7z) direkt entpacken.
- **Ordnung im Zielordner:** `Autor\Reihe (Band 01 - 06) [Lücke Bd 3, 5]\Reihe - Band 04 - Titel.mp3` – mit automatisch gepflegter Angabe fehlender Bände.
- **Nach Genre sortieren:** z.B. `Genre\Autor\Reihe` – oder eine **eigene Ordnerstruktur** aus Genre, Autor, Reihe, Sprecher, Jahr, Spice-Grad und Altersempfehlung (z.B. `Romantasy\16+\Autorin\Reihe`). Vorhandene Bücher lassen sich per „Zielordner aufräumen“ umsortieren.
- **Spice-Grad (0–5 🌶️) und Altersempfehlung** im Buchprofil – in der Datei gespeichert (zusätzlich als erste Zeile im Kommentar, damit auch Player wie Evermusic sie anzeigen), in der Sammlung filterbar, in der Übersichtstabelle exportierbar.

### Sammlung verwalten
- **Sammlung:** alle Hörbücher durchsuchen, filtern und anhören – mit **gehört**, **Sterne-Bewertung** und **Notizen**.
- **Statistik:** Stunden gesamt, Autoren, Genres, größte Reihen, Neuzugänge.
- **Wunschliste:** fehlende Bände deiner Reihen, mit Titeln aus der Online-Suche – plus **Neuerscheinungs-Alarm**.
- **Übersicht als Tabelle:** Excel, PDF, Word, Markdown oder CSV, Spalten frei wählbar.
- **Mehrere Bücher gleichzeitig bearbeiten**, **Schreibweisen vereinheitlichen**, **fehlende Angaben online auffüllen**.
- **Gleiche Angaben für gleiche Autoren und Reihen** – neue Bücher übernehmen Genre/Sprecher aus der eigenen Sammlung.

### Pflegen & absichern
- **Gesundheitscheck:** findet beschädigte, abgeschnittene oder unvollständige Dateien und trägt fehlende Kapitel nach.
- **Doppelte Hörbücher** finden und entscheiden, was damit passiert.
- **Zielordner aufräumen** mit Vorschau.
- **Rückgängig** für Verschieben, Umbenennen, Papierkorb und geänderte Angaben.
- **Automatische Sicherung** der Bibliothek (z.B. in OneDrive oder pCloud).
- **Gleiche Lautstärke (ReplayGain)** – ohne das Audio zu verändern.
- Vor jedem Löschen wird nachgefragt; Entferntes landet im Papierkorb.

### Unterwegs hören
- **Übertragen** auf **OneDrive / pCloud** (z.B. für **Evermusic** auf iPhone und Android), **USB-Stick, SD-Karte, MP3-Player** oder **Android-Handy per USB** – inkrementell, mit Cover.
- **Eingangsordner:** neue Downloads werden automatisch erkannt und geladen.

### Bedienung
- Modernes Design mit vielen Farbthemen, eigenen Hintergrundbildern und **Hell/Dunkel wie Windows**.
- Für **Windows 11** gemacht: Fenster an den Bildschirmrand andocken (Snap), eigene Fenster für Prüfungen, Benachrichtigungen.
- **Einrichtungsassistent**, eingebautes **Handbuch** (Umschalt+F1) und jede Zusatzfunktion **einzeln ein- und ausschaltbar**.
- **17 Sprachen** samt Handbuch: Deutsch, Englisch, Französisch, Spanisch, Italienisch, Niederländisch, Portugiesisch, Polnisch, Russisch, Ukrainisch, Türkisch, Schwedisch, Chinesisch, Japanisch, Koreanisch, Hindi und Arabisch (von rechts nach links). Weitere oder verbesserte **Sprachpakete** lassen sich in der App herunterladen oder aus einer Datei hinzufügen (die Übersetzungen außer Deutsch und Englisch sind KI-Übersetzungen – Hinweise auf Fehler sind willkommen).

---

## Datenschutz

Alles läuft lokal auf deinem PC. Online gehen nur Suchanfragen (Autor/Titel) an die Metadaten-Dienste, das Laden von Covern und – falls eingeschaltet – die Update-Prüfung bei GitHub. Deine Original-Dateien werden nie verändert.

---

## Lizenz & Drittsoftware

© 2026 Vanessa Hormes. Verwendet u.a. FFmpeg (GPLv3), Qt/PyQt6 (LGPLv3/GPLv3), mutagen (GPL), requests (Apache 2.0), openpyxl (MIT) und Lucide-Symbole (ISC) – Details in der Datei `Lizenzhinweise.txt` im Programmordner.
