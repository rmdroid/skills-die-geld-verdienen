---
protected: true
---

# 4. Vom GitHub-Link zum ersten brauchbaren Ergebnis

Auf GitHub findet Lindenwerk einen Skill, dessen Beschreibung gut zur Anfragebearbeitung passt. Die Seite enthält eine Einführung, mehrere Ordner und einen Installationshinweis. Das Team könnte sofort den vorgeschlagenen Befehl ausführen. Zunächst möchte es jedoch verstehen, welche Dateien es übernimmt und was davon für den eigenen Versuch gebraucht wird.

Dieser Zwischenschritt ist keine Formalität. Er verbindet die Auswahl eines interessanten Fundes mit einer nachvollziehbaren Anwendung. Sie müssen dafür kein Entwickler werden. Sie sollten eine Projektbeschreibung, eine Skill-Datei, eine Version und zusätzliche Bestandteile unterscheiden können. Genau darum geht es in diesem Kapitel.

## 4.1 Eine Repository-Seite lesen

Ein Repository ist eine verwaltete Sammlung von Dateien mit einer Änderungsgeschichte. Auf seiner Startseite finden Sie meist eine Einführung, häufig in einer Datei namens README. Sie erklärt, was das Projekt anbieten möchte und wie es verwendet werden soll. Diese Beschreibung ist eine Orientierung; sie ist noch kein Nachweis, dass der Skill zu Ihrer Aufgabe passt.

Suchen Sie den konkreten Skill-Ordner. Eine große Sammlung kann sehr unterschiedliche Aufgaben enthalten. Der Titel des gesamten Projekts sagt dann wenig über einen einzelnen Bestandteil aus. Öffnen Sie die zugehörige SKILL.md und lesen Sie auch Hinweise zu zusätzlichen Dateien und Voraussetzungen.

Achten Sie darauf, wer die Sammlung betreut und ob die Beschreibung zur vorhandenen Ordnerstruktur passt. Eine Anleitung, die auf nicht mehr vorhandene Dateien verweist, deutet auf zusätzlichen Klärungsbedarf hin. Eine hohe Zahl von Sternen kann Aufmerksamkeit zeigen. Sie ersetzt keine inhaltliche Prüfung des ausgewählten Skills.

## 4.2 Die Herkunft für später festhalten

Notieren Sie den Eigentümer des Repositorys, seinen Namen, den Pfad des Skills und den verwendeten Versionsstand. Das Datum des Downloads ist ebenfalls hilfreich, reicht allein aber nicht aus. Wenn die Sammlung später verändert wird, möchten Sie die damals verwendeten Dateien wiedererkennen können.

GitHub unterscheidet unter anderem Branches, Tags und Commits. Ein Branch wie main bezeichnet einen Entwicklungszweig, dessen Inhalt sich ändern kann. Ein Tag kennzeichnet häufig einen benannten Stand. Ein Commit bezeichnet einen konkreten Stand der Änderungsgeschichte. Für einen nachvollziehbaren Buchbezug ist ein festgehaltener Commit besonders hilfreich; die zugehörigen Dateien sollten zusätzlich aufbewahrt werden.

Eine Release-Seite kann eigens zusammengestellte Downloadpakete enthalten. Diese sind nicht zwangsläufig identisch mit dem vollständigen Quellarchiv. Lesen Sie deshalb, was das jeweilige Paket enthält. Ein Archiv des gesamten Repositorys ist nicht automatisch das richtige Installationspaket für Ihre Oberfläche.

## 4.3 Lizenz und Weitergabe einordnen

Ein öffentlich sichtbares Repository bedeutet nicht, dass jede Art der Weiterverwendung erlaubt ist. Suchen Sie die Lizenzdatei und prüfen Sie, ob einzelne Ordner oder mitgelieferte Materialien abweichende Hinweise enthalten. Für unsere Buchsammlung werden Herkunft, Lizenz und Änderungen je übernommenem Bestandteil dokumentiert.

Lässt sich eine ausreichende Erlaubnis für die geplante Verwendung nicht feststellen, behandeln wir den Fund zunächst als Referenz und stellen keine Kopie zum Download bereit. Eine selbst geschriebene Erläuterung und die Weiterverteilung fremder Dateien sind unterschiedliche Handlungen. Die Entscheidung zur Aufnahme in die Sammlung muss deshalb vor dem Kopieren getroffen werden.

Auch bei einer grundsätzlich passenden Lizenz bleiben die konkreten Bedingungen zu beachten. Entfernen Sie vorhandene Urheber- und Lizenzhinweise nicht beiläufig beim Aufräumen. Wenn die Einordnung unklar ist, wird sie vor der Veröffentlichung geklärt. Für den Leser soll später erkennbar sein, welche Bestandteile unverändert übernommen und welche bearbeitet wurden.

## 4.4 Das passende Material herunterladen

