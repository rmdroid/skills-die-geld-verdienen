---
protected: true
---

# 1. Was ein KI-Skill ist – und was er leisten kann

## 1.1 Eine Arbeitsanweisung, die wiederverwendbar wird

Am Ende einer Projektbesprechung liegen einige Notizen vor. Ein Termin wurde verschoben, eine technische Frage ist offen, und jemand hat vorgeschlagen, den Umfang der ersten Ausbaustufe zu verkleinern. Nun soll daraus ein Protokoll entstehen, das auch eine abwesende Kollegin versteht.

Die Aufforderung „Fasse diese Notizen zusammen“ lässt viel offen. Soll die Zusammenfassung den Gesprächsverlauf nacherzählen? Soll sie Entscheidungen hervorheben? Müssen Aufgaben mit Verantwortlichen und Fristen enthalten sein? Und wie wird ein Vorschlag dargestellt, über den noch nicht entschieden wurde?

Eine erfahrene Projektleiterin würde diese Unterschiede wahrscheinlich berücksichtigen. Sie kennt den Zweck des Protokolls. Vielleicht hat sie gelernt, dass ein zu beiläufig formulierter Vorschlag später als Auftrag verstanden wird. Ihr Vorgehen besteht deshalb aus mehr als gutem Schreiben. Sie ordnet Aussagen ein, sucht nach fehlenden Angaben und achtet auf die Folgen der Formulierung.

Ein KI-Skill kann Teile dieses Vorgehens ausdrücklich beschreiben und wiederverwendbar machen. Für dieses Buch verwenden wir folgende Arbeitsdefinition: Ein Skill ist ein abgegrenztes Paket aus Anweisungen und gegebenenfalls ergänzenden Materialien, das ein KI-System bei einer bestimmten Aufgabe unterstützt. Er beschreibt eine Vorgehensweise; die aktuellen Eingaben liefern den jeweiligen Fall.

Der Begriff wird im Alltag unterschiedlich weit verwendet. Manchmal ist damit lediglich eine gespeicherte Anweisung gemeint. Beim offenen Agent-Skills-Format handelt es sich um einen Ordner mit einer Datei namens SKILL.md. Diese enthält Angaben zum Skill und seine Anweisungen. Weitere Dateien können hinzukommen. Wenn wir später einen konkreten Download besprechen, unterscheiden wir deshalb zwischen dem installierbaren Paket und einer angepassten Textanleitung für den Chat.

Diese Unterscheidung hat praktische Folgen. Eine Textanleitung kann beispielsweise festlegen, wie ein Protokoll gegliedert werden soll. Ein vollständiges Paket kann zusätzlich eine Vorlage und ein Hilfsprogramm enthalten. Wer nur die Anweisung kopiert, hat damit noch nicht die Funktionen dieses Hilfsprogramms übernommen.

## 1.2 Der aktuelle Auftrag und die dauerhafte Vorgehensweise

Bei einem wiederkehrenden Ablauf ändern sich manche Informationen von Fall zu Fall. Andere bleiben über längere Zeit gleich. Im Protokollbeispiel wechseln Teilnehmende, Themen und Entscheidungen. Die Forderung, Vorschläge von Beschlüssen zu unterscheiden, bleibt bestehen.

Diese Trennung erleichtert die Arbeit mit Skills. Der aktuelle Auftrag könnte lauten: „Erstelle aus den beigefügten Notizen das interne Ergebnisprotokoll für das Projekt Dokumentensuche.“ Er benennt die Aufgabe und das Material. Der Skill ergänzt die wiederkehrende Vorgehensweise: Gesprächsinhalte ordnen, Beschlüsse kennzeichnen, Aufgaben erfassen und fehlende Zuständigkeiten sichtbar machen.

Unternehmensspezifische Vorgaben bilden eine weitere Ebene. Vielleicht sollen Protokolle immer eine Projektnummer enthalten. Vielleicht dürfen Kundennamen in einer bestimmten internen Übersicht nur abgekürzt erscheinen. Solche Regeln können in geeigneten Referenzen oder Anweisungen bereitgestellt werden. Sie müssen aber auffindbar, aktuell und für den konkreten Einsatz freigegeben sein.

