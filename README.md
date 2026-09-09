# Skills, die Geld verdienen

Buch und Skill-Quellen von Robert Meyer. VitePress mit manuell gestarteter Veröffentlichung auf GitHub Pages.

## Lokal

Node.js 22 oder neuer. `npm ci`, dann `npm run docs:dev`. Produktionsprüfung: `npm run docs:build` und `npm run docs:preview`.

## Einmalige Einrichtung und Veröffentlichung

1. Repository Settings → Pages → Source: GitHub Actions.
2. Actions → Website manuell veröffentlichen → Run workflow → main.
3. Nach erfolgreichem Lauf: https://rmdroid.github.io/skills-die-geld-verdienen/

Kein Push-Trigger und kein Zeitplan. Änderungen werden erst beim nächsten manuellen Lauf veröffentlicht.

## Passwort und Öffentlichkeit

Die Buchseiten und die Skill-Übersicht zeigen eine lokale Passwortabfrage. Passwort: Skills_2026. Sie ist nur eine Zugangshürde für normale Besucher. Das öffentliche Repo sowie ausgelieferte Dateien sind ohne Passwort lesbar; dies ist kein vertraulicher oder zahlungspflichtig abgesicherter Bereich. Keine lokale Volltextsuche, damit kein zusätzlicher frei zugänglicher Suchindex entsteht.

## Domain und Amazon

Die separate Landingpage liegt unter landingpage/. Sie kann nach Domainbestellung auf einem statischen Webspace unter skills-die-geld-verdienen.de bereitgestellt werden. Kein CNAME für dieses Pages-Projekt setzen, wenn die Buchadresse bei github.io bleiben soll. Die Landingpage verlinkt die öffentliche Leseprobe und den Lesebereich. Der tatsächliche Amazon-Produktlink fehlt noch; keinen erfundenen ASIN-Link einsetzen.

## Inhalte

Die Kapitel liegen in docs/buch/. Die zwölf Originalquellen sind in skills.json und docs/skills.md dokumentiert. Es werden keine fremden Skill-Dateien als eigene Pakete ausgegeben. Anpassungen und tatsächliche Laufzeittests stehen separat aus.

## Rechte

Buchtexte, Cover und Abbildungen: © Robert Meyer, 2026. Alle Rechte vorbehalten. Öffentliche Lesbarkeit ist keine allgemeine Weiterverwendungslizenz. Für externe Skill-Quellen gelten die Lizenzen ihrer jeweiligen Urheber.
