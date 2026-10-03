# EU AI Act: wo anfangen

**Die Verordnung ist groß, Ihre Kapazität ist es nicht.** Dieses Repository beantwortet eine Frage, die in den meisten Leitfäden fehlt: Was tut man **zuerst**, wenn eine Person das nebenbei macht?

*Where to start with the EU AI Act when the available capacity is one person, part-time: a sequenced path, and the misconceptions that waste the most time.*

---

## Die Lage, von der aus hier gedacht wird

Ein Unternehmen mit 40 Beschäftigten. Jemand aus dem Rechnungswesen oder der IT hat das Thema zusätzlich bekommen, hat vielleicht einen Tag im Monat dafür, und liest einen Leitfaden, der 60 Pflichten auflistet — ohne Reihenfolge.

Das Ergebnis ist meist eines von zwei: Es wird eine Richtlinie geschrieben, weil das machbar aussieht. Oder es wird gar nichts getan, weil alles gleich dringend wirkt.

Beides ist vermeidbar, und zwar mit einer einfachen Erkenntnis: **Die Pflichten sind nicht gleich dringend, und sie bauen aufeinander auf.**

## Vier Dinge, die heute gelten

Unabhängig von jeder Risikoklasse und von jeder Verschiebung:

| Pflicht | Seit | Aufwand |
|---|---|---|
| **Art. 5** — keine verbotenen Praktiken betreiben | 2.2.2025 | einmalig prüfen, gering |
| **Art. 4** — KI-Kompetenz der Beschäftigten | 2.2.2025 | mittel, wiederkehrend |
| **Art. 50** — Transparenz: Chatbots, erzeugte Inhalte | 2.8.2026 | technisch klein |
| GPAI-Pflichten | 2.8.2025 | betrifft Modellanbieter, nicht Sie |

**Hochrisiko nach Anhang III gilt erst ab 2.12.2027** — um 16 Monate verschoben durch den Digital Omnibus (Verordnung (EU) 2026/1744). Das ist die wichtigste Entlastung und die häufigste Fehlinterpretation zugleich.

## Was die Verschiebung nicht verschiebt

Sie betrifft den **Pflichtenkatalog** für Hochrisikosysteme. Sie betrifft nicht die zwei Schritte davor:

1. **Wissen, was man hat.** Ohne Register ist nicht feststellbar, ob man betroffen ist.
2. **Wissen, in welcher Rolle.** Nach Art. 25 kann eine Organisation unbemerkt zum **Anbieter** eines Hochrisikosystems werden — mit Konformitätsbewertung und technischer Dokumentation. Das ist keine Arbeit von sechs Wochen.

Wer bis Ende 2027 wartet, beginnt dann mit der Bestandsaufnahme und erfüllt die Pflichten gleichzeitig.

## Die Reihenfolge

| Phase | Was | Warum zuerst |
|---|---|---|
| **1** | Verbotenes ausschließen (Art. 5) | gilt seit 2025, und ein Treffer macht alles andere gegenstandslos |
| **2** | Bestand aufnehmen | ohne Register ist jede weitere Aussage eine Vermutung |
| **3** | Transparenz umsetzen (Art. 50) | gilt seit August 2026, technisch klein |
| **4** | KI-Kompetenz (Art. 4) | gilt seit 2025, und ohne sie funktioniert keine Aufsicht |
| **5** | Einstufen | jetzt mit Grundlage |
| **6** | Pflichten je Klasse | das meiste davon hat Zeit bis 2027 |

Ausführlich, mit Aufwandsschätzung je Phase: [Der Weg](./knowledge-base/eu-ai-act/compliance-path.md)

## Die acht Irrtümer, die am meisten Zeit kosten

1. „Der AI Act ist verschoben." — Art. 50 gilt seit August 2026.
2. „Wir nutzen nur fremde Tools, also sind wir nicht betroffen." — Betreiberpflichten gelten; und Art. 25 kann Sie zum Anbieter machen.
3. „Wir brauchen erst eine KI-Richtlinie." — Eine Richtlinie für einen unbekannten Bestand regelt nichts.
4. „Unser Anbieter ist konform, also sind wir es." — Seine Konformität ersetzt Ihre Betreiberpflichten nicht.
5. „Das macht der Datenschutzbeauftragte mit." — Teilweise, aber die Rollenfrage und die Einstufung sind nicht DSGVO.
6. „Wir sind zu klein." — Es gibt keine Schwelle nach Beschäftigtenzahl.
7. „Es entscheidet ja ein Mensch." — Nur, wenn er es tatsächlich kann.
8. „Hochrisiko betrifft uns nicht, wir machen keine Medizintechnik." — Beschäftigung und Kreditwürdigkeit sind die häufigeren Fälle.

Jeder mit Begründung: [Irrtümer](./knowledge-base/eu-ai-act/common-misconceptions.md)

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Was wann gilt](./knowledge-base/eu-ai-act/overview.md) | Fristen, und was heute schon zu tun ist |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | die sechs Begriffe, die man wirklich braucht |
| [Betrifft es uns](./knowledge-base/eu-ai-act/scope-and-actors.md) | Rolle, Art. 25, räumliche Geltung |
| [Die Klassen](./knowledge-base/eu-ai-act/risk-logic.md) | der Aufbau, ohne Einstufungslehre |
| [Der Weg](./knowledge-base/eu-ai-act/compliance-path.md) | sechs Phasen mit Aufwand und Ergebnis |
| [Irrtümer](./knowledge-base/eu-ai-act/common-misconceptions.md) | acht Sätze, die Zeit kosten |
| [Wer macht das](./knowledge-base/eu-ai-act/inventory-and-governance.md) | Zuständigkeit bei knapper Kapazität |

### Vorlage

[Fahrplan](./templates/compliance-roadmap-template.md) — die sechs Phasen mit Terminen, Verantwortlichen und Aufwand, zum Vorlegen in der Geschäftsführung.

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Danach

- [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) — Phase 2 im Detail
- [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) — Phase 5
- [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) — Phase 6
- [KI-Kompetenz](https://github.com/SimpleAct-Compliance/elearning) — Phase 4
- [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) — wie alles zusammenhängt

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt die Phasen als verbundene Register mit Fristen und Prüfprotokoll: **[AI Act Software](https://simpleact.de/ai-act-software)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