Hilfreich ist die Frage: Würde diese Information auch beim nächsten vergleichbaren Auftrag gelten? Wenn ja, ist sie ein Kandidat für die dauerhafte Vorgehensweise oder ihre Referenzen. Wenn nein, gehört sie eher zu den Eingaben des aktuellen Falls. Das verhindert, dass eine alte Kundenangabe versehentlich zum Standard für alle späteren Vorgänge wird.

Ein häufiger Fehler besteht darin, einen erfolgreichen Einzelversuch unverändert als allgemeine Anleitung zu speichern. Im Versuch standen vielleicht bereits der richtige Preis, eine besondere Frist und der Name der zuständigen Person. Bei der Wiederverwendung wirken diese Details dann wie Vorgaben. Die scheinbare Zeitersparnis führt zu Korrekturaufwand, weil nicht sauber zwischen Beispiel und Regel unterschieden wurde.

## 1.3 Wie ein Skill-Paket aufgebaut sein kann

Im offenen Format ist SKILL.md die zentrale Datei. Die Endung .md steht für Markdown, ein lesbares Textformat mit einfachen Auszeichnungen etwa für Überschriften. Der Dateianfang enthält strukturierte Angaben, mindestens Name und Beschreibung. Danach folgen die Anweisungen. Die Beschreibung soll auch erkennen lassen, bei welchen Aufgaben der Skill relevant ist.

Für den geschäftlichen Einsatz ist weniger die Schreibweise der Datei interessant als die Frage, was darin geregelt wird. Welches Ergebnis soll entstehen? Welche Angaben müssen vorliegen? In welcher Reihenfolge wird gearbeitet? Was geschieht bei Widersprüchen? Welche Kontrolle ist vorgesehen? Solche Fragen können in der Hauptdatei beantwortet werden, ohne dass sie bereits ein großes Softwareprojekt daraus machen.

Ergänzende Referenzen können Fachinformationen enthalten. Vorlagen geben beispielsweise die Gliederung eines Berichts vor. Skripte sind ausführbare Programme, die bestimmte Arbeitsschritte übernehmen können. Ein Skill muss nicht alle diese Bestandteile besitzen. Für eine eng umrissene Textaufgabe kann eine verständliche Anleitung genügen.

Entscheidend ist, ob die zusätzlichen Bestandteile etwas Konkretes leisten. Eine zehnseitige Referenzdatei ist kein Qualitätsmerkmal für sich. Sie kann nützlich sein, wenn sie freigegebene Leistungspakete beschreibt. Sie kann hinderlich sein, wenn sie veraltete Angaben enthält oder dieselben Regeln an mehreren Stellen unterschiedlich formuliert.

Die folgende Abbildung ordnet die Bestandteile in einen Arbeitszusammenhang ein. Sie zeigt zugleich, warum ein Skill allein noch kein Ergebnis erzeugt: Eingaben, ausführende Umgebung und anschließende Prüfung gehören dazu.

![Abbildung 1: Eingaben und Skill-Paket werden von einer geeigneten KI-Umgebung verarbeitet. Das Ergebnis bleibt Gegenstand fachlicher Prüfung.](/images/abbildung-1.png)

Ein Beispiel: Eine freigegebene Preisliste ist eine Referenz. Eine Angebotsgliederung ist eine Vorlage. Ein kleines Programm, das Positionen addiert, ist ein Werkzeug. Die Anweisung, nur freigegebene Preise zu verwenden und fehlende Preise als offen zu kennzeichnen, gehört zur Vorgehensweise. Erst das Zusammenspiel macht daraus einen nützlichen Arbeitsablauf.

## 1.4 Was beim Einsatz geschieht

Das offene Format sieht ein bedarfsgerechtes Laden vor. Zunächst können Name und Beschreibung helfen, einen passenden Skill zu erkennen. Bei Aktivierung werden die ausführlichen Anweisungen gelesen. Ergänzende Materialien können bei Bedarf hinzukommen. Wie die Auswahl und das Laden konkret umgesetzt sind, hängt von der jeweiligen Anwendung ab.

Für Anwender ergibt sich daraus eine wichtige Frage: Wurde der vorgesehene Skill tatsächlich verwendet? Ein passendes Ergebnis allein beweist das nicht. Die KI könnte auch ohne die zusätzliche Anleitung eine plausible Antwort erzeugt haben. Umgekehrt kann ein wenig passender Name oder eine unklare Beschreibung die Auswahl erschweren.

