---
protected: true
---

# 7. So ist ein guter Skill aufgebaut

Zwei Skills tragen fast denselben Namen. Der erste verspricht „professionelle Ergebnisse auf höchstem Niveau“. Der zweite beschreibt, welche Eingaben er benötigt, wie er mit fehlenden Angaben umgeht und wann die Bearbeitung endet. Der erste klingt eindrucksvoller. Der zweite lässt sich leichter beurteilen.

Ein guter Skill macht die Arbeitsweise verständlich. Er soll der KI Orientierung geben und Menschen ermöglichen, diese Orientierung zu prüfen. In diesem Kapitel betrachten wir den Aufbau aus fachlicher Sicht. Die vollständigen Dateien gehören weiterhin in die separate Sammlung. Sie lernen hier, welche Bestandteile wozu dienen und woran Sie Schwächen erkennen.

## 7.1 Zweck und Auslöser gehören zusammen

Die technische Grundlage eines Skill-Pakets ist die SKILL.md. Im offenen Agent-Skills-Format stehen am Anfang Metadaten, darunter Name und Beschreibung. Danach folgt die eigentliche Anleitung. Zusätzliche Referenzen, Materialien und Skripte können das Paket ergänzen.

Die Beschreibung sollte die Aufgabe so eingrenzen, dass eine passende Auswahl möglich wird. „Hilft im Vertrieb“ umfasst zu viel. „Strukturiert eingehende Kundenanfragen für die interne Vorbereitung eines Erstgesprächs“ benennt einen konkreten Anlass und ein Ergebnis.

Beschreiben Sie auch naheliegende Aufgaben, für die der Skill nicht vorgesehen ist. Ein Verfahren zur internen Anfrageübersicht soll nicht allein wegen des Wortes „Kunde“ jede Reklamation bearbeiten. Die fachliche Grenze reduziert Verwechslungen und erleichtert später Tests zur richtigen Auswahl.

## 7.2 Eingaben als Arbeitsgrundlage beschreiben

Eine Anleitung braucht ein klares Bild der benötigten Informationen. Welche Angaben sind unverzichtbar? Welche verbessern nur die Qualität? In welcher Form können sie vorliegen? Ein guter Skill verlangt nicht pauschal „alle relevanten Informationen“, sondern macht die Relevanz konkret.

Bei Lindenwerk ist der Text der Anfrage notwendig. Eine ergänzende Gesprächsnotiz kann hilfreich sein. Angaben zum Budget dürfen fehlen, solange das Ergebnis diese Lücke offen ausweist. Eine verbindliche Preisberechnung wäre unter denselben Voraussetzungen dagegen nicht möglich.

Unterscheiden Sie fehlende Angaben von nicht anwendbaren Angaben. „Budget unbekannt“ bedeutet etwas anderes als „Budget für diesen internen Vorgang nicht relevant“. Solche Unterschiede verhindern, dass eine Ausgabe vollständig aussieht, obwohl zentrale Informationen unklar geblieben sind.

## 7.3 Schritte nach ihrem fachlichen Zweck ordnen

Die Anleitung sollte eine nachvollziehbare Folge beschreiben. Für eine Anfrageübersicht könnte sie zunächst den Gegenstand bestimmen, anschließend belegte Angaben ordnen, Lücken und Widersprüche erfassen und daraus Fragen für das Erstgespräch ableiten.

Jeder Schritt braucht einen Zweck. Eine Aufforderung wie „Denke besonders gründlich nach“ beschreibt kein prüfbares Arbeitsergebnis. Die Anforderung, widersprüchliche Nutzerzahlen mit ihren jeweiligen Quellen gegenüberzustellen, ist dagegen konkret. Sie lässt sich in einem Testfall beobachten.

Vermeiden Sie unnötig starre Abläufe. Wenn keine Anhänge vorliegen, muss kein Anhangsschritt künstlich ausgefüllt werden. Wenn eine zentrale Eingabe fehlt, kann eine Rückfrage vor der weiteren Bearbeitung sinnvoll sein. Gute Anleitungen beschreiben solche Verzweigungen so, dass die Bearbeitung nicht lediglich eine Liste abarbeitet.

## 7.4 Ein Ergebnis mit erkennbaren Merkmalen verlangen

Ein festes Ausgabeformat hilft, wenn mehrere Menschen dieselbe Art von Ergebnis benötigen. Es sollte die nächste Handlung unterstützen. Für Lindenwerk sind eine kurze Bedarfsbeschreibung, bekannte Angaben, offene Fragen und ein vorgeschlagener nächster Schritt sinnvoll.

