# EU AI Act: wo anfangen — Volltext

Dieses Dokument fasst das Repository in einem Stück zusammen.

## Die Lage, von der aus hier gedacht wird

Ein Unternehmen mit 40 Beschäftigten. Jemand aus der IT oder dem Rechnungswesen hat das Thema zusätzlich bekommen, hat vielleicht einen Tag im Monat, und liest einen Leitfaden mit 60 Pflichten ohne Reihenfolge.

Das Ergebnis ist meist eines von zwei: Es wird eine Richtlinie geschrieben, weil das machbar aussieht. Oder es wird gar nichts getan, weil alles gleich dringend wirkt. Beides ist vermeidbar — die Pflichten sind nicht gleich dringend, und sie bauen aufeinander auf.

## Was heute gilt

Nach dem Digital Omnibus (Verordnung (EU) 2026/1744, in Kraft seit 27.7.2026) sind drei Pflichten anwendbar, die jedes Unternehmen betreffen, das KI einsetzt:

**Art. 5** — keine verbotenen Praktiken, seit 2.2.2025. **Art. 4** — KI-Kompetenz, seit 2.2.2025, ohne Risikoklasse und ohne Größenschwelle. **Art. 50** — Transparenz, seit 2.8.2026.

**Hochrisiko nach Anhang III gilt erst ab 2.12.2027**, um 16 Monate verschoben. Das ist die wichtigste Entlastung und die häufigste Fehlinterpretation zugleich: Wer daraus schließt, der AI Act sei verschoben, betreibt heute unkennzeichnete Chatbots.

Was die Verschiebung nicht verschiebt, sind die zwei Schritte davor: zu wissen, welche KI im Haus ist, und in welcher **Rolle**. Nach Art. 25 kann eine Organisation unbemerkt zum Anbieter eines Hochrisikosystems werden — mit Konformitätsbewertung und technischer Dokumentation, und das ist ein Projekt über Monate. Wer im Dezember 2027 feststellt, dass er seit zwei Jahren Anbieter ist, hat ein anderes Problem als jemand, der es 2026 festgestellt hat.

## Die sechs Phasen

**1 Verbotenes ausschließen.** Art. 5, acht Praktiken, an den tatsächlich eingesetzten Werkzeugen durchgehen. Die beiden, die in gekaufter Software vorkommen: Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen, und ungezieltes Auslesen von Gesichtsbildern. Eine Funktion, die Gespräche nach Stimmung auswertet, ist Emotionserkennung — am Arbeitsplatz verboten, nicht reguliert. Aufwand: ein halber Tag. Ergebnis: acht Zeilen mit Datum.

**2 Bestand aufnehmen.** Aus fünf Quellen suchen, nicht fragen: Beschaffung und Kreditorenliste, Auslagenerstattung, Anmeldedienst, aggregierte Netzprotokolle, Release-Notes bestehender Software. Die letzte liefert den häufigsten Fall: Ein CRM bekommt eine Zusammenfassungsfunktion, und ab diesem Release verarbeitet ein KI-System Kundendaten, ohne dass ein Projekt existiert. Aufwand: 3 bis 8 Tage. Ergebnis: ein Register mit einem Eintrag je Einsatzzweck, und ein Suchprotokoll — letzteres ist in einer Prüfung wichtiger als die Vollständigkeit selbst, weil es belegt, dass gesucht wurde.

**3 Transparenz umsetzen.** Art. 50, seit August 2026 anwendbar, technisch meist klein, fast überall übersehen. Hinweis bei direktem Kontakt, sichtbar vor der ersten Eingabe; maschinenlesbare Kennzeichnung erzeugter Inhalte. Nachweis je Fall mit Datum **und Produktversion** — ohne Version belegt eine Bildschirmaufnahme nur, dass es einmal so aussah.

**4 KI-Kompetenz.** Art. 4, seit Februar 2025. Systembezogen schulen: wie dieses Modell irrt, woran man eine falsche Ausgabe erkennt, was man damit tun darf, was nicht hineingegeben werden darf. Eine allgemeine KI-Schulung erfüllt den Punkt nicht. Teilnahmeliste mit Datum und Inhaltsangabe — eine Liste ohne Inhalt belegt Anwesenheit, nicht Kompetenz.

**5 Einstufen.** Je Einsatzzweck, in dieser Reihenfolge: KI-System, Ausnahme, Art. 5, Anhang I/III, Art. 50. Dazu die Rollenfrage. Aufwand: 2 bis 4 Stunden je Einsatzzweck. Ergebnis: eine Klasse mit Begründung und Annahmen; das Annahmenfeld fehlt am häufigsten und ist in einer Prüfung das wertvollste.

**6 Pflichten je Klasse.** Der größte Teil hat Zeit. Jetzt schon sinnvoll, auch ohne Hochrisikosystem: menschliche Aufsicht benennen und ausübbar machen, einen Meldeweg für Fehlfunktionen schaffen, Auslöser je System eintragen, einen Testsatz gegen den stillen Modellwechsel einrichten.

