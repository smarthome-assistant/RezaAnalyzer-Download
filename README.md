# RezaAnalyzer — Download

Auswertung für **Smart Home und Bastler**: ein Windows-Programm, das Verläufe aus Home Assistant, ESPHome, Tasmota,
Arduino und Messgeräten einliest, übersichtlich zeigt und in wenigen Klicks auswertet. Was kostet mein Strom? Wann
läuft die Heizung? Ist es im Keller zu feucht? Wie oft ist der Sensor ausgefallen?

Kein Server, kein Konto, kein Internet: Dateien rein, anschauen, Ergebnis als Bild, Tabelle oder Bericht.

Dieses Repo enthält nur die freigegebenen Programmpakete, keinen Quellcode.

## Herunterladen

Unter **[Releases](../../releases)** die neueste Version wählen und `RezaAnalyzer-<Version>.zip` laden.
Entpacken und `RezaAnalyzer.exe` starten. Es gibt keine Installation und braucht keine Administratorrechte.
Die Kurzanleitung liegt im Paket.

**Voraussetzungen:** Windows 10 oder 11 (64 Bit). Läuft auch auf älteren Rechnern mit alten Grafiktreibern, notfalls
mit reiner Software-Darstellung.

## Lizenz und Testschlüssel

Das Programm braucht einen Lizenzschlüssel. Er wird offline geprüft und gilt nur auf einem Rechner.

**7-Tage-Testschlüssel anfragen:** Programm starten, im Fenster „Lizenz“ die **Rechner-ID** kopieren und per E-Mail an
**markus.reza.tain@reza-tain-smart-solutions.de** schicken. Der Schlüssel kommt per Antwort-Mail und wird im
selben Fenster eingetragen.

Nutzungsbedingungen: siehe [LICENSE](LICENSE). Die Lizenzen der mitverwendeten Bibliotheken liegen dem Paket bei
(`Lizenzen.md`).

Die Akustik-Auswertungen sind an Normen angelehnt. Das Programm ist kein geeichtes Messgerät.

## Sicher und privat

- **Keine Netzwerkverbindung, keine Telemetrie:** Die Daten verlassen den Rechner nicht.
- **Rohdaten werden nur gelesen** und nie verändert.
- **Jedes Release wird vor dem Erscheinen geprüft.** In der Release-Notiz stehen das VirusTotal-Ergebnis und die
  SHA-256-Prüfsumme der exe.
- **Für IT-Abteilungen:** Sicherheitsdatenblatt, Prüfbericht und Software-Stückliste gibt es auf Anfrage an
  markus.reza.tain@reza-tain-smart-solutions.de.

### Prüfsumme kontrollieren

In PowerShell im entpackten Ordner:

```
Get-FileHash .\RezaAnalyzer.exe -Algorithm SHA256
```

Der Wert muss mit dem SHA-256 in der Release-Notiz übereinstimmen.