Für einen ersten Einblick können Sie Dateien direkt auf GitHub lesen. Zum Download eines vollständigen Quellarchivs bietet GitHub auf der Repository-Seite „Code“ und „Download ZIP“ an. Für einen bestimmten Stand wählen Sie zuvor den entsprechenden Bezug beziehungsweise verwenden dessen Archiv. Ein solches Archiv enthält Dateien, aber keine vollständige lokale Git-Arbeitsumgebung mit Änderungsgeschichte.

Entpacken Sie den Download zunächst in einen eigenen Prüfbereich. Suchen Sie den ausgewählten Skill-Ordner und vergleichen Sie seinen Inhalt mit der Beschreibung. Enthält er nur die Anleitung, oder auch Skripte, Vorlagen und weitere Unterordner? Werden Dateien außerhalb dieses Ordners vorausgesetzt? Die Antworten entscheiden, was für eine vollständige Verwendung übernommen werden muss.

Kopieren Sie nicht vorschnell nur die SKILL.md. Wenn sie auf eine Vorlage verweist, würde diese fehlen. Übernehmen Sie umgekehrt auch nicht ungeprüft eine ganze Sammlung mit zahlreichen weiteren Funktionen. Das Ziel ist ein vollständiges, überschaubares Paket für die ausgewählte Aufgabe.

## 4.5 Vor dem Aktivieren hineinsehen

Lesen Sie zuerst Zweck und Einsatzbedingungen. Geht es um die Aufgabe, die Sie tatsächlich bearbeiten möchten? Prüfen Sie anschließend die vorgesehenen Handlungen. Ein Skill zur Anfrageanalyse sollte nicht überraschend Daten an einen unbekannten Dienst übertragen oder zusätzliche Programme ohne nachvollziehbaren Zweck einrichten.

Bei Skripten reicht eine gut klingende Beschreibung nicht aus. Sie müssen fachkundig geprüft werden, bevor sie in einer dafür geeigneten Umgebung ausgeführt werden. Wenn diese Prüfung für Ihren Einstieg unverhältnismäßig wäre, wählen Sie zunächst einen Kandidaten mit weniger Voraussetzungen. Das ist eine begründete Auswahlentscheidung.

Sehen Sie sich außerdem Beispielausgaben an. Enthalten sie belegbare Aussagen und erkennbare Lücken? Oder füllen sie fehlende Informationen mit plausibel klingenden Angaben? Ein Beispiel kann zeigen, welche Arbeitsweise die Verfasser erwarten. Ob sie zuverlässig eingehalten wird, klären erst Ihre eigenen Versuche.

## 4.6 In der vorgesehenen Umgebung bereitstellen

Für eine lokale projektbezogene Einrichtung in Claude Code liegt der Skill-Ordner unter .claude/skills, für Codex unter .agents/skills. Der jeweilige Unterordner enthält die SKILL.md und ihre benötigten Begleitdateien. Verwenden Sie einen eindeutigen Namen und prüfen Sie anschließend in der Skill-Auswahl, ob der Eintrag erkannt wird. Falls eine Änderung nicht erscheint, kontrollieren Sie den Ablageort und starten die Sitzung gegebenenfalls neu.

In den direkten Chatoberflächen verwenden Sie den vorgesehenen Installations- oder Importweg für Skills beziehungsweise Plugins. Folgen Sie dabei der Anleitung für genau diese Oberfläche und das angebotene Paket. Ein ZIP-Archiv einer großen GitHub-Sammlung kann anders aufgebaut sein als ein erwartetes Skill-Paket. Das Umbenennen der Datei löst diesen Unterschied nicht.

Für Claude beschreibt die offizielle Hilfe die Verwaltung über den Anpassungsbereich und die Skill-Auswahl; die konkrete Darstellung kann sich ändern. Für ChatGPT beschreibt die offizielle Dokumentation Skills und Plugins als Wege zur wiederverwendbaren Bereitstellung. Ein lokaler Ordnerpfad ist deshalb keine allgemeine Installationsanleitung für den Browser.

Wenn Ihre Oberfläche keinen passenden Import anbietet, halten Sie das als Einschränkung fest. Ein manuelles Nachvollziehen der Textanleitung kann den fachlichen Ansatz erproben. Es ersetzt den vollständigen Installationstest nicht. In der späteren Sammlung wird der jeweils geprüfte Weg direkt beim Skill dokumentiert.

## 4.7 Den ersten Auftrag bewusst klein halten

Verwenden Sie eine kurze fiktive Anfrage. Bei Lindenwerk könnte sie lauten: „Wir möchten unsere Dokumentensuche verbessern. Ungefähr 20 Beschäftigte sollen schneller Angebote und Projektunterlagen finden. Welche Systeme betroffen sind, klären wir noch. Können wir dazu ein Erstgespräch vereinbaren?“