Die Phasen 1 bis 4 sind zusammen etwa zwei Arbeitswochen und decken alles ab, was heute fällig ist. Der Teil mit Frist ist überschaubar; der große Teil hat Zeit.

## Die eine Frage, die den Einstieg möglich macht

> Berührt die Ausgabe dieses Systems Beschäftigung, Bildung, Kreditwürdigkeit, Strafverfolgung, Migration, Justiz, wesentliche Dienstleistungen oder kritische Infrastruktur?

Eine Tatsachenfrage, keine Rechtsfrage. Der Fachbereich kann sie beantworten; ein Jurist kann sie nicht stellen, wenn er von dem System nichts weiß. Bei Ja folgt eine rechtliche Bewertung, bei Nein gehört das Nein mit Datum festgehalten — ein geprüftes Nein ist ein Nachweis.

Beschäftigung und wesentliche Dienstleistungen sind die zwei Anhang-III-Bereiche, die gewöhnliche Unternehmen treffen. Beschäftigung ist der häufigste und unauffälligste, weil Personalwerkzeuge selten als KI-Projekt beschafft werden.

## Acht Irrtümer

Der AI Act sei verschoben — Art. 50 gilt seit August 2026. Wir nutzen nur fremde Tools — Betreiberpflichten gelten, und Art. 25 kann Sie zum Anbieter machen. Wir brauchen erst eine Richtlinie — eine Richtlinie für einen unbekannten Bestand regelt nichts und verlagert die Nutzung auf private Geräte. Unser Anbieter ist konform — seine Konformität ersetzt Ihre Betreiberpflichten nicht, und konform ist eine Behauptung, bis eine Fundstelle existiert. Das macht der Datenschutzbeauftragte mit — teilweise, aber Rollenbestimmung, Einstufung, Art. 50 und Art. 4 sind nicht DSGVO. Wir sind zu klein — es gibt keine Schwelle. Es entscheidet ja ein Mensch — nur, wenn er Zeit hat, befugt ist und die Ausgabe versteht. Hochrisiko betrifft uns nicht — Beschäftigung und Kreditwürdigkeit sind die häufigeren Fälle.

Ein neunter, der seltener ausgesprochen wird: dass man warte, bis sich die Rechtslage geklärt hat. Die Unsicherheit betrifft die Erfüllung der Hochrisikopflichten, nicht die Feststellung der eigenen Lage — und die wird durch keine Leitlinie einfacher.

## Wer das macht

Es muss eine **Person** sein, keine Abteilung, mit einem benannten **Zeitbudget**. Zentral möglich sind: Fristen kennen, Weg planen, Art. 5 prüfen, Suche anstoßen, Schulung organisieren. Nicht zentral möglich: Inventareinträge aktuell halten und Aufsicht ausüben. Eine zentrale Stelle mit achtzig Einträgen kann bei keinem sagen, ob er noch stimmt.

Der Aufnahmeweg entscheidet über alles Weitere: acht Felder werden ausgefüllt, vierzig werden umgangen. Und ein Verbot hilft nicht — es verlagert die Nutzung dorthin, wo sie unsichtbar ist. Schatten-KI entsteht selten aus Trotz; jemand hatte eine Aufgabe, ein Werkzeug half, und es gab keinen erkennbaren Weg, das anzumelden.

In kleinen Häusern ist die Rollentrennung schwierig. Die ehrliche Lösung ist die abgeschwächte Form, ausdrücklich dokumentiert: Die Umsetzende prüft, eine zweite Person sieht die Prüfung nach. Was nicht geht, ist die Trennung zu behaupten.

## Was vorgelegt wird

Drei Zahlen, nicht die Pflichtenliste: Wie viele KI-Einsatzzwecke gibt es? Wie viele berühren einen Anhang-III-Bereich? Welche Pflichten sind heute fällig und noch offen?

Und vier Entscheidungen, die die Geschäftsführung treffen muss: wer zuständig ist mit welchem Zeitbudget; ob Systeme mit offenen Befunden weiterlaufen; ob ein Werkzeug wegen eines Art.-5-Treffers abgeschaltet wird; ob externe Hilfe geholt wird.

Die zweite bleibt in der Praxis meist unausgesprochen. Ein System läuft weiter, obwohl ein Befund offen ist — das ist zulässig und gehört als Entscheidung festgehalten, nicht als Versäumnis entstehen gelassen.

## Weg durch das Repository

1. [Was wann gilt](./knowledge-base/eu-ai-act/overview.md)
2. [Sechs Begriffe](./knowledge-base/eu-ai-act/definitions.md)
3. [Betrifft es uns](./knowledge-base/eu-ai-act/scope-and-actors.md)
4. [Der Weg](./knowledge-base/eu-ai-act/compliance-path.md) — sechs Phasen mit Aufwand
5. [Irrtümer](./knowledge-base/eu-ai-act/common-misconceptions.md)
6. [Wer macht das](./knowledge-base/eu-ai-act/inventory-and-governance.md)
7. [Fahrplan](./templates/compliance-roadmap-template.md) ausfüllen und vorlegen

---

Keine Rechtsberatung. Stand: Oktober 2026.