Das Format allein reicht jedoch nicht. Unter der Überschrift „Offene Fragen“ könnten belanglose Rückfragen stehen, während ein entscheidender Widerspruch übersehen wird. Ergänzen Sie deshalb fachliche Merkmale: Offene Fragen sollen sich aus fehlenden oder widersprüchlichen Angaben ergeben und für das Erstgespräch relevant sein.

Eine gute Ausgabe darf leer lassen, was tatsächlich nicht vorhanden ist. Wenn keine Entscheidung dokumentiert wurde, soll das Ergebnis nicht aus Höflichkeit eine erfinden. Der sichtbare Hinweis „Keine Entscheidung in den Unterlagen belegt“ kann die richtige Ausfüllung des betreffenden Abschnitts sein.

## 7.5 Fakten, Ableitungen und Annahmen trennen

Bei vielen betrieblichen Aufgaben muss ein Skill über eine reine Abschrift hinausgehen. Er soll Informationen ordnen oder nächste Schritte vorschlagen. Damit entstehen Ableitungen. Diese müssen als solche erkennbar bleiben.

Aus einer Anfrage nach besserer Dokumentensuche lässt sich ableiten, dass im Gespräch über Dokumentenbestände gesprochen werden sollte. Daraus folgt nicht, dass der Kunde bereits ein bestimmtes System verwendet. Der erste Satz ist eine begründete Gesprächsvorbereitung, der zweite wäre eine unbelegte Tatsachenbehauptung.

Eine gute Anleitung legt fest, wie diese Unterschiede dargestellt werden. Für wichtige Angaben kann sie eine Zuordnung zur Eingabe verlangen. Das bedeutet nicht, dass jede Zeile einen langen Quellenapparat benötigt. Eine kurze Angabe wie „Kunden-E-Mail“ oder „Gesprächsnotiz vom …“ kann innerhalb des Arbeitsdokuments genügen, sofern die Quelle eindeutig ist.

## 7.6 Lücken und Abbruchbedingungen einbauen

Ein Skill sollte wissen, was geschieht, wenn der normale Weg nicht möglich ist. Darf ein Entwurf mit gekennzeichneten Lücken entstehen? Muss zuerst nachgefragt werden? Wann ist ein Fall außerhalb des vorgesehenen Umfangs?

Für eine interne Anfrageübersicht können fehlende Angaben Teil des Ergebnisses sein. Für eine abschließende Angebotskalkulation wären fehlende Mengen oder Preise möglicherweise ein Grund, die Berechnung nicht vorzunehmen. Dieselbe Lücke hat je nach Aufgabe eine andere Bedeutung.

Formulieren Sie Abbruchbedingungen anhand beobachtbarer Situationen. „Bei Unsicherheit vorsichtig sein“ bleibt unbestimmt. „Wenn zwei maßgebliche Quellen unterschiedliche Mengen nennen und keine Priorität festgelegt ist, die Abweichung ausweisen und keine verbindliche Kalkulation erstellen“ beschreibt ein überprüfbares Verhalten.

## 7.7 Materialien gezielt auslagern

Eine lange Anleitung wird nicht automatisch besser, wenn sie alle denkbaren Informationen enthält. Stabile fachliche Regeln, umfangreiche Vorlagen und Beispiele können in getrennten Materialien übersichtlich bereitgestellt werden. Der Skill muss dann deutlich machen, wann welche Datei gebraucht wird.

Trennen Sie verschiedene Aufgaben der Materialien. Eine Vorlage bestimmt die Struktur. Eine Referenz beschreibt fachliche Regeln. Ein Beispiel zeigt, wie eine Regel im konkreten Fall aussieht. Ein Skript kann eine klar umrissene technische Verarbeitung übernehmen. Diese Bestandteile sollten nicht gegenseitig ihre Funktion verschleiern.

Für Lindenwerk könnte die gültige Leistungsübersicht eine Referenz sein. Ein früheres Kundenangebot ist dagegen kein geeigneter allgemeiner Regelkatalog. Es enthält fallspezifische Vereinbarungen. Wer beides vermischt, riskiert, dass eine Ausnahme des alten Projekts zur vermeintlichen Standardleistung wird.

## 7.8 Gute Beispiele zeigen auch Grenzen

Ein gelungenes Beispiel verdeutlicht, wie Eingaben in ein Ergebnis übergehen. Es sollte kurz genug sein, dass Leser die Zuordnung prüfen können. Besonders hilfreich ist eine kleine Erläuterung, warum eine bestimmte Formulierung richtig ist.

Ergänzen Sie mindestens ein Beispiel mit einer Lücke oder einem Widerspruch. Sonst lernt der Leser nur den idealen Verlauf kennen. Bei Lindenwerk könnte die richtige Ausgabe zeigen, dass aus „möglichst im Oktober“ keine bestätigte Umsetzungsfrist wird.

