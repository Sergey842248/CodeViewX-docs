# CodeView X

Ein vielseitiger **Code-Editor** und **Dokumentenbetrachter** für Android und iOS.

## Features

- 📁 **Dateiverwaltung** – Durchsuche, erstelle, bearbeite und lösche Dateien und Ordner
- 💻 **Syntax-Highlighting** – Unterstützt über 40 Programmiersprachen (Python, JS, TS, Java, C/C++, Rust, Go, Swift, Kotlin, PHP, Dart, HTML, CSS, SQL, Markdown u. v. m.)
- 📄 **Dokumentenbetrachter** – PDF, Word (DOCX), Excel (XLSX), PowerPoint (PPTX)
- 🎨 **Anpassbares Theme** – Helles / dunkles Theme, frei wählbare Schriftart und -größe
- ✏️ **Inline-Editor** – Text-, Code- und Log-Dateien direkt bearbeiten
- 🚀 **Schnelle Navigation** – Verzeichnisse durchsuchen und zwischen Dateien wechseln

## Erste Schritte

### Voraussetzungen

- Flutter SDK (>= 3.11.0)
- Dart SDK (>= 3.11.0)

### Installation

```bash
git clone https://github.com/dein-benutzer/CodeView.git
cd CodeView
flutter pub get
flutter run
```

### Build

```bash
flutter build apk        # Android
flutter build ios        # iOS
flutter build macos      # macOS (falls konfiguriert)
```

## Berechtigungen

Die App benötigt folgende Berechtigungen, um auf deine Dateien zuzugreifen:

- **Android**  
  - `READ_EXTERNAL_STORAGE` – Dateien lesen  
  - `WRITE_EXTERNAL_STORAGE` – Dateien speichern und bearbeiten  
  - `MANAGE_EXTERNAL_STORAGE` – Umfassende Dateiverwaltung (Android 11+)

- **iOS**  
  - Zugriff auf die Dokumentenauswahl / iCloud Drive, um Dateien zu öffnen und zu speichern

## Datenschutz

Die vollständige Datenschutzerklärung findest du in [PRIVACY_POLICY.md](PRIVACY_POLICY.md).

## Mitwirken

Pull Requests sind willkommen. Für größere Änderungen bitte zuerst ein Issue öffnen.

## Lizenz

[Füge hier deine Lizenz ein]
