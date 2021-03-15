---
layout: security.hbs
title: Sicherheit
---

# Sicherheit

## Fehler in Node.js melden

Melde Sicherheitsfehler in Node.js über [HackerOne](https://hackerone.com/nodejs).

Your report will be acknowledged within 24 hours, and you’ll receive a more detailed response to your report within 48 hours indicating the next steps in handling your submission.

Nach der ersten Antwort auf Ihren Bericht das Sicherheitsteam wird versuchen, dich über die Fortschritte auf dem Weg zu einer Korrektur und vollständigen Ankündigung auf dem Laufenden zu halten, und können zusätzliche Informationen oder Hinweise zu dem gemeldeten Problem anfordern.

### Node.js Bug-Bounty Programm

Das Node.js Projekt beschäftigt sich mit einem offiziellen Bug Bounty Programm für Sicherheit Forscher und verantwortliche öffentliche Enthüllungen. Das Programm wird über die HackerOne Plattform verwaltet. Siehe <https://hackerone.com/nodejs> für weitere Details.

## Fehler in einem Drittanbieter-Modul melden

Sicherheitsfehler in Modulen von Drittanbietern sollten ihren jeweiligen Betreuern gemeldet werden und auch über den Knoten koordiniert werden. s Ecosystem Sicherheitsteam via [HackerOne](https://hackerone.com/nodejs-ecosystem).

Details zu diesem Prozess finden Sie im [Security Group Repository](https://github.com/nodejs/security-wg/blob/master/processes/third_party_vuln_process.md).

Vielen Dank für die Verbesserung der Sicherheit von Node.js und seines Ökosystems. Deine Bemühungen und die verantwortungsvolle Offenlegung werden sehr geschätzt und werden anerkannt.

## Offenlegungsrichtlinie

Hier ist die Sicherheits-Offenlegungsrichtlinie für Node.js

* Der Sicherheitsbericht wird empfangen und einem primären Handler zugewiesen. Diese -Person koordiniert den Fix- und Release-Prozess. Das Problem ist bestätigt und eine Liste aller betroffenen Versionen wird ermittelt. Code wird geprüft, um potenzielle ähnliche Probleme zu finden. Fixes sind für alle Releases vorbereitet, die noch in Wartung. Diese Korrekturen werden nicht zum öffentlichen Repository übertragen, sondern lokal bis zur Ankündigung gehalten.

* Ein empfohlenes Embargodatum für diese Verwundbarkeit wird gewählt und ein CVE (Common Schwachstellen und Exposures (CVE®)) wird für die Verwundbarkeit angefordert.

* Am Embargo-Datum wird der Sicherheits-Mailingliste von Node.js eine Kopie der Ankündigung gesendet. Die Änderungen werden in das öffentliche Repository gepresst und neue Builds werden auf nodejs.org bereitgestellt. Innerhalb von 6 Stunden nachdem die Mailingliste benachrichtigt wurde, wird eine Kopie der Ankündigungen im Node.js Blog veröffentlicht.

* Normalerweise wird das Embargodatum 72 Stunden seit der Ausstellung des CVE festgelegt. Dies kann jedoch je nach Schwere des Fehlers oder Schwierigkeiten bei der Anwendung eines Fehlers variieren.

* Dieser Prozess kann einige Zeit in Anspruch nehmen, insbesondere wenn eine Koordinierung mit den Betreuern anderer Projekte erforderlich ist. Es werden alle Anstrengungen unternommen, um den Fehler so rechtzeitig wie möglich zu behandeln; ist es jedoch wichtig, dass wir den oben genannten Release-Prozess verfolgen, um sicherzustellen, dass die Offenlegung in einer konsistenten Art und Weise behandelt wird.

## Empfange Sicherheitsupdates

Sicherheitsbenachrichtigungen werden über die folgenden Methoden verteilt.

* <https://groups.google.com/group/nodejs-sec>
* [https://nodejs.org/de/blog/](https://nodejs.org/en/blog/)

## Kommentare zu dieser Richtlinie

Wenn Sie Vorschläge haben, wie dieser Prozess verbessert werden könnte, senden Sie bitte einen [Pull-Request](https://github.com/nodejs/nodejs.org) oder [erstellen Sie ein Problem](https://github.com/nodejs/security-wg/issues/new) zur Diskussion.
