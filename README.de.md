# CbCR Workbook v3 — 2025 Simulation

[English](README.md) · [Deutsch](README.de.md) · [简体中文](README.zh-CN.md)

[Projektübersicht](https://v6rfy78ggr-rgb.github.io/v6rfy78ggr-rgb/de.html) · [Kurzer Einstieg](TRY_IT.md) · [Versionen](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/releases) · [Excel-Vorlage laden](workbooks/CbCR_Template_v3.xlsx)

Ein chinesisch-englisches Excel-Arbeitspaket zur Aufbereitung von Country-by-Country-Reporting-Daten, Rückfragen und Berichten. Enthalten sind eine leere Vorlage und ein vollständig fiktives Beispiel mit fünf Einheiten. Diese deutsche Anleitung bedeutet keine deutsche Übersetzung der Arbeitsmappe.

## Einstieg

Das Repository über **Code → Download ZIP** herunterladen und entpacken. Für eine neue Übung [`workbooks/CbCR_Template_v3.xlsx`](workbooks/CbCR_Template_v3.xlsx), für das Beispiel [`examples/2025_CbCR_Completed_Example.xlsx`](examples/2025_CbCR_Completed_Example.xlsx) öffnen. Desktop-Microsoft-Excel verwenden. Makros und externe Arbeitsmappenverknüpfungen sind nicht enthalten. Andere Tabellenprogramme wurden nicht als gleichwertig abgenommen.

Der [englische Bedienleitfaden](guides/Project_Operating_and_Review_Guide_EN.pdf) erläutert den Ablauf: Parameter, Einheiten, Originalwährungszahlen, Wechselkurse, Anpassungen, Erläuterungen, Unterlagenanforderungen, Bestätigungen, offene Punkte und Berichte. Gelbe Zellen sind Eingaben. Eine bekannte Null als 0 erfassen; Unbekanntes leer lassen. Die vorbereiteten Zeilen und Spalten bieten Platz für 50 Einheiten.

## Inhalt und Methode

- Formelbasierte Vorlage und ausgefülltes Beispiel für 2025 mit getrennten Quellperioden und Berichtsdatumsangaben.
- Fiktive Abschlüsse und Eingabematrix unter `examples/source-documents/`.
- Sechs direkt aus Excel exportierte chinesische/englische Berichts-PDFs unter `examples/reports/`. Nach Änderungen an der Mappe neu exportieren.
- Wechselkursdaten und Methodenbeschreibung unter `examples/methodology/`. Verwendet wird der Mittelwert der täglichen inversen EZB-Notierungen, nicht der Kehrwert des durchschnittlichen Jahreskurses.

## Stand und Grenzen

Auf Wunsch des Herausgebers enthält diese öffentliche Ausgabe weder `CLIENT_2025_Supplement_EN.pdf` noch den chinesischen PDF-Leitfaden. Der englische Leitfaden beschreibt das ursprüngliche Gesamtpaket; die dort genannte Ergänzungsunterlage ist hier nicht verfügbar. Die ursprünglichen Ordner entsprechen hier `workbooks/`, `examples/`, `examples/source-documents/`, `examples/reports/` und `examples/methodology/`. Die ausgefüllte Arbeitsmappe ist enthalten, ihr Belegpaket jedoch nicht vollständig.

v3 stammt vom **6. November 2026**. Die Veröffentlichungskontrolle am **23. November 2026** ergab in beiden Mappen keine gespeicherten Formelfehler, Makros oder externen Beziehungen. Lokale Verzeichnispfade wurden aus Metadaten entfernt; Arbeitsblatt-XML blieb unverändert. Das ausgeblendete Berechnungsblatt ist beabsichtigt. Das Lesen gespeicherter Werte ist keine neue Excel-Berechnung. Wiederöffnen und bedingte Formatierung sind in der Zielumgebung zu prüfen; der aktuelle Nachweis steht in [VALIDATION.md](VALIDATION.md).

Unternehmen, Kennungen, Antworten und Freigaben sind fiktiv. Das Beispiel stellt keine gesetzlichen CbCR- oder Pillar-Two-Pflichten fest. Pillar-Two-Blätter dienen der Datenvorbereitung, nicht der vollständigen GloBE-/Ergänzungssteuerberechnung oder GIR-Erstellung. PDFs sind keine iXBRL-Einreichungsdateien. Ein geändertes Berichtsjahr darf bestätigte Quellperioden nicht überschreiben.

## Rückmeldungen

Bitte Excel-Version, Betriebssystem, Blatt/Zelle, fiktive Eingaben, erwartetes und tatsächliches Ergebnis sowie den Berechnungsstatus nennen. Besonders hilfreich: fehlende Angaben, Periodenwechsel, zusätzliche Einheiten und Druckbereiche. Die Formeln sind die bearbeitbare Implementierung; plattformspezifische Erzeugungswerkzeuge sind nicht enthalten.

Eigene Vorlagen und Dokumentation stehen unter MIT. Für EZB-Daten gelten die ursprünglichen Bedingungen und Quellenangaben in [NOTICE.md](NOTICE.md).

## Mitwirken

[Fehler melden oder Verbesserung vorschlagen](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/issues/new/choose). Rückmeldungen auf Deutsch, Englisch und Chinesisch sind willkommen. Ausschließlich fiktive Daten verwenden; Issues sind öffentlich. Zum Prüfprozess siehe [CONTRIBUTING.md](CONTRIBUTING.md), zur MIT-Lizenz [LICENSE](LICENSE).