In einer geeigneten Testumgebung sollten Sie daher nachvollziehen können, welche Anweisungen und Dateien herangezogen wurden. Die Selbstauskunft der KI kann bei der Orientierung helfen, ersetzt aber keine sichtbaren Ausführungsinformationen, soweit die Umgebung diese bereitstellt. Bei einem reinen Chatversuch dokumentieren Sie zumindest die verwendete Anweisung, die Eingaben und das Ergebnis.

Für den Anfang müssen Sie nicht jede interne Verarbeitung verstehen. Sie sollten aber die Grenze zwischen Verfügbarkeit und Verwendung kennen. Eine Datei auf Ihrem Rechner kann nur dann Einfluss haben, wenn die eingesetzte Umgebung sie auch lesen und in die Bearbeitung einbeziehen kann. Ein Download allein ist noch keine Einrichtung.

Ebenso wenig verleiht die Erwähnung eines Werkzeugs im Skill der KI automatisch Zugriff darauf. Wenn eine Anleitung ein Kundenverwaltungssystem abfragen soll, muss die entsprechende Verbindung tatsächlich vorhanden und passend berechtigt sein. Fehlt sie, braucht der Ablauf entweder geeignete bereitgestellte Daten oder eine klar benannte Unterbrechung. Die fehlende Verbindung darf nicht durch erfundene Informationen verdeckt werden.

## 1.5 Prompt, Skill, Agent und Automatisierung

Vier Begriffe begegnen Ihnen in diesem Themenfeld besonders häufig. Ihre Grenzen werden je nach Produkt unterschiedlich gezogen. Für die Arbeit in diesem Buch ist die folgende funktionale Unterscheidung hilfreich.

Ein Prompt ist eine Eingabe an das KI-System. Er kann kurz sein oder eine ausführliche Vorgehensweise enthalten. Wenn Sie die KI bitten, einen Text zu kürzen, formulieren Sie einen Prompt. Auch eine sorgfältig ausgearbeitete, wiederverwendete Anweisung bleibt zunächst eine Eingabe, solange sie auf diesem Weg übergeben wird.

Ein Skill verpackt eine Vorgehensweise für einen bestimmten Aufgabentyp. Er kann Anweisungen mit weiteren Dateien verbinden und in einer passenden Umgebung gezielt verfügbar gemacht werden. Ein ausführlicher Prompt und ein einfacher Skill können sich inhaltlich stark ähneln. Der Unterschied liegt dann vor allem darin, wie die Anleitung organisiert, ausgewählt und mit weiteren Materialien verwendet wird.

Als Agent bezeichnen wir hier eine KI-gestützte Ausführungseinheit, die innerhalb vorgegebener Grenzen mehrere Schritte bearbeiten und gegebenenfalls Werkzeuge nutzen kann. Sie kann einen Skill als Anleitung heranziehen. Der Skill ist dabei nicht selbst der handelnde Mitarbeiter. Er liefert einen Teil der Vorgaben für das ausführende System.

Eine Automatisierung regelt beispielsweise, wann ein Ablauf startet und welche Systeme miteinander verbunden werden. Eine neu eingegangene Datei könnte einen Verarbeitungsschritt auslösen. Das kann mit oder ohne KI geschehen. Umgekehrt können Sie einen Skill manuell starten, ohne irgendeinen zeitgesteuerten oder ereignisgesteuerten Ablauf einzurichten.

Für die Lindenwerk Services GmbH lässt sich das an einem Protokoll erklären. Eine Mitarbeiterin gibt den Auftrag. Der Protokoll-Skill beschreibt die fachliche Bearbeitung. Eine geeignete KI-Umgebung führt sie aus. Erst eine zusätzlich eingerichtete Automatisierung würde beispielsweise nach jeder neuen Transkriptdatei selbstständig einen Entwurf anstoßen. Ob anschließend etwas gespeichert oder versendet wird, ist wiederum eine eigene Festlegung.

Diese Trennung verhindert überzogene Erwartungen. Wer einen Skill herunterlädt, erhält nicht automatisch einen rund um die Uhr arbeitenden Prozess. Wer einen Ablauf automatisiert, hat damit noch nicht seine fachliche Qualität gesichert. Beides kann zusammenwirken, muss aber getrennt verstanden und geprüft werden.

## 1.6 Ein Protokollbeispiel: Was soll übernommen werden?

