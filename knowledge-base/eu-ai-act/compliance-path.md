# Der Weg

Sechs Phasen, in dieser Reihenfolge. Je Phase: was zu tun ist, welcher Aufwand realistisch anfällt, und was am Ende vorliegt.

Die Aufwandsangaben gelten für ein Unternehmen mit etwa 40 Beschäftigten und einer Person, die das nebenbei macht. Sie sind geschätzt, nicht gemessen — aber die Größenordnung ist wichtiger als die Zahl, weil das Missverhältnis zwischen den Phasen der eigentliche Hinweis ist.

---

## Phase 1: Verbotenes ausschließen

**Warum zuerst:** Art. 5 gilt seit **2.2.2025**, und ein Treffer macht alles Weitere gegenstandslos — ein Verbot lässt sich nicht durch Dokumentation heilen. Die Phase ist außerdem kurz.

**Was zu tun ist:** Die acht verbotenen Praktiken einmal durchgehen. Nicht aus dem Gedächtnis, sondern an den eingesetzten Werkzeugen.

Die beiden, die in gekaufter Software vorkommen und deshalb konkret zu prüfen sind:

- **Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen.** Funktionen, die Kundengespräche oder Bewerbungsgespräche nach Stimmung auswerten. In Analysewerkzeugen für Vertrieb und Personal durchaus verbreitet.
- **Ungezieltes Auslesen von Gesichtsbildern** aus dem Netz oder aus Überwachungsaufnahmen. Werkzeuge zur Personensuche oder Identitätsprüfung.

**Aufwand:** ein halber Tag, wenn man weiß, welche Werkzeuge im Haus sind. Sonst gehört diese Phase mit Phase 2 zusammen.

**Ergebnis:** eine Notiz mit acht Zeilen und Datum. Das ist der Nachweis.

## Phase 2: Bestand aufnehmen

**Warum hier:** Ohne Register ist jede weitere Aussage eine Vermutung. Und diese Phase ist die längste — wer sie unterschätzt, plant den Rest falsch.

**Was zu tun ist:** Aus fünf Quellen suchen, nicht fragen:

| Quelle | Findet |
|---|---|
| Beschaffung und Kreditorenliste | eingekaufte Werkzeuge mit Vertrag |
| Auslagenerstattung | Einzelabos, die an der Beschaffung vorbeigehen |
| Anmeldedienst (SSO) | zentral angemeldete Dienste |
| Netzprotokolle, **aggregiert** | Dienste ohne Vertrag und ohne Anmeldung |
| Release-Notes bestehender Software | nachträglich ergänzte KI-Funktionen |

Die letzte Quelle liefert den häufigsten Fall: Ein CRM bekommt eine Zusammenfassungsfunktion, und ab diesem Release verarbeitet ein KI-System Kundendaten, ohne dass ein Projekt dazu existiert.

**Aufwand:** 3 bis 8 Tage, verteilt über mehrere Wochen, weil Antworten auf Anfragen warten müssen.

**Ergebnis:** ein Register mit einem Eintrag **je Einsatzzweck**, und ein Suchprotokoll. Letzteres ist in einer Prüfung wichtiger als die Vollständigkeit selbst: Es belegt, dass gesucht wurde.

Ausführlich: [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory)

## Phase 3: Transparenz umsetzen

**Warum hier:** Art. 50 gilt seit **2.8.2026**, ist technisch klein und wird fast überall übersehen, weil die Aufmerksamkeit bei Hochrisiko liegt.

**Was zu tun ist:** Für jeden Fall aus dem Register prüfen:

| Fall | Pflicht |
|---|---|
| Chatbot, Sprachassistent, direkter Kontakt | Hinweis, dass es KI ist — sichtbar **vor** der ersten Eingabe |
| erzeugte oder bearbeitete Inhalte (Text, Bild, Ton, Video) | maschinenlesbare Kennzeichnung |
| Emotionserkennung, biometrische Kategorisierung | Betroffene informieren |
| Deepfake | offenlegen |

**Aufwand:** ein bis zwei Tage je betroffenes System, meist Entwicklungsarbeit.

**Ergebnis:** Kennzeichnung im laufenden System, und je Fall ein Nachweis mit **Datum und Produktversion**. Ohne Version belegt eine Bildschirmaufnahme nur, dass es einmal so aussah.

## Phase 4: KI-Kompetenz

**Warum hier:** Art. 4 gilt seit **2.2.2025** und braucht keine Risikoklasse. Und sie ist Voraussetzung für Phase 6: Eine menschliche Aufsicht, die nicht versteht, wie ein Modell irrt, ist keine Aufsicht.