Wählen Sie den bereitgestellten Skill ausdrücklich aus. Beschreiben Sie das gewünschte Ergebnis: eine interne Übersicht für die Vorbereitung des Erstgesprächs. Geben Sie an, welche Eingabe maßgeblich ist und dass fehlende Angaben als offene Fragen erscheinen sollen. Diese Hinweise beschreiben den aktuellen Auftrag; sie sind kein vollständiger Skill-Text.

Prüfen Sie dann am Ergebnis, ob es zwischen bekannten Angaben und offenen Punkten unterscheidet. Eine Zahl von 20 Beschäftigten darf auftauchen. Ein Budget, ein verbindlicher Termin oder die Behauptung eines vorhandenen Dokumentenmanagementsystems wäre durch diese Eingabe nicht gedeckt.

## 4.8 Vier typische Fehler gezielt untersuchen

Wird der Skill nicht angezeigt, prüfen Sie Ablageort, Dateinamen und Paketstruktur. Wird er angezeigt, aber nicht verwendet, wählen Sie ihn ausdrücklich aus und stellen eine klar passende Aufgabe. So trennen Sie die Erkennung des Pakets von der automatischen Auswahl.

Wird die Anleitung verwendet, aber eine Datei nicht erzeugt, prüfen Sie die dafür benötigten Werkzeuge und das erwartete Ausgabeformat. Eine sprachliche Zusage, die Datei sei erstellt, genügt nicht. Die Datei muss tatsächlich vorliegen und geöffnet werden können.

Ist das Ergebnis inhaltlich schwach, vergleichen Sie zunächst Eingabe und Vorgaben. Vielleicht fehlt eine entscheidende Information. Vielleicht widersprechen sich Auftrag und Vorlage. Erst danach lohnt es sich, den Skill zu ändern. Andernfalls reparieren Sie womöglich eine Ursache, die in diesem Fall gar nicht vorliegt.

## 4.9 Was das für Ihre Rolle bedeutet

### Für Geschäftsführer

Fordern Sie für aufgenommene Skills einen verständlichen Herkunftsnachweis und eine klare Einsatzbeschreibung. Das muss kein umfangreicher Bericht sein. Entscheidend ist, dass die ausgewählte Datei, ihr Zweck und der verwendete Stand nachvollziehbar sind.

Geben Sie dem Team Zeit für einen vollständigen ersten Durchlauf. Eine Installation ohne Ergebnisprüfung ist noch keine erfolgreiche Einführung.

### Für IT-Leiter

Prüfen Sie neben der Anleitung auch referenzierte Dateien, Abhängigkeiten und mögliche Verbindungen. Achten Sie darauf, dass die fachliche Prüfung denselben Stand verwendet, den Sie technisch beurteilt haben.

Halten Sie fest, welche Bestandteile tatsächlich installiert wurden. So bleibt bei späteren Problemen erkennbar, ob eine zusätzliche Funktion oder eine Änderung aus einer anderen Quelle hinzugekommen ist.

### Für Selbstständige

Führen Sie eine kleine Liste Ihrer verwendeten Skills mit Quelle, Version und Zweck. Das spart Zeit, wenn ein Download verschwindet oder Sie nach einigen Monaten erneut mit dem Verfahren arbeiten möchten.

Übernehmen Sie für Kundenprojekte nur Varianten, deren Voraussetzungen Sie erklären können. Eine Sammlung mit vielen Funktionen ist für den Einstieg weniger hilfreich als ein passender, überschaubarer Kandidat.

### Für Abteilungsleiter

Lassen Sie den ersten Durchlauf von einer zweiten Person wiederholen. Dabei zeigt sich, welche Schritte bisher nur mündlich oder aus Gewohnheit bekannt sind.

Bewahren Sie ein freigegebenes Beispiel mit Eingabe und erwarteten Merkmalen auf. Neue Nutzer können daran prüfen, ob ihre Einrichtung grundsätzlich passt, bevor sie mit anspruchsvolleren Fällen beginnen.

## 4.10 Ihr erster nachvollziehbarer Durchlauf

Notieren Sie Quelle, Versionsstand, installierten Umfang und Umgebung. Führen Sie eine kleine Aufgabe mit fiktiven Daten aus und speichern Sie Eingabe und unverändertes Ergebnis. Ergänzen Sie, welche Anforderungen erfüllt wurden und welche Beobachtung noch offen ist.

Damit haben Sie mehr erreicht als einen Download. Sie können erklären, welche Dateien Sie verwenden, wo sie arbeiten und woran Sie ein brauchbares Ergebnis erkennen. Diese Grundlage trägt die tägliche Nutzung im nächsten Kapitel.

### Was Sie aus diesem Kapitel mitnehmen

Der Weg vom Fund zur Anwendung umfasst Herkunft, passende Erlaubnisse, vollständige Dateien, eine geeignete Einrichtung und einen überprüften Durchlauf. Ein Download wird erst durch diese Zuordnung zu einem nachvollziehbaren Arbeitsmittel.