Die folgende Situation ist fiktiv. In einer Besprechung zur Dokumentensuche fallen drei Aussagen. Eine Person schlägt vor, die erste Ausbaustufe auf Rechnungen zu begrenzen. Eine zweite möchte vorher prüfen, ob die Geschäftsführung auch Verträge einbeziehen will. Schließlich sagt die Projektleiterin zu, diese Frage am Donnerstag zu klären.

Ein ungenauer Ergebnistext könnte daraus machen: „Die erste Ausbaustufe umfasst Rechnungen. Die Projektleiterin setzt die Einschränkung bis Donnerstag um.“ Der Satz ist flüssig, verändert aber den Inhalt. Aus einem Vorschlag wird ein Beschluss, aus einer Klärung eine Umsetzung und aus einer offenen Frage eine festgelegte Grenze.

Eine brauchbare Vorgehensweise würde drei Kategorien unterscheiden. Unter „Vorschlag“ steht die Beschränkung auf Rechnungen. Unter „Offene Frage“ steht die mögliche Einbeziehung von Verträgen. Unter „Aufgabe“ steht die Klärung durch die Projektleiterin am Donnerstag. Das Ergebnis kann knapp bleiben und dennoch genauer sein.

Für den Skill bedeutet das: Die Anweisung muss diese Unterscheidung vorsehen. Sie sollte außerdem festlegen, was passiert, wenn eine Aussage nicht eindeutig zugeordnet werden kann. Eine Rückfrage oder eine Markierung als ungeklärt ist dann oft hilfreicher als eine vollständige, aber unzutreffende Liste.

Für die Prüfung bedeutet es: Sie kontrollieren nicht nur Rechtschreibung und Lesbarkeit. Sie vergleichen die entscheidenden Aussagen mit dem Ausgangsmaterial. Hat sich der Status verändert? Wurde ein Termin ergänzt? Ist eine Person als verantwortlich eingetragen, obwohl sie lediglich an der Diskussion beteiligt war?

Dieses Beispiel ist bewusst klein. An einem kurzen Ausschnitt lassen sich solche Fehler leichter erkennen als an einem langen Protokoll. Für erste Tests lohnt es sich deshalb, wenige Aussagen mit klar unterscheidbarer Bedeutung zu verwenden. Erst wenn der Ablauf diese Situationen brauchbar behandelt, ist ein umfangreicheres Beispiel sinnvoll.

## 1.7 Standardisierung ist keine Ergebnisgarantie

Ein gut beschriebener Ablauf kann die Bearbeitung strukturieren. Er ist aber kein Nachweis dafür, dass jede Vorgabe in jedem Durchlauf korrekt umgesetzt wird. Schon die Eingaben können unvollständig sein. Auch eine klare Anweisung kann falsch auf den konkreten Fall angewendet werden. Hinzu kommen mögliche Fehler in Referenzen oder Werkzeugen.

Daraus folgt eine nüchterne Haltung: Der Skill macht Anforderungen ausdrücklich und damit prüfbar. Er entbindet Sie nicht davon, ihre Einhaltung zu kontrollieren. Wenn Ihr Skill verlangt, jede Empfehlung mit einer Quelle zu verbinden, müssen Sie zumindest stichprobenartig untersuchen, ob die genannte Quelle existiert und die Aussage trägt.

Besonders wichtig ist die Unterscheidung zwischen einem Entwurf und einer freigegebenen Handlung. Ein vorbereiteter Antworttext kann noch korrigiert werden. Eine versendete Nachricht erreicht den Kunden. Ein Vorschlag zur Änderung eines Projektplans ist etwas anderes als die tatsächlich gespeicherte Änderung. Solche Übergänge sollten ausdrücklich geregelt sein.

Die Abbildung zeigt einen bewusst begrenzten Ablauf. Die KI erstellt einen Entwurf. Anschließend wird entschieden, ob er geprüft und verwendbar ist, korrigiert werden muss oder wegen fehlender Angaben zurückgestellt wird. Es gibt keinen sachlichen Grund, einen unvollständigen Fall allein deshalb freizugeben, weil bereits ein Text vorliegt.

![Abbildung 2: Ein Entwurf führt über die Prüfung entweder zur Freigabe oder zurück zur Klärung. Fehlende Informationen bleiben ein eigener Bearbeitungszustand.](/images/abbildung-2.png)

