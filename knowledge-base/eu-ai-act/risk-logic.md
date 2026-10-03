# Die Klassen

Für den Einstieg genügt der Aufbau. Die vollständige Einstufungslehre liegt in der [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu).

## Der wichtigste Satz zuerst

**Eingestuft wird ein Einsatzzweck, nicht ein Werkzeug.**

Dasselbe Sprachmodell kann in der Produktsuche folgenlos und in der Bewerbervorauswahl ein Hochrisikosystem sein. Eine Zeile wie „Sprachmodell: minimales Risiko" ist deshalb keine Einstufung — sie ist eine Abkürzung, die in einer Prüfung nicht hält.

Praktische Folge: Ein Werkzeug mit drei Einsatzzwecken braucht drei Einstufungen. Die Versuchung, eine zu machen, ist groß; der Preis fällt später an, weil eine gemeinsame Einstufung sich an der riskantesten Verwendung orientieren muss.

## Die vier Klassen

| Klasse | Bedeutung | Anwendbar |
|---|---|---|
| **Verboten** (Art. 5) | darf nicht betrieben werden | seit 2.2.2025 |
| **Hochrisiko** (Anhang I/III) | voller Pflichtenkatalog | ab 2.12.2027 / 2.8.2028 |
| **Transparenzpflicht** (Art. 50) | Kennzeichnung und Hinweise | seit 2.8.2026 |
| **Minimal** | Inventar, Art. 4, Wiedervorlage | — |

**Es ist keine Stufenleiter.** Art. 50 liegt **neben** den anderen, nicht darunter: Ein Hochrisikosystem mit Chatfunktion hat beides, und ein System mit minimalem Risiko kann eine Transparenzpflicht haben. Das ist der häufigste Denkfehler in diesem Bereich.

## Die Reihenfolge der Prüfung

```
  1 Ist es ein KI-System?           Art. 3 Nr. 1
  2 Greift eine Ausnahme?            Art. 2
  3 Ist es verboten?                 Art. 5    <- Treffer beendet alles
  4 Ist es Hochrisiko?               Anhang I / III
  5 Greift eine Transparenzpflicht?  Art. 50   <- unabhängig von 4
```

Wer bei Schritt 4 anfängt, prüft das Falsche zuerst: Spricht Schritt 3 an, ist der Pflichtenkatalog aus Schritt 4 gegenstandslos, weil das System nicht betrieben werden darf. Ein Verbot lässt sich nicht durch Dokumentation heilen.

## Art. 5: die beiden, die man wirklich prüfen muss

Acht Praktiken sind verboten. Sechs klingen exotisch und sind es in einem gewöhnlichen Unternehmen meist auch. Zwei nicht:

**Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen.** Funktionen, die Gespräche nach Stimmung auswerten — in Analysewerkzeugen für Vertrieb und Personal durchaus verbreitet. Am Arbeitsplatz ist das **verboten**, nicht reguliert.

**Ungezieltes Auslesen von Gesichtsbildern** aus dem Netz oder aus Überwachungsaufnahmen. Werkzeuge zur Personensuche oder Identitätsprüfung.

Beide kommen als Funktion in gekaufter Software vor, ohne dass jemand sie bestellt hat.

## Anhang III: die zwei Bereiche, die normale Unternehmen treffen

| Bereich | Typische Berührung |
|---|---|
| **Beschäftigung** | Bewerberauswahl, Leistungsbewertung, Aufgabenzuweisung, Kündigung |
| **Wesentliche Dienstleistungen** | Kreditwürdigkeit, Versicherungstarifierung |

Die anderen sechs — Biometrie, kritische Infrastruktur, Bildung, Strafverfolgung, Migration, Justiz — treffen vor allem Behörden und bestimmte Branchen.

**Beschäftigung ist der häufigste und unauffälligste Fall**, weil Personalwerkzeuge selten als KI-Projekt beschafft werden.

## Die Ausnahme nach Art. 6 Abs. 3

Ein System in einem Anhang-III-Bereich ist **nicht** hochriskant, wenn es nur eine eng begrenzte Verfahrensaufgabe erfüllt, ein menschliches Ergebnis verbessert, Muster erkennt ohne die Bewertung zu ersetzen, oder vorbereitend tätig ist.

Zwei Dinge, die regelmäßig schiefgehen:

**Sie ist kein Freibrief.** Die Verordnung verlangt eine **dokumentierte Bewertung**. Ein Satz „fällt unter die Ausnahme" ohne Begründung ist kein erfüllter Punkt.

**Die Rückausnahme wird übersehen.** Wird **Profiling** natürlicher Personen vorgenommen, greift die Ausnahme **nicht** — unabhängig von allen vier Tatbeständen. Sie steht nicht in der Aufzählung, sondern danach, und wird deshalb beim Lesen oft übersprungen.

Und die inhaltlich schwierige Stelle: „ohne die menschliche Bewertung zu ersetzen". Wird ein Vorschlag in 98 von 100 Fällen übernommen, ersetzt er sie praktisch — unabhängig davon, was im Prozessdiagramm steht.

## Art. 50: klein, und heute fällig

| Fall | Was zu tun ist |
|---|---|
| Chatbot, Sprachassistent | Hinweis, sichtbar **vor** der ersten Eingabe |
| erzeugte oder bearbeitete Inhalte | maschinenlesbare Kennzeichnung |
| Emotionserkennung, biometrische Kategorisierung | Betroffene informieren |
| Deepfake | offenlegen |

Nachweis je Fall: Bildschirmaufnahme mit **Datum und Produktversion**. Ohne Version belegt sie nur, dass es einmal so aussah.

## Quer dazu: GPAI

Pflichten für Modelle mit allgemeinem Verwendungszweck treffen den **Modellanbieter**, nicht den Betreiber. Wer ein Modell über eine Schnittstelle nutzt, wird davon nicht zum GPAI-Anbieter.

**Für Sie bedeutet das eine andere Frage:** Erfüllt Ihr Anbieter diese Pflichten, und liefert er die Unterlagen, auf die Ihre eigene Dokumentation aufbauen muss? Ein Nein gehört in die Beschaffung.

## Und ohne Klasse: Art. 4

KI-Kompetenz, anwendbar seit 2.2.2025, unabhängig von jeder Klasse. Sie ist keine Formalie: Sie ist die Voraussetzung dafür, dass menschliche Aufsicht überhaupt funktioniert. Wer nicht weiß, wie ein Modell irrt, kann seine Ausgabe nicht beurteilen.

## Weiter

[Der Weg](./compliance-path.md) · [Irrtümer](./common-misconceptions.md) · [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu)
