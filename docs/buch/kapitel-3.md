---
protected: true
---

# 3. Die passende Arbeitsumgebung vorbereiten

Ein Kollege führt bei Lindenwerk einen Skill vor. Er wählt einen Ordner aus, nennt die Aufgabe und erhält eine Datei mit einer geordneten Anfrageübersicht. Eine Kollegin versucht denselben Ablauf in ihrem Chat. Sie erhält einen Text, aber keine Datei. Außerdem kann die KI einen Anhang nicht lesen. Beide haben dieselbe Anleitung verwendet. Ihre Arbeitsumgebungen können dennoch unterschiedliche Dinge tun.

Bevor Sie einen Skill beurteilen, sollten Sie deshalb klären, wo er arbeiten soll. Dazu müssen Sie nicht sämtliche Einstellungen eines KI-Produkts kennen. Sie brauchen ein verständliches Bild der benötigten Eingaben, Werkzeuge und Zugriffe. Die konkreten Menüs können sich ändern. Der Zusammenhang zwischen Aufgabe und Voraussetzungen bleibt bestehen.

## 3.1 Vier Bestandteile des Arbeitsplatzes

Betrachten Sie Ihren Arbeitsplatz in vier Teilen. Zunächst gibt es die Oberfläche, in der Sie Aufgaben stellen und Ergebnisse entgegennehmen. Hinzu kommt das Modell, das Informationen verarbeitet und Anweisungen umsetzt. Der dritte Teil sind die Werkzeuge, etwa zum Lesen einer Tabelle oder zum Erstellen einer Datei. Der vierte Teil sind die zugänglichen Daten und Dienste.

Ein Skill beschreibt, wie diese Möglichkeiten für eine bestimmte Aufgabe eingesetzt werden sollen. Er stellt sie nicht allein durch seine Existenz bereit. Eine Anweisung zum Lesen eines Kundenordners hilft nur, wenn die Umgebung diesen Ordner erreichen darf und technisch lesen kann. Eine Anweisung zum Erstellen einer Word-Datei benötigt einen entsprechenden Weg zur Dateierzeugung.

## 3.2 Claude Code und Codex als Arbeitsumgebungen

In Claude Code und Codex können Skills in einer Umgebung eingesetzt werden, die mit Projektdateien und Entwicklungswerkzeugen arbeitet. Das ist auch für betriebliche Dokumentenabläufe interessant. Ein Vorgang kann mehrere Dateien umfassen; Hilfsprogramme können Daten aufbereiten oder Ausgaben erzeugen. Entscheidend bleibt, welche Werkzeuge im konkreten Arbeitsplatz verfügbar sind.

Für lokal verwaltete Skills dokumentiert Claude Code unter anderem projektbezogene Ordner unter .claude/skills. Codex dokumentiert dafür .agents/skills. Diese Pfade gehören zur jeweiligen lokalen Einrichtung. Ein Ordner auf Ihrem Rechner ist nicht allein deshalb auch in einer entfernten Sitzung oder einer anderen Oberfläche verfügbar.

Für Lindenwerks ersten Versuch empfiehlt sich als Arbeitsorganisation ein eigener Projektordner mit fiktiven Eingaben. Die Skill-Dateien und die erwarteten Ausgaben werden getrennt abgelegt. Das erleichtert den Vergleich: Was wurde eingelesen? Was wurde neu erzeugt? Was hat eine Person anschließend verändert?

Ein lokal gestartetes Programm bedeutet außerdem nicht automatisch, dass das Modell vollständig lokal rechnet. Prüfen Sie die tatsächliche Verbindung und die Vorgaben Ihrer Organisation, bevor Sie Geschäftsdaten verwenden. Für die ersten Übungen dieses Buches genügen die fiktiven Daten.

## 3.3 Claude und ChatGPT als direkte Arbeitsoberflächen

Auch in Claude und ChatGPT gehören Skills zum jeweils angebotenen Funktionsumfang. Die Installation und Auswahl erfolgen über die dafür vorgesehenen Funktionen der Oberfläche beziehungsweise über installierbare Pakete. Ob eine bestimmte Funktion im eigenen Konto verfügbar ist, hängt von der konkreten Oberfläche und ihren Freigaben ab. Prüfen Sie das im verwendeten Arbeitsplatz.

Eine entscheidende Unterscheidung ist die zwischen einem aktivierten Skill und einem Text, den Sie in eine Nachricht kopieren. Kopierter Text kann eine Vorgehensweise vermitteln. Damit sind aber noch keine Begleitdateien installiert, keine Werkzeuge eingerichtet und keine wiederkehrende Auswahl sichergestellt.