Wie tief die Kontrolle gehen muss, hängt von der Aufgabe ab. Bei einer internen Themenliste genügt möglicherweise eine kurze Durchsicht. Bei einer Zusage an einen Kunden müssen Leistungsumfang, Preise und Termine sorgfältig geprüft werden. Diese Unterschiede sollten schon bei der Auswahl des Einsatzfalls berücksichtigt werden.

## 1.8 Was ein Skill nicht reparieren kann

Wenn im Unternehmen niemand festgelegt hat, wer eine bestimmte Entscheidung treffen darf, kann der Skill diese Zuständigkeit nicht verlässlich aus der Luft erzeugen. Er kann die Lücke sichtbar machen oder nachfragen. Die organisatorische Entscheidung bleibt erforderlich.

Dasselbe gilt für widersprüchliche Vorgaben. Angenommen, eine alte Vorlage nennt eine Reaktionszeit von zwei Tagen, eine neue Leistungsbeschreibung aber einen Tag. Eine Anweisung, „die Unterlagen zu berücksichtigen“, löst diesen Konflikt noch nicht. Es braucht eine Regel, welche Quelle maßgeblich ist, oder eine Klärung durch die verantwortliche Person.

Auch eine unübersichtliche Datenablage verschwindet nicht durch eine gute Skill-Datei. Wenn wichtige Unterlagen fehlen oder mehrere Fassungen denselben Namen tragen, muss die Bearbeitung mit dieser Unsicherheit umgehen. Es wäre irreführend, die entstehende Suche nach der richtigen Datei vollständig als KI-Problem zu behandeln.

Ein weiterer Grenzfall ist die seltene, neuartige Entscheidung. Ein Skill kann dafür Fragen strukturieren und Materialien ordnen. Wenn jedoch kaum belastbare Erfahrungen vorliegen, kann eine feste Anleitung die notwendige Auseinandersetzung auch zu früh verengen. Dann besteht ihr Nutzen eher darin, Annahmen offenzulegen, als eine fertige Empfehlung zu erzeugen.

Sie sollten deshalb vor der Einführung fragen, welcher Teil des Problems durch eine wiederverwendbare Vorgehensweise bearbeitbar ist. Vielleicht ist das Schreiben des Berichts gut geeignet, die Klärung der Projektverantwortung aber nicht. Eine saubere Grenze macht den Skill nützlicher, weil seine Aufgabe verständlich bleibt.

## 1.9 Woran Sie einen brauchbaren Kandidaten erkennen

Ein guter erster Eindruck entsteht, wenn Sie den Zweck des Skills in eigenen Worten erklären können. „Hilft bei Geschäftsaufgaben“ ist zu breit. „Erstellt aus bereitgestellten Projektinformationen einen Bericht mit Abweichungen und Entscheidungsbedarf“ beschreibt eine prüfbare Aufgabe.

Als Nächstes sollten Sie erkennen, was der Skill benötigt. Genügen Text und Dateien? Erwartet er eine bestimmte Vorlage? Greift er auf Programme oder externe Dienste zu? Eine Anleitung, deren Voraussetzungen zu Ihrer Umgebung nicht passen, wird durch häufiges Ausprobieren nicht automatisch geeigneter.

Sehen Sie sich außerdem an, wie fehlende Informationen behandelt werden. Ein brauchbarer Kandidat sollte nicht darauf angewiesen sein, dass jeder Fall perfekt vorbereitet ist. Rückfragen, gekennzeichnete Lücken und eine klar benannte Unterbrechung können Teil einer guten Lösung sein.

Schließlich muss das Ergebnis beurteilbar sein. Bei einem Lieferantenvergleich können Sie etwa kontrollieren, ob beide Angebote über dieselbe Laufzeit betrachtet wurden. Bei einer Prozessbeschreibung prüfen Sie, ob auch ein dokumentierter Ausnahmefall vorkommt. Bleibt unklar, woran Sie Erfolg erkennen, ist es für eine belastbare Bewertung zu früh.

Diese Kriterien ersetzen noch keine ausführliche Prüfung. Sie helfen Ihnen, einen Kandidaten auszuwählen, dessen Erprobung sich lohnt. Die späteren Kapitel vertiefen die technische Einrichtung, die Herkunft der Dateien und die Bewertung ihrer Ergebnisse.

## 1.10 Was das für Ihre Rolle bedeutet