**Was zu tun ist:** Festhalten, wer welches System bedient und beaufsichtigt, und diese Leute **systembezogen** schulen. Eine allgemeine KI-Schulung erfüllt den Punkt nicht.

Was eine brauchbare Schulung vermittelt:

- wie dieses Modell typischerweise irrt — mit Beispielen aus dem eigenen Haus
- woran man eine falsche Ausgabe erkennt
- was man damit **tun** darf: übergehen, korrigieren, eskalieren
- was nicht hineingegeben werden darf

**Aufwand:** ein Tag Vorbereitung, zwei Stunden je Gruppe, jährliche Wiederholung.

**Ergebnis:** Teilnahmeliste mit Datum **und Inhalt**. Eine Liste ohne Inhaltsangabe belegt Anwesenheit, nicht Kompetenz.

## Phase 5: Einstufen

**Warum erst jetzt:** Eine Einstufung braucht das Register aus Phase 2. Vorher ist sie eine Schätzung mit Aktenzeichen.

**Was zu tun ist:** Je Einsatzzweck in dieser Reihenfolge prüfen — KI-System, Ausnahme, Art. 5, Anhang I/III, Art. 50. Und die Rollenfrage: Greift Art. 25?

Die Frage, die den unbemerkten Fall findet: **Berührt die Ausgabe Beschäftigung, Bildung, Kreditwürdigkeit, Strafverfolgung, Migration, Justiz, wesentliche Dienstleistungen oder kritische Infrastruktur?**

**Aufwand:** 2 bis 4 Stunden je Einsatzzweck. Bei Treffern in einem dieser Bereiche kommt rechtliche Prüfung hinzu.

**Ergebnis:** je Einsatzzweck eine Klasse mit **Begründung und Annahmen**. Das Annahmenfeld fehlt am häufigsten und ist in einer Prüfung das wertvollste.

Ausführlich: [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu)

## Phase 6: Pflichten je Klasse

**Warum zuletzt:** Weil der größte Teil davon Zeit hat. Anhang III gilt ab **2.12.2027**, Anhang I ab 2.8.2028.

**Was jetzt schon sinnvoll ist, auch ohne Hochrisikosystem:**

- menschliche Aufsicht benennen und **ausübbar** machen
- Protokollierung einrichten, soweit möglich
- einen Weg schaffen, auf dem eine Fehlfunktion gemeldet wird
- Auslöser je System eintragen, die eine Neubewertung erfordern
- einen **Testsatz** gegen den stillen Modellwechsel einrichten

**Was bei Hochrisiko hinzukommt und lange dauert:** Risikomanagementsystem, technische Dokumentation nach Anhang IV, Qualitätsmanagement, Konformitätsbewertung — und das nur in der Anbieterrolle.

**Aufwand:** nicht in Tagen schätzbar. Bei einem Hochrisikosystem in der Anbieterrolle ist das ein Projekt, nicht eine Aufgabe.

Ausführlich: [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist)

---

## Das Missverhältnis, das die Planung bestimmt

| Phase | Aufwand | Fälligkeit |
|---|---|---|
| 1 Verbotenes ausschließen | halber Tag | seit 2.2.2025 |
| 2 Bestand aufnehmen | 3–8 Tage | Voraussetzung |
| 3 Transparenz | 1–2 Tage je System | seit 2.8.2026 |
| 4 KI-Kompetenz | 1 Tag + 2 h je Gruppe | seit 2.2.2025 |
| 5 Einstufen | 2–4 h je Einsatzzweck | Voraussetzung |
| 6 Pflichten | Projekt | größtenteils ab 2.12.2027 |

Die Phasen 1 bis 4 sind zusammen etwa zwei Arbeitswochen und decken alles ab, was **heute** fällig ist. Das ist die praktisch wichtigste Aussage dieses Repositories: Der Teil mit Frist ist überschaubar; der große Teil hat Zeit.

## Was in der Geschäftsführung vorgelegt wird

Nicht die Phasenliste, sondern drei Zahlen:

1. **Wie viele KI-Einsatzzwecke** gibt es (nach Phase 2)?
2. **Wie viele berühren einen Anhang-III-Bereich** — und sind damit rechtlich zu bewerten?
3. **Welche Pflichten sind heute fällig**, und welche davon sind noch offen?

Vorlage: [Fahrplan](../../templates/compliance-roadmap-template.md)

## Weiter

[Irrtümer](./common-misconceptions.md) · [Wer macht das](./inventory-and-governance.md) · [Fahrplan](../../templates/compliance-roadmap-template.md)