Ein Gegenbeispiel sollte den Fehler präzise benennen. „Unprofessionell“ ist als Bewertung zu unbestimmt. „Stellt einen Kundenwunsch als zugesagte Leistung dar“ bezeichnet die fachliche Schwäche. Diese Beschreibung kann später auch in eine Prüfliste oder einen Testfall übernommen werden.

## 7.9 Verständlichkeit vor Länge

Lesen Sie eine Anleitung aus Sicht einer Person, die den ursprünglichen Autor nicht befragen kann. Sind Begriffe erklärt? Ist klar, welche Datei maßgeblich ist? Passen die Anweisungen zum erwarteten Ergebnis? Gibt es zwei Stellen, die denselben Fall unterschiedlich regeln?

Streichen Sie Wiederholungen, die keine zusätzliche Entscheidung klären. Ergänzen Sie dagegen dort, wo eine Regel nur angedeutet wird. Ein guter Skill ist so ausführlich wie für die Aufgabe nötig. Die Zahl seiner Zeilen ist kein Qualitätsmerkmal.

Achten Sie auf absolute Versprechen. Eine Anleitung kann Prüfungen vorsehen, aber nicht allein dadurch Fehlerfreiheit garantieren. Formulierungen sollten das tatsächlich vorgesehene Verfahren beschreiben. Die Zuverlässigkeit wird mit passenden Fällen untersucht, nicht durch selbstbewusste Adjektive hergestellt.

## 7.10 Was das für Ihre Rolle bedeutet

### Für Geschäftsführer

Prüfen Sie Zweck, Grenzen und Ergebnisanforderungen. Sie müssen nicht jede technische Zeile verstehen, sollten aber erklären können, für welche Entscheidung oder Handlung der Skill Vorarbeit leistet.

Achten Sie darauf, dass Unternehmensregeln erkennbar von einzelnen Kundenvereinbarungen getrennt sind. Eine unbemerkte Verallgemeinerung kann später größere Wirkung entfalten als ein sprachlicher Fehler.

### Für IT-Leiter

Prüfen Sie, welche Dateien und Werkzeuge referenziert werden und ob diese Verweise vollständig sind. Technische Zusatzfunktionen brauchen einen erkennbaren fachlichen Zweck und einen eigenen überprüfbaren Umfang.

Unterscheiden Sie Regeln in der Anleitung von technisch erzwungenen Grenzen. Ein beschriebenes Verbot ist noch keine Zugriffskontrolle. Diese Unterscheidung gehört in die Beurteilung des Gesamtverfahrens.

### Für Selbstständige

Lesen Sie vorhandene Skills wie eine Arbeitsanweisung, für deren Ergebnis Sie einstehen müssen. Wenn Sie eine Passage fachlich nicht beurteilen können, klären Sie sie vor der Verwendung in Ihrer Leistung.

Bevorzugen Sie klare Einsatzbedingungen und nachvollziehbare Beispiele. Ein großer Funktionsumfang hilft wenig, wenn Sie bei jedem Auftrag erst herausfinden müssen, welche Teile tatsächlich gelten.

### Für Abteilungsleiter

Lassen Sie die Ergebnisanforderungen von den späteren Empfängern prüfen. Ein formal vollständiges Dokument kann im Team trotzdem wenig helfen, wenn die entscheidenden Informationen schwer zu finden sind.

Sammeln Sie gute und fehlerhafte Beispiele mit kurzer Begründung. Sie machen die fachlichen Erwartungen für neue Beschäftigte und für die spätere Anpassung des Skills sichtbar.

## 7.11 Einen Kandidaten fachlich lesen

Nehmen Sie einen vorhandenen Skill und markieren Sie Zweck, Eingaben, Schritte, Ausgabe und Verhalten bei Lücken. Schreiben Sie zu jedem Bestandteil auf, ob er klar, unklar oder nicht vorhanden ist. Prüfen Sie anschließend, ob die Teile zusammenpassen.

Halten Sie drei konkrete Fragen fest, die vor einem Einsatz beantwortet werden müssen. Damit entsteht eine begründete Beurteilung, die über einen allgemeinen Eindruck hinausgeht. Im nächsten Kapitel wird daraus eine gezielte Anpassung.

### Was Sie aus diesem Kapitel mitnehmen

Ein guter Skill verbindet einen klaren Anlass mit geeigneten Eingaben, nachvollziehbaren Schritten und prüfbaren Ergebnissen. Materialien und Beispiele unterstützen diese Arbeitsweise. Besonders aufschlussreich ist, wie die Anleitung mit fehlenden Informationen und Fällen außerhalb ihres Umfangs umgeht.