### Für Geschäftsführer

Lassen Sie sich den geplanten Skill anhand einer konkreten Aufgabe erklären. Fragen Sie nach dem heutigen Aufwand, dem vorgesehenen Ergebnis und der verantwortlichen Person für die Freigabe. Eine Vorführung mit einem gelungenen Beispiel ist ein Einstieg, aber noch keine Grundlage für eine unternehmensweite Einführung.

Trennen Sie den Wunsch nach Entlastung von der Entscheidung über Befugnisse. Ein Skill kann für die Vorbereitung eines Angebots geeignet sein, ohne selbst Angebote versenden zu dürfen. Legen Sie zunächst fest, welcher Arbeitsschritt verbessert werden soll und wer das Ergebnis beurteilt.

### Für IT-Leiter

Untersuchen Sie den Unterschied zwischen Anleitung und Ausführung. Enthält das Paket nur Text, oder werden Skripte, Dateien und externe Dienste vorausgesetzt? Prüfen Sie insbesondere, ob die beschriebenen Zugriffe in Ihrer Umgebung tatsächlich möglich und passend begrenzt sind.

Für einen ersten Versuch ist eine nachvollziehbare, getrennte Testablage hilfreich. Halten Sie fest, welche Fassung des Skills und welche Eingaben verwendet wurden. So lässt sich später erkennen, ob eine Änderung aus dem Skill, dem Ausgangsmaterial oder der Umgebung stammt.

### Für Selbstständige

Beginnen Sie mit einem Ablauf, den Sie häufig wiederholen und selbst gut kontrollieren können. Ein Gesprächsprotokoll, eine Leistungsabgrenzung oder ein wiederkehrender Bericht kann dafür geeignet sein. Wählen Sie zunächst einen Kandidaten mit wenigen Voraussetzungen, damit die Einrichtung nicht mehr Aufmerksamkeit beansprucht als die Aufgabe.

Betrachten Sie Ihre persönliche Prüfung als Teil der Leistung. Ein schneller Entwurf spart erst dann Arbeit, wenn Sie ihn mit vertretbarem Aufwand in ein verwendbares Ergebnis überführen können. Beobachten Sie deshalb auch, welche Fehler Sie regelmäßig korrigieren müssen.

### Für Abteilungsleiter

Klären Sie mit dem Team, was ein gutes Ergebnis ausmacht. Wenn mehrere Beschäftigte dieselbe Aufgabe unterschiedlich verstehen, braucht es zuerst gemeinsame Kriterien. Ein Skill kann diese Kriterien anschließend ausdrücken und bei der Bearbeitung verfügbar machen.

Nutzen Sie den ersten Versuch als Gespräch über den Ablauf. Welche Rückfragen treten immer wieder auf? Welche Ausnahme kennt bisher nur eine Person? Auf diese Weise wird auch sichtbar, welches Erfahrungswissen noch dokumentiert werden muss, bevor eine KI damit arbeiten kann.

## 1.11 Ihre erste Aufgabe

Wählen Sie eine wiederkehrende Tätigkeit und beschreiben Sie sie in einem Satz. Ergänzen Sie anschließend, welche Informationen zu Beginn vorliegen und welches Ergebnis am Ende benötigt wird. Versuchen Sie dabei, das Ergebnis so zu benennen, dass ein anderer Mensch seine Brauchbarkeit beurteilen könnte.

Notieren Sie eine typische Lücke und einen typischen Fehler. Beim Protokoll könnte die Lücke ein fehlender Verantwortlicher sein. Der Fehler könnte darin bestehen, einen Vorschlag als Beschluss auszugeben. Damit haben Sie bereits zwei Anforderungen, die später in die Auswahl und Prüfung eines Skills einfließen können.

Legen Sie zum Schluss fest, wer das Ergebnis freigibt. Für diese Übung müssen Sie noch nichts installieren. Sie schaffen die fachliche Grundlage, an der eine spätere technische Umsetzung gemessen werden kann.

### Was Sie aus diesem Kapitel mitnehmen

Ein Skill hält eine Vorgehensweise fest. Seine Wirkung hängt von Eingaben, Materialien und Umgebung ab. Er macht Anforderungen wiederverwendbar; ihre Einhaltung bleibt zu prüfen. Das nächste Kapitel behandelt den wirtschaftlichen Nutzen.