Für einen einfachen Versuch können Sie eine textbasierte Vorgehensweise mit fiktiven Eingaben nachvollziehen. Bezeichnen Sie diesen Versuch dann auch so. Wenn der eigentliche Skill Skripte oder spezielle Verbindungen voraussetzt, ist die manuelle Textanwendung nur ein begrenzter Vergleich. Sie beweist nicht, dass das vollständige Paket unterstützt wird.

Für die Begleitmaterialien dieses Buches wird deshalb je Skill angegeben, welche Variante für welche Umgebung vorgesehen ist. Eine allgemeine Aussage wie „läuft überall“ wäre zu ungenau. Fachliche Eignung, Installation, Dateiverarbeitung und tatsächlicher Teststatus werden getrennt beschrieben.

## 3.4 Mit dem Ergebnis beginnen

Wählen Sie die Umgebung anhand dessen aus, was am Ende benötigt wird. Wenn Sie eine kurze Übersicht im Chat prüfen und anschließend selbst weiterverarbeiten möchten, ist der technische Bedarf gering. Wenn Sie aus mehreren Tabellen eine formatierte Arbeitsmappe erzeugen müssen, kommen andere Voraussetzungen hinzu.

Lindenwerk beginnt mit einer Anfrageübersicht im Textformat. Sie enthält Bedarf, vorhandene Angaben, offene Fragen und einen vorgeschlagenen nächsten Schritt. Für diesen ersten Versuch muss kein Kundensystem angebunden werden. Das Team kopiert eine fiktive Anfrage in die vorgesehene Eingabe und prüft den Entwurf.

Erst wenn die fachliche Struktur brauchbar ist, betrachtet das Team weitere Schritte: Anhänge lesen, Ergebnisse als Datei ablegen und gegebenenfalls Daten aus einem freigegebenen System übernehmen. So lässt sich erkennen, welcher zusätzliche Aufwand durch die Verbindung entsteht. Der technische Ausbau erhält einen konkreten Zweck.

## 3.5 Einen übersichtlichen Testbereich anlegen

Legen Sie für die Erprobung eine kleine, eindeutige Ablage an. Ein Bereich enthält unveränderte Eingaben. Ein zweiter enthält die verwendete Skill-Version und zugehörige Materialien. Ein dritter enthält Ergebnisse. Eine kurze Notiz hält Datum, Umgebung und Beobachtungen fest.

Bewahren Sie die ursprüngliche Eingabe auf, auch wenn Sie sie später verbessern. Andernfalls ist nicht mehr erkennbar, ob ein besseres Ergebnis durch den Skill oder durch leichteres Ausgangsmaterial entstanden ist. Dasselbe gilt für die Ausgabe: Die unveränderte KI-Fassung und die menschlich korrigierte Fassung erfüllen unterschiedliche Zwecke.

## 3.6 Zugriffe auf die konkrete Aufgabe begrenzen

Fragen Sie für jeden Zugriff, wozu er in diesem Versuch gebraucht wird. Zum Erstellen eines Entwurfs ist ein Versandzugriff häufig unnötig. Zum Auswerten einer exportierten Tabelle muss nicht sofort das gesamte betriebliche System angebunden werden. Ein begrenzter Start macht Fehler leichter überschaubar.

Unterscheiden Sie außerdem Anweisungen und technische Berechtigungen. Ein Satz im Skill kann das gewünschte Verhalten beschreiben. Er ersetzt keine wirksame Zugriffsbeschränkung. Wenn eine Anwendung technisch Dateien verändern kann, sollte die Einrichtung so gestaltet sein, dass der Testbereich und die erlaubten Handlungen zum Versuch passen.

Vermeiden Sie Zugangsdaten in Skill-Dateien und Beispielen. Solche Dateien werden leicht weitergegeben oder in ein Repository aufgenommen. Verbindungen und Zugangsdaten gehören in die dafür vorgesehenen Einstellungen der jeweiligen Umgebung. Die Anleitung kann beschreiben, welche Verbindung benötigt wird, ohne geheime Werte zu enthalten.

## 3.7 Den Arbeitsplatz mit einem kleinen Durchlauf prüfen

Beginnen Sie mit einer Eingabe, deren Inhalt Sie vollständig überblicken. Lassen Sie den vorgesehenen Skill auswählen und eine einfache Aufgabe bearbeiten. Prüfen Sie anschließend, ob die benötigten Materialien tatsächlich verfügbar waren und ob das Ergebnis im erwarteten Format vorliegt.

