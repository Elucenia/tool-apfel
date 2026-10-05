<!-- ELUCENIA technical documentation · apfel · de · no clinical/professional/rights approval -->

# Apfel-Score (postoperative Übelkeit und Erbrechen)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/apfel)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Weibliches Geschlecht

`fem`

### Nichtraucher

`naofuma`

### Postoperative Übelkeit und Erbrechen oder Reisekrankheit in der Anamnese

`historia`

### Geplanter postoperativer Opioidgebrauch

`opioide`

## Fassung der Methode

Vereinfachter Apfel 1999: 4 Faktoren, 0–4; nicht das Koivuranta-Modell

## Dokumentierte Formel

1 Punkt je Faktor: weiblich, Nichtraucher, frühere PONV oder Reisekrankheit, postoperative Opioide.

## Grenzen und Population

Der vereinfachte Apfel-Score von 1999 wurde bei Erwachsenen unter Inhalationsanästhesie ohne antiemetische Prophylaxe für Übelkeit oder Erbrechen in den ersten 24 Stunden untersucht. Wahrscheinlichkeiten der Originalkohorte sind nicht automatisch für Kinder, andere Anästhesieverfahren oder Personen mit bereits laufender Prophylaxe neu kalibriert. Die antiemetische Strategie erfordert eine eigene Beurteilung und Leitlinie.

## Referenzen

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
