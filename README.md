# Attention First – Testversion zum Herunterladen

Attention First ist ein Mailclient mit lokalem Agenten: Er ordnet Mails, Chats und Aufgaben nach Dringlichkeit statt
nach Eingang. Alles läuft auf dem eigenen Rechner, auch das Sprachmodell.

Dieses Repository enthält nur die Installer der Testversion, keinen Quelltext.

## Download (Version 0.7.8)

| System | Datei |
|---|---|
| Windows 10/11 (x64) | [Attention-First-Setup-0.7.8.exe](https://github.com/JHX8888/attention-first-download/releases/download/v0.7.8/Attention-First-Setup-0.7.8.exe) |
| macOS (Apple-Chip) | [Attention-First-0.7.8-arm64.dmg](https://github.com/JHX8888/attention-first-download/releases/download/v0.7.8/Attention-First-0.7.8-arm64.dmg) |

Prüfsummen (SHA-256) stehen in `SHA256SUMS.txt` und am Release.

## Hinweise zur Installation

- **Nicht signiert:** Die Installer tragen kein Zertifikat. Windows zeigt beim Start „Der Computer wurde durch Windows
  geschützt“; über „Weitere Informationen“ und „Trotzdem ausführen“ geht es weiter.
- **macOS:** Die App ist nicht von Apple beglaubigt und auf einem Mac noch nicht getestet. Erster Start per Rechtsklick
  und „Öffnen“ oder über Systemeinstellungen › Datenschutz & Sicherheit › „Dennoch öffnen“. Meldet macOS, die App sei
  beschädigt, hilft im Terminal: `xattr -cr "/Applications/Attention First.app"`
- **Erster Start:** Die App lädt einmalig ein Sprachmodell von rund 5 GB. Danach arbeitet sie ohne Verbindung zu
  einem KI-Dienst.
- **Zum Ausprobieren ohne Postfach:** Unter „Konten“ lässt sich ein Konto vom Typ „Demo“ mit erfundenen Nachrichten
  anlegen.

Testversion ohne Gewähr. Rückmeldungen bitte direkt an den Absender des Links.