Eine Selbstauskunft der KI ist dabei nur ein Hinweis. Aussagekräftiger sind sichtbare Schritte, tatsächlich erzeugte Dateien und ein überprüfbares Ergebnis. Wenn eine Vorlage verwendet werden sollte, muss sich ihre Struktur in der Ausgabe wiederfinden. Wenn eine Tabelle gelesen werden sollte, vergleichen Sie mindestens einige Werte mit dem Original.

Notieren Sie, an welcher Stelle der Ablauf endet. Ist die Datei nur erzeugt oder auch an einem vereinbarten Ort abgelegt? Muss sie noch heruntergeladen werden? Was geschieht beim Schließen der Sitzung? Solche Fragen wirken klein, entscheiden aber darüber, ob ein Kollege den Ablauf am nächsten Tag nachvollziehen kann.

## 3.8 Was das für Ihre Rolle bedeutet

### Für Geschäftsführer

Geben Sie den fachlichen Einsatzrahmen vor: Welche Aufgabe wird erprobt, welche Daten sind dafür vorgesehen und wer beurteilt das Ergebnis? Damit kann die IT eine passende Umgebung schaffen, statt allgemeine Vorstellungen von einem KI-Arbeitsplatz erraten zu müssen.

Lassen Sie sich den Weg der Daten in einfachen Worten erklären. Für die Entscheidung reicht häufig ein klares Bild von Eingabe, Verarbeitung und Ablage. Ein Produktname allein beschreibt diesen Weg nicht.

### Für IT-Leiter

Dokumentieren Sie die tatsächlich bereitgestellte Umgebung. Dazu gehören die verwendete Oberfläche, der Ablageort des Skills, notwendige Werkzeuge und die vorgesehenen Zugriffe. Erfassen Sie Abweichungen zwischen lokalen und entfernten Sitzungen.

Sorgen Sie für einen nachvollziehbaren Rückweg aus dem Versuch: Wie wird der Skill deaktiviert, wo liegen erzeugte Dateien und wie werden Verbindungen entfernt, die nicht mehr benötigt werden? Das erleichtert auch spätere Änderungen.

### Für Selbstständige

Beginnen Sie mit einem Arbeitsplatz, dessen Dateien und Ergebnisse Sie selbst sicher verwalten können. Ein übersichtlicher Versuch spart mehr Zeit als eine umfangreiche Einrichtung, deren Zusammenhänge Sie nach einer Woche erneut rekonstruieren müssen.

Trennen Sie Testmaterialien von laufenden Kundenunterlagen. Wenn Sie mehrere Mandate betreuen, geben Sie jeweils nur die für den aktuellen Auftrag vorgesehenen Informationen hinzu. Ein gemeinsamer großer Ordner ist dafür keine gute Arbeitsgrundlage.

### Für Abteilungsleiter

Prüfen Sie den Ablauf auf dem Arbeitsplatz einer zweiten Person. Eine gelungene Vorführung auf dem Rechner des Initiators sagt wenig darüber aus, ob das Team dieselben Voraussetzungen besitzt.

Halten Sie typische Bedienfragen fest. Wo wird der Skill ausgewählt? Welche Datei ist die Eingabe? Wo liegt das Ergebnis? Diese Hinweise gehören in eine kurze Arbeitsanleitung, die neue Nutzer ohne zusätzliche Vorführung verstehen können.

## 3.9 Ihr Arbeitsplatz-Steckbrief

Beschreiben Sie den vorgesehenen Arbeitsplatz auf einer halben Seite: Aufgabe, Oberfläche, Eingabeformat, benötigte Werkzeuge, erlaubte Zugriffe und erwarteter Ablageort. Markieren Sie alle Punkte, die noch nicht überprüft wurden.

Führen Sie anschließend einen kleinen Durchlauf mit fiktiven Daten aus. Ergänzen Sie, was tatsächlich funktioniert hat und wo eine Voraussetzung fehlt. Dieser Steckbrief ist der Ausgangspunkt für die Installation im nächsten Kapitel.

### Was Sie aus diesem Kapitel mitnehmen

Ein Skill arbeitet innerhalb einer konkreten Umgebung. Prüfen Sie deshalb Anweisung, Werkzeuge, Datenzugriff und Ergebnisformat getrennt. Ein übersichtlicher Testbereich und ein einfacher erster Durchlauf machen sichtbar, welche Voraussetzungen für den späteren Einsatz noch fehlen.
